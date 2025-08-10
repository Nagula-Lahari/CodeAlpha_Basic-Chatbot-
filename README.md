# Basic Rule-Based Chatbot 🤖

A simple Python chatbot built for **CodeAlpha's Python Internship (Task 4)**. This chatbot responds to basic user inputs like greetings and farewells using rule-based logic.

## Features ✨
- Responds to **greetings** (`hello`, `hi`, `hey`)
- Answers **"how are you?"** 
- Handles **goodbyes** (`bye`, `goodbye`)
- Graceful handling of **unrecognized inputs**
- Case-insensitive input matching
- Continuous conversation loop until exit

## Tech Stack 💻
- Python 3.x
- Built-in libraries: No dependencies required!

## How to Run 🚀
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CodeAlpha_Basic_Chatbot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CodeAlpha_Basic_Chatbot
   ```
3. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Code Structure 📝
```python
def simple_chatbot():
    # Main loop
    while True:
        user_input = input("You: ").lower().strip()
        
        # Rule-based responses
        if any(word in user_input for word in ["hello", "hi", "hey"]):
            print("Chatbot: Hi there!")
        elif "how are you" in user_input:
            print("Chatbot: I'm doing great, thanks!")
        elif any(word in user_input for word in ["bye", "goodbye"]):
            print("Chatbot: Goodbye! Have a nice day!")
            break
        else:
            print("Chatbot: Sorry, I didn't understand that.")
```

## Demo 💬
```
You: Hello
Chatbot: Hi there!
You: HOW ARE YOU?
Chatbot: I'm doing great, thanks!
You: bye
Chatbot: Goodbye! Have a nice day!
```

## About CodeAlpha Internship 📌
This project was completed as part of **CodeAlpha's Python Programming Internship**.  

🔗 [CodeAlpha Website](https://www.codealpha.tech)  
📧 Contact: services@codealpha.tech

---

Feel free to contribute or suggest improvements! 🚀
```

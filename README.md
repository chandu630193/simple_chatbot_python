# simple_chatbot_python
def run_chatbot():
    print("Chatbot active. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").strip().lower()
        
        if user_input == "hello":
            print("Chatbot: hi!")
        elif user_input == "how are you":
            print("Chatbot: I'm fine, thanks !")
        elif user_input == "what is your name":
            print("Chatbot: made by @chandu")
        elif user_input == "bye":
            print("Chatbot: Goodbye !")
            break 
        else:
            print("Chatbot: I only understand 'hello', 'how are you', and 'bye'.")

run_chatbot()

# -CODSOFT-TASK-1
 def rule_based_chatbot():
    print("🤖 Hello! I'm a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if "hello" in user_input or "hi" in user_input:
            print("Bot: Hello! How can I help you?")
        
        elif "how are you" in user_input:
            print("Bot: I'm just a program, but I'm doing fine. Thanks for asking!")
        
        elif "your name" in user_input:
            print("Bot: I'm RuleBot, your assistant.")
        
        elif "help" in user_input:
            print("Bot: I can answer simple questions like greetings, name, and feelings.")
        
        elif "bye" in user_input:
            print("Bot: Goodbye! Have a great day 😊")
            break
        
        else:
            print("Bot: I'm not sure how to respond to that. Try asking something else.")

# Run the chatbot
rule_based_chatbot()

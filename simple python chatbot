from datetime import datetime
# Function to greet the user
def greet():
    current_time = datetime.now().strftime("%H:%M:%S")
    print(f"Bot: Hello! How can I assist you today? (Current time: {current_time})")

# Function to handle user input
def handle_input(user_input):
    if user_input.lower() == "hello":
        print("Bot: Hi there!")

    elif user_input.lower() == "time":
        current_time = datetime.now().strftime("%H:%M:%S")
        print(f"Bot: The current time is {current_time}.")
    elif user_input.lower() == "bye":
        print("Bot: Goodbye! Have a great day!")
        return False
    else:
        print("Bot: Sorry, I didn't understand that.")

    return True

# Main function to run the chatbot
def run_chatbot():
    greet()
    running = True

    while running:
        user_input = input("User: ")
        running = handle_input(user_input)

run_chatbot()

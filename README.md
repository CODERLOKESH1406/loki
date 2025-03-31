#bank balnce
command = ""
name = ""
account_number = ""
password = ""

while command != "hi":
    command = input("Hi: ").strip().upper()
    
    if command == "HELLO":
        print("Hello sir, this is Max.")
        print("How can I help you, sir?")
    
    elif command.lower() == "can i know my bank balance?":
        name = input("Ok sir! What is your name? ").strip()
        
        if name.lower() == "lokesh":
            account_number = input("What is your account number? ").strip()
            
            if account_number == "1234567890":
                password = input("Enter your password: ").strip()
                
                if password == "14062004":
                    print("Your bank balance is 40,00,000")
                    break
                else:
                    print("Incorrect password.")
            else:
                print("Invalid account number.")
        else:
            print("Name not recognized.")

print("Thank you for banking with us.")

'''The Caesar cipher is a way to change the letters in a message by shifting them a certain number of places in the alphabet. The "key" is the letter that tells you how many places to shift. For example:

- A key "D" means you shift every letter 3 places forward (A becomes D, B becomes E, etc.).
- A key "M" means shift 12 places forward.
- A key "A" means no shift.
- A key "Z" can mean either shift 25 places forward or 1 place backward.

For example, if you shift "CAESAR" with a key "P" (which means 15 places forward), it becomes "RPTHPG."

This program will decrypt messages that used the Caesar Cipher.
'''

def encryption():
    print("Encryption function!")
    again()
    
def decryption():
    print("Decryption function!")
    again()

def again():
    again_answer = input("Do you want to do another message? 'y' or 'n'")
    if again_answer == 'y':
        prompt_user()
    if again_answer == 'n':
        print("The program has ended, have a nice day!")
        exit()
  
def prompt_user():
    while True:
        answer = input("Do you want to encrypt ('e') or decrypt ('d') a message with the Caesar cipher?")
        if answer == 'e':
            encryption()
            break
        elif answer == 'd':
            decryption()
            break
        else:
            print("Invalid input, please enter 'e' for encryption or 'd' for decryption.")

prompt_user()

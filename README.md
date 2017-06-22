start = '''
You work at Trump Co.
'''

print(start)

print("Type 'male' or 'female.")
user_input = input()
if user_input == "male":
    print("You're a new employee and just got a pay raise!")
    print("Type 'gf' to treat your gf on a date or type 'boyz' to treat your boys to a boy's night.")
    user_input = input()
    if user_input == "gf":
        print("Your girlfriend loved the date and you got lucky tonight! ;)")
        print("Flash forward: your girlfriend is pregnant...")
        print("Type 'bye' to leave her or type 'paternity' to ask boss for paternity leave")
        user_input = input()
        if user_input == "bye":
            print("You felt bad.. for like a day. But now you're enjoying the single life! The end.")
            print("Congrats. You are a priveleged male who gets what he wants")
        elif user_input == "paternity":
            print("Your boss is very supportive and gives you a month of much deserved paid leave. You live happily. The end.")
            print("Congrats. You are a priveleged male who gets what he wants")
        else:
            print("Incorrect input! Try again.")
    elif user_input == "boyz":
        print("You partied hard with the boys and had a great time! The end.")
        print("Congrats. You are a priveleged male who gets what he wants")
    else:
        print("Incorrect input! Try again.")
elif user_input == "female":
    print("You've been working here for 5 yrs without any promotions but a new male employee just got a pay raise. YOU'RE IN RAGE MODE")
    print("Type 'confront' to confront boss or type 'say nothing' to stay quiet.")
    user_input = input()
    if user_input == "confront":
        print("Your boss fires you and you end up living on the streets.")
        print("A shady man offers you a job as a stripper at his night club. An old rich guy offers to be your sugar daddy.")
        print("Type 'stripper' to accept offer 1 or type 'sugar baby' to take offer 2.")
        user_input = input()
        if user_input == "stripper":
            print("You choose the life of a stripper... but what about your baby???")
            print("Type 'adopt' to give up your baby for adoption or type 'keep' to bare that baby bump.")
            user_input = input()
            if user_input == "adopt":
                print("You're able to focus on your job but never see your baby again. The end.")
                print("Good luck in the future as a woman")
            elif user_input == "keep":
                print("You struggle to provide for both yourself and the baby. The end.")
                print("Good luck in the future as a woman")
            else:
                print("Incorrect input! Try again.")
        elif user_input == "sugar baby":
            print("Your sugar daddy buys you a lot of stuff. The end.")
            print("Good luck in the future as a woman")
        else:
            print("Incorrect input! Try again.")
    elif user_input == "say nothing":
        print("You keep recieving the same low pay for the next five years during which you get married and pregnant. You ask your boss for maternity leave.")
        print("Type 'week' for two weeks of paid leave or type 'month' for one month of unpaid leave.")
        user_input = input()
        if user_input == "week":
            print("Your suffer from PPD but don't have enough free time to get treatment. The end.")
            print("Good luck in the future as a woman in the industry")
        elif user_input == "month":
            print("Your husband must work over time to support family financially and you must care for children as well as yourself as you recieve treatment for PPD. The end.")
            print("Good luck in the future as a woman in the industry")
        else:
            print("Incorrect input! Try again.")
    else:
        print("Incorrect input! Try again.")
else:
    print("Incorrect input! Try again.")

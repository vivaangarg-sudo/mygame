game_on = True
has_key = False

while game_on == True:
    print('Welcome to the game!')
    print('Chose Your Path, You may go left or right')
    Path = input('Path: ')
    
    # --- FIRST CHOICE SECTION ---
    if Path == 'left': 
        print("you find a key, it is old and rusty, but it might be useful later.")
        has_key = True
    elif Path == 'right': 
        print("The dirt path continues into the foggy forest, you can not see anything but you know danger lies ahead.")
        has_key = False
    else:
        print('Invalid choice, please choose left or right. You have 2 more mistakes left before it comes. Please try again.')
        print('Chose Your Path, You may go left or right') 
        Path = input('Path: ')
        if Path == 'left': 
            print("you find a key, it is old and rusty, but it might be useful later.")
            has_key = True
        elif Path == 'right': 
            print("The dirt path continues into the foggy forest, you can not see anything but you know danger lies ahead.")
            has_key = False

    # --- SECOND CHOICE SECTION ---
    next_choice = input('Do you want to go straight or turn left? ')
    
    if next_choice == 'straight':
        if has_key == True:
            print("You continue down the path to find a treasure chest, you use the key to open it and find a pile of gold coins, you bribe any monster that comes by and win the game!!!.")
            game_on = False
        else:
            print("You continue down the path to find a treasure chest, while trying to open it you are ambushed by a monster and lose the game.")
            game_on = False
            
    elif next_choice == 'left':
        print("The path leads to a dead end, however you spot a tree that has berries on it, you can eat them to regain some health and stamina.")
            
    else:
        # 🌟 FIXED TYPO BOX: Now checks your correction!
        print('Invalid choice, please choose straight or left. You have 1 more mistake left before it comes')
        next_choice = input('Do you want to go straight or turn left? ')
        
        if next_choice == 'straight':
            if has_key == True:
                print("You continue down the path to find a treasure chest, you use the key to open it and find a pile of gold coins, you bribe any monster that comes by and win the game!!!.")
                game_on = False
            else:
                print("You continue down the path to find a treasure chest, while trying to open it you are ambushed by a monster and lose the game.")
                game_on = False
        elif next_choice == 'left':
            print("The path leads to a dead end, however you spot a tree that has berries on it, you can eat them to regain some health and stamina.")

    # --- THIRD CHOICE SECTION ---
    if game_on == True:
        Next_choice = input('Do you want to go straight or turn right? ')
        if Next_choice == 'straight':
            if has_key == True:
                print("You continue down the path to find a treasure chest, you use the key to open it and a mysterious gas escapes from the chest, you slowly lose conciousness and die, you lose the game.")
                game_on = False
            else:
                print("You continue down the path to find a button, out of hunger curiosity you press it and a trapdoor opens beneath you, you fall into a pit and die.")
                game_on = False
        else:
            print('Invalid choice, please choose straight or right. You have 1 more mistake left before it comes')
            Next_choice = input('Do you want to go straight or turn right? ')
            if Next_choice == 'straight':
                if has_key == True:
                    print("You continue down the path to find a treasure chest, you use the key to open it and a mysterious gas escapes from the chest, you slowly lose conciousness and die, you lose the game.")
                    game_on = False
                else:
                    print("You continue down the path to find a button, out of hunger curiosity you press it and a trapdoor opens beneath you, you fall into a pit and die.")
                    game_on = False

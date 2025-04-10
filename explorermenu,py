#this explorer was written by an inexperienced editor, so problems may well occur during use
#explorer-menu v1.0.0        #version VSC 1.99.1 (user setup)            #python 3.13.2 64bit        OS: Windows_NT x64 10.0.19045

#this code is publicly available, any user has the right to edit this code 

#conditions for publishing the code you modified:                       
# #be sure to mention the page https://github.com/m2uroy
#When publishing the modified explorer menu in the version, mention cv (community version), that is, when changing the v1.0.0 version, you must publish it as v1.0.0cv

#it was developed by user m2uroy

#recommendations
#use the program on behalf of the administrator to work correctly     #use the program if you are confident in your actions, I am not responsible for the consequences
#all notes are written in english, through a translator

#do you have any ideas? you can suggest them by writing to my telegram @m2uroy                    #we have a telegram channel @explorermenu
#the idea of the code: entertainment and small, simple operations

import time
import os

from colorama import init, Fore # type: ignore
init()
print(Fore.CYAN + """                  
                  _                                                       
                 (_ )                                                     
   __       _ _   | |   _   _ __   __  _ __    ___ ___    __   ___  _   _ 
 / __ \ \/ )  _ \ | | / _ \(  __)/ __ \  __) /  _   _  \/ __ \  _  \ ) ( )
(  ___/)  (| (_) )| |( (_) ) |  (  ___/ |    | ( ) ( ) |  ___/ ( ) | (_) |
 \____)_/\_)  __/(___)\___/(_)   \____)_)    (_) (_) (_)\____)_) (_)\___/ 
           | |                                                            
           (_)                               v1.0.0                                              
""")


def create_file():
    folder_path = input("\nEnter the path where you want to create the file.: ")
    file_name = input("\nEnter the file name (with the extension, the format: example.txt): ")
    file_path = os.path.join(folder_path, file_name)

    try:
        with open(file_path, 'w') as file:
            file.write("")  
        print(f"File {file_name} successfully created by directory {folder_path}.")
    except FileNotFoundError:
        print("The specified folder path is incorrect. Please check it out..")
    except Exception as e:
        print(f"An error has occurred: {e}")

def menu():
    while True:
        print(Fore.WHITE + "\nMenu")
        print(Fore.WHITE + "1. Create File")
        print(Fore.WHITE + "2. Exit")
        
        choice = input("Enter the option number: ")

        if choice == '1':
            create_file()
        elif choice == '2':
            print("Exiting the program...")
            time.sleep(2)
            break
        else:
            print("Incorrect input. Choose 1 or 2.")

if __name__ == "__main__":
    print("\nYou are in a file creation environment")
    menu()

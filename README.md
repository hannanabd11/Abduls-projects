# Abduls-projects
it is my first project
import os
import pyttsx3
engine = pyttsx3.init()
if __name__=='__main__':
    while True:
        x=input('Enter what u want to speak: ')
        if x=='q':
            engine.say('bye bye see u again')
            engine.runAndWait()
            print("Bye bye see u again,Thanks for using. h")
            break
        command=engine.say(x)
        engine.runAndWait()
        
        
        

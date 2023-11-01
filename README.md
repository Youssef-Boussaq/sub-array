
import time

def animation_hello():
    mot = "Hello"
    while True:
        for i in range(len(mot)):
            print(mot[i % len(mot)], end='\r')
            time.sleep(0.5)

animation_hello()

<h1 align = "center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=lora+Code&size=75&duration=2000&pause=550&color=FF72FF&background=000000EE&center=true&multiline=true&width=1920&height=384&lines=Hello+world" alt="Typing SVG" /></a>
</h1>
import time

def animation_hello():
    mot = "Hello"
    while True:
        for i in range(len(mot)):
            print(mot[i % len(mot)], end='\r')
            time.sleep(0.5)

animation_hello()

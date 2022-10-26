# trinket

basically, it is required to make the shape of elephant by coding in the website: https://trinket.io/sense-hat. I have process these steps until the line 32, and I got a issue report, which said "TypeError: elephant() takes exactly 3 arguments (0 given) on line 32 in main.py" and I have no clue how to fix it. 

my coding it is below:
def elephant (o,c1,c2):
    elephant = [
    o, o, c1, c1, o, o, o, o,
    o, c1, c1, c1, c1, c1, c1, o,
    c1, o, c1, c1, c1, c1, c1, c1,
    c1, c1, c1, c1, c1, c1, c1, c1,
    c1, c2, c2, c1, c1, c1, c1, c1,
    c1, o, c1, c1, c1, c1, c1, c1,
    c1, o, c1, c1, o, c1, c1, o,
    c1, o, c2, c1, o, c2, c1, o,
]
    return elephant()
    
images = [elephant]
count = 0

while True: 
    s.set_pixels(images[count % len(images)]())
    time.sleep(.75)
    count += 1

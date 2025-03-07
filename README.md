# Visual-Code-Stuio
#My first program
t = 1
import time
def countdown(t):
    while t > 0:
        t -= 1
        time.sleep(1)
import turtle
screen = turtle.Screen().bgcolor('white')
for i in range(2):
    from turtle import *
    pensize(20)
    color("black")
    circle(50)
    color("white")
    circle(50)
import turtle 
turtle.color('black')
style = ('Courier', 30, 'italic') 
name = turtle.textinput("What is your name?", "Name:")
pensize = 0
while True:
    want = turtle.textinput('What do you wanna do?','Do you want to play a quiz game, open a calculator or stop the program?')
    want = want.lower()
    if want == 'open a calculator':
        while True:
            from calculator import *
            import math
            what = turtle.textinput('What do you wanna do?','Do you want to subtract 2 numbers, add 2 numbers , divide 2 numbers or multyply 2 numbers? ')
            what = what.lower()
            x = numinput('Number', 'Number:', default=None, minval=None, maxval=None)
            y = numinput('Number', 'Number:', default=None, minval=None, maxval=None)
            if what == 'subtract':
                turtle.write('The answer is:',font=style, align='center')
                countdown(t)
                turtle.clear()
                turtle.write(subtract(x,y), font=style, align='center')
                countdown(t)
                turtle.clear()
            if what == 'add':
                turtle.write('The answer is:', font=style, align='center')
                countdown(t)
                turtle.clear()
                turtle.write(add(x,y), font=style, align='center')
                countdown(t)
                turtle.clear()
            if what == 'divide':
                turtle.write('The answer is:', font=style, align='center')
                countdown(t)
                turtle.clear()
                turtle.write(divide(x,y), font=style, align='center')
                countdown(t)
                turtle.clear()
                turtle.clear()
            if what == 'multyply':
                turtle.write('The answer is:', font=style, align='center')
                countdown(t)
                turtle.clear()
                turtle.write(add(x,y), font=style, align='center')
                countdown(t)
                turtle.clear()
            stop = turtle.textinput('Another one?','Do you what to make another operation(yes or no)? ')
            stop = stop.lower()
            if stop == 'no':
                turtle.write('See you soon!', font=style, align='center')
                print(' ')
                countdown(t)
                turtle.clear()
                break          
    if want == 'play a quiz game':
        score = 0
        turtle.write('What kind of game is minecraft?', font=style, align='center')
        q1 = turtle.textinput('Question 1','Answer: ')
        q1 = q1.lower()
        if q1 == 'sandbox':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('Who invented the theory of relativity?', font=style, align='center')
        q2 = turtle.textinput('Question 2','Answer: ')
        q2 = q2.lower()
        if q2 == 'albert einstein':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('What is the chemical compotision of water?', font=style, align='center')
        q3 = turtle.textinput('Question 3','Answer: ')
        q3 = q3.lower()
        if q3 == 'h2o':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('When did WW2 end?', font=style, align='center')
        q4 = turtle.textinput('Question 4','Answer: ')
        q4 = q4.lower()
        if q4 == '1945':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('When did WW2 start?', font=style, align='center')
        q5 = turtle.textinput('Question 5','Answer: ')
        q5 = q5.lower()
        if q5 == '1939':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('What is the most eaten type of meat?', font=style, align='center')
        q6 = turtle.textinput('Question 6','Answer: ')
        q6 = q6.lower()
        if q6 == 'chicken':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('When was the PS4 relesed?', font=style, align='center')
        q7 = turtle.textinput('Question 7','Answer: ')
        q7 = q7.lower()
        if q7 == '2013':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('What do you get when you dry and burn clay?', font=style, align='center')
        q8 = turtle.textinput('Question 8','Answer: ')
        q8 = q8.lower()
        if q8 == 'cermaic' or q8 == 'terracota' or q8 == 'bricks':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('In what year was the Fortnite battle royale relesed?', font=style, align='center')
        q9 = turtle.textinput('Question 9','Answer: ')
        q9 = q9.lower()
        if q9 == '2017':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('In what year was PokemonGO relesed?', font=style, align='center')
        q10 = turtle.textinput('Question 10','Answer: ')
        q10 = q10.lower()
        if q10 == '2016':
            turtle.clear()
            turtle.write('CORRECT!', font=style, align='center')
            score += 1
            countdown(t)
            turtle.clear()
        else:
            turtle.clear()
            turtle.write('INCORRECT',font=style, align='center')
            countdown(t)
            turtle.clear()
        turtle.write('-----RESULTS-----',font=style,align='center')
        countdown(t)
        turtle.clear()
        if score == 1:
            turtle.write('You got 1 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 2:
            turtle.write('You got 2 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 3:
            turtle.write('You got 3 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 4:
            turtle.write('You got 4 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 5:
            turtle.write('You got 5 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 6:
            turtle.write('You got 6 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 7:
            turtle.write('You got 7 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 8:
            turtle.write('You got 8 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 9:
            turtle.write('You got 9 out of 10 questions!',font=style, align='center')
            countdown(t)
            turtle.clear()
        if score == 0:
            turtle.write("Aww how unlucky, you only got 0 questions right? Well that's too bad.",font=style,align='center')
            countdown(t)
            turtle.clear()
        if score == 10:
            turtle.write('Wow, congratulations you got 10 out of 10 questions right!',font=style,align='center')
            countdown(t)
            turtle.clear()
    if want == 'stop the program':
        turtle.write('Goodbye!!!',font=style,align='center')
        countdown(t)
        break

# mad-libs-
#hi

import random
import time

def rules():
    print('                                                                                                 H O W    T O    P L A Y  ?')
    line()
    print()
    print('''                                       > One player acts as the “reader” and asks the other players,who haven't seen the story,to fill in the blanks with
                                                                       adjectives, nouns, exclamations, colors, adjectives, and more.''')
    print("                                             > These words are inserted into the blanks and then the story is read aloud to give hilarious results.")
    print("                                                                                > There are no winners or losers, only laughter.")
    print()
    line()
    
def exits():
    print('------------------------------------------------------                                 Thank you for playing the game                                 ------------------------------------------------------')


def haunted_story1():
    print('\n')
    print('Enter an adjective: ')
    adj1=input()
    print("Enter a girl's name: ")
    name1=input()
    print('Enter an adjective: ')
    adj2=input()
    print('Enter a noun: ')
    noun1=input()
    print('Enter an animal: ')
    animal=input()
    print('Enter a verb ending with -ing: ')
    verb1=input()
    print('Enter an adverb: ')
    adverb1=input()
    print('Enter an adjective: ')
    adj3=input()
    print("Enter a boy's name: ")
    name2=input()
    print('Enter an adjective: ')
    adj4=input()
    print('Enter a noun: ')
    noun2=input()
    print('Enter a verb ending with -ing: ')
    verb2=input()
    print('Enter a plural noun: ')
    pnoun=input()
    print('Enter verb ending with -ing:')
    verb3=input()
    print()
    for i in 'proccessing story.....':
        print(i,end='')
        time.sleep(0.15)
    print('\n')
    print('''             They say my school is haunted; my''',adj1,'''friend,''',name1,
            '''says she saw a''',adj2,noun1,'''floating at the end of the hall
              near down the hallway at night, you'll hear a''',animal,verb1,adverb1,
            '''My''',adj3,'''friend''',name2,'''saw a''',adj4,noun2,verb2,'''under one of
            the tables once. I hope I never see any''',pnoun,verb3,'''eating lunch there, is scary enough!''')
    

def haunted_story2():
    print('\n')
    print('Enter a colour: ')
    colour1=input()
    print('Enter a verb ending with -ed: ')
    verb1=input()
    print('Enter a number: ')
    num1=input()
    print('Enter an animal: ')
    animal=input()
    print('Enter an adjective: ')
    adj1=input()
    print('Enter a tool: ')
    tool=input()
    print('Enter a vegetable: ')
    veg=input()
    print('Enter a vessel: ')
    vessel=input()
    print('Enter a colour : ')
    colour2=input()
    print('Enter a noun: ')
    noun1=input()
    print('Enter a fruit: ')
    fruit1=input()
    print('Enter a type of candy: ')
    candy=input()
    print('Enter a noun: ')
    noun2=input()
    print('Enter a noun: ')
    noun3=input()
    print('enter a verb')
    verb2=input()
    print('Enter a type of furniture: ')
    furniture=input()
    print('Enter a colour: ')
    colour3=input()
    print('Enter a plural noun: ')
    pnoun=input()
    print('Enter a noun: ')
    noun4=input()
    print()
    for i in 'proccessing story.....':
        print(i,end='')
        time.sleep(0.15)
    print('\n')
    
    print('''Today we had a substitute teacher for science class, with''',colour1,
          '''hair that''',verb1,'''straight up''',num1,'''inches high. His name was
            Mr.''',animal,'''and he said he'd show us why science was the most''',adj1,'''class.
            First,he used a''',tool,'''and a''',veg,'''to make a''',vessel,'''of water turn''',colour2,'''.
            Then he made a''',noun1,'''of the solar system using''',fruit1,''',''',candy,''',''','''and''',noun2,'''.
            When the principal walked by and saw the substitute teacher using''',noun3,'''to''',verb2,'''the''',
            furniture,'''into''',colour3,pnoun,'''she asked him to show the class a movie about''',noun4,'''instead.
            The next day, we had a different substitute teacher.''')


def christmas_story1():
    print('\n')
    print('Enter a noun: ')
    noun1=input()
    print('Enter an adjective: ')
    adj1=input()
    print('Enter a noun: ')
    noun2=input()
    print('Enter an adjective: ')
    adj2=input()
    print('Enter a verb: ')
    verb1=input()
    print('Enter a verb: ')
    verb2=input()
    print('Enter a plural noun: ')
    pnoun1=input()
    print('Enter an item of food: ')
    food=input()
    print('Enter a plural noun: ')
    pnoun2=input()
    print('Enter an adjective: ')
    adj3=input()
    print('Enter a verb: ')
    verb3=input()
    print('Enter a verb: ')
    verb4=input()
    print('Enter a noun: ')
    noun3=input()
    print("Enter a person's name: ")
    name1=input()
    print('Enter a singular verb')
    sverb1=input()
    print('Enter an adjective: ')
    adj4=input()
    print('Enter a noun: ')
    noun4=input()
    print('Enter a verb ending with -ing: ')
    verb5=input()
    print('Enter an affectionate term: ')
    at=input()
    print('Enter a persons name: ')
    name2=input()
    print('Enter a singular verb: ')
    sverb2=input()
    print()
    for i in 'proccessing story.....':
        print(i,end='')
        time.sleep(0.15)
    print('\n')
    
    print('''Oh,the''',noun1,'''outside is''',adj1,''',
But the''',noun2,'''is so''',adj2,''',
And since we've no place''',verb1,''',
Let it snow,let it snow,let it snow.
It doesn't,''',verb2,pnoun1,'''of stopping,
And i brought some''',food,'''for popping 
The''',pnoun2,'''are turned way down''',adj3,''',
Let it snow,let it snow.
When we finally''',verb3,'''good night,
How I'll''',verb4,''' going out in the''',noun3,''';
But if''',name1,'''really''',sverb1,'''me tight,
All the way home I'll be''',adj4,'''.
The''',noun4,'''is slowly''',verb5,''',and,my''',at,
''', we are still good-bye-ing,
But as long as''',name2,sverb2,'''me so,
Let it snow,let it snow,let it snow.''')

def christmas_story2():
    print('\n')
    print('Enter an adjective: ')
    adj1=input()
    print("Enter a noun: ")
    noun=input()
    print('Enter a relative: ')
    adj2=input()
    print('Enter a noun: ')
    noun1=input()
    print('Enter an noun: ')
    noun2=input()
    print('Enter an adjective: ')
    adjective2=input()
    print('Enter an adjective: ')                                   
    adjective3=input()
    print('Enter a person: ')
    person=input()
    print("Enter an animal: ")
    animal=input()
    print('Enter a location: ')
    location=input()
    print('Enter a adjective: ')
    adjective4=input()
    print('Enter a holiday: ')
    holiday=input()
    print('Enter an adjective: ')
    adjective5=input()
    print('Enter a noun: ')
    noun3=input()
    print("Enter a noun: ")
    noun4=input()
    print("Enter an adjective : ")
    adjective6=input()
    print("Enter a noun : ")
    noun5=input()
    print("Enter an adjective : ")
    adjective7=input()
    print("Enter a holiday : ")
    holiday2=input
    print()
    for i in 'proccessing story.....':
        print(i,end='')
        time.sleep(0.15)
    print('\n')
    print('''             I have been a very,''',adj1,'''this year!,''',noun,
            '''I always help my''',adj2,'''with chores around the''',noun1,'''and take out the''',noun2,'''everyday.'''
            '''I really hope that I am on the''',adjective2,'''list this year! I have done a lot of''',adjective3,'''things,so I think I deserve it! I even
            helped''',person,'''feed their''',animal,'''while they were they on vacation in''',location,
            '''I have a few''',adjective4,holiday,'''wishes this year, and I would love to see a''',adjective5,
          '''new underneath the tree with my name on it! It would make me the happiest''',noun3,'''on the''',noun4,'''! Oh, and if you could put a''',
          adjective6,noun5,'''inside of my stocking, that would be''',adjective7,'''too! Merry''',holiday2)

def callback(fn):
    fn()

def line():
    print('-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------')


line()
print('                                                                                                     ',end='')
for i in 'M  A  D  L  I  B  S':
    print(i,end='')
    time.sleep(0.1) 
print()
line()


def game1():
    print()
    print('                                                                                                             1.Play')
    print('                                                                                                        2.How to play')
    print('                                                                                                             3.Exit')
    print()
    global option
    option=int(input('Enter the number with the option you want to choose : '))
    print()
    if option==1 or option==2:
        line()

def game2():
    print()
    print('                                                                                                             1.Play')
    print('                                                                                                             3.Exit')
    print()
    global option
    option=int(input('Enter the number with the option you want to choose : '))
    print()
    if option==1:
        line()

    
option=0
game1()

horror=[1,2]
christmas=[1,2]

if option==1:
    print('                                                                                         Which story would you like to pick?')
    line()
    print()
    print('                                                                                                       1.Horror story')
    print()
    print('                                                                                                    2.Christmas story')
    print()
    story_pick=int(input('Enter your option : '))
    line()
    if story_pick==1:
        f=random.choice(horror)
        if f==1:
            callback(haunted_story1)
        elif f==2:
            callback(haunted_story2)
        print()
        exits()
    elif story_pick==2:
        f=random.choice(christmas)
        if f==1:
            callback(christmas_story1)
        elif f==2:
            callback(christmas_story2)
        print()
        exits()

elif option==2:
    rules()
    game2()
    if option==1:
        print('                                                                                         Which story would you like to pick?')
        line()
        print()
        print('                                                                                                       1.Horror story')
        print()
        print('                                                                                                    2.Christmas story')
        print()
        story_pick=int(input('Enter your option : '))
        line()
        if story_pick==1:
            f=random.choice(horror)
            if f==1:
                callback(haunted_story1)
            elif f==2:
                callback(haunted_story2)
            print()
            exits()
        elif story_pick==2:
            f=random.choice(christmas)
            if f==1:
                callback(christmas_story1)
            elif f==2:
                callback(christmas_story2)
            print()
            exits()
    elif option==3:
        exits()
        
elif option==3:
    exits()

# Games

The solutions can be found in the relative files. But it's much more fun to solve them alone! You will learn more 😉

![Games](https://images.unsplash.com/photo-1545558014-8692077e9b5c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80)

### 🐄 Milka [If/Else]

Milka the cow needs 10 grass to do 1 chocolate
2 Grass grow from 1 rain.

1. Define a variable called "rain" and one called "grass"
2. With an "if" check if there is enough grass to make a chocolate
3. If enough, print how many chocolates we can have, otherwise be sad

Bonus Points: Give the cow a name and print it

### 🤺 Ninjas [If/Else]

We need to fight 50 dragons.
A ninja can defeat 3 dragons.
Do we win or loose?

1. Define a variable "ninjas" and one "dragons" and print if we win or loose based on the variables

Bonus Points: Say how many more ninjas do we need to win the fight!

### 👨‍👧‍👧 Pairs [If/Else]

All the students must get together in groups.
Are all students in a group or is there someone alone?

1. Define a variable "students" and one "group_size"
2. Check with the modulo operator "%" if there is someone left out in the gruop

Bonus Points: How many additional students do you need to fill the group?
Bonus Bonus Points: What group sizes are possible so that no one is left out?

### 🙎‍♀️ The new friend [Lists]

We have a list of friends
"Charlie" is a new friend, but in the beginning she is at the end.
We all like Charlie so we put her in the middle of our friends.

1. Create a list with 4 names (Alice, Bob, Diana, Elisa)
2. Put Charlie inside the friend list
3. Move Charlie to the middle

### 🍕 Pizza [Loops]

Mario eats a pizza.
The pizza is so tasty that everytime he eats a slice he wants to say "Mhhhhhh"
Everytime he eats a slice his hunger gets lowered by 1
If he is full, stop eating and say "I'm full 🤤"
When he is finished he says "Mamma mia! Buonissima! 😋"

1. Define a variable "slices" and "hunger"
2. For each slice say "mhhh"
3. Check if he has hunger left
4. When finished say "Mamma ..."

Bonus Points: say if he is still hungry after eating

### 🚂 Train Driver [Loops]

You are driving a train from Berlin to Paris.
On the way to Paris you will stop in Hamburg, Amsterdam and Brussels before arriving in Paris.
Every time you depart you will need to tell the passengers that you are departing and what the next stop will be.
In paris tell the passengers that is the last stop

Bonus Points: Do all the prints inside the loop.

### ⛽️ How far can we make it? [Functions]

Renee is driving when she realises that her tank is almost empty.
She knows her car burns a certain amount of liters of gas every 100km.
She also knows the distance to the next gas station.
Will she make it or will she be stranded?

Renee drives a Jaguar F-TYPE R that consumes 10,9 l/100km.
The next gas station is in 420km.
She has 40 Liters of gas left

Arnold drives a Fiat 500 that consumes 4,9 l/100km.
The next gas station is in 285km.
He has 15 Liters of gas left

Annabelle drives a Renault Espace that consumes 5,8 l/100km.
The next gas station is in 69km.
She has 4 Liters of gas left

Bonus Points: Will the drivers make it if they drive slowly (+10% efficiency)?


### 🙍🏼‍️🙍🏼‍️🙍🏼‍ The oldest [Dictionaries]

You have some students and know how old they are. Mike is 19, Peter is 20, Michelle is 22 and Nicole is 20.

1. Save the age of each student in a dictionary.
2. Add the student Max who is 18 years old.
3. Today is Michelle's birthday, so make Michelle her one year older.
4. Choose a name and check if there is a student with this name.
5. Find the oldest student and print his name and age.


### ⛰📃✂️ Rock-Paper-Scissors [Dictionaries]

You want to play rock-paper-scissors against the computer.

1. Define a dictionary for each player that stores its name and current score.
2. Ask the player about his or her name and ask how many round should be played.
3. Each round, ask the player for his or her choice. The computer should pick a random choice.
4. Evaluate each round and print who has won.

Bonus Points: Accept different spelling of each choice ('rock', 'Rock', 'rOcK') and maybe even abbreviations.


### 🙍🏼‍♂️ Human [Classes]

1) Implement a class Human class with just the attributes `name` and `age`. Do not forget the constructor.
2) Add a method for saying hi. It should print out the name and the age.
3) Add a method for having birthday that increases the age of the current human by one.
4) Add a list of hobbies to your Human class (remember the constructor) and include the hobbies in the say_hi method.
5) Add a method has_hobby to find out, if the given hobby is one of the humans hobbies. Return a True or False.
6) Add a method to add a humans hobby. If the human already has the hobby, print an appropriate message and do not add
   it. Otherwise, add it.

Bonus: Inheritance! If your are really fast and feel comfortable with object-oriented programming in Python, have a look
    at this [short introduction to inheritance](https://github.com/nick-lehmann/SnakeCharmerGuide/blob/master/docs/code/class_inheritance.py).
    Try to implement a subclass of Human that represents a Student. Add an attribute that represents his or her student
    id and change the method for saying hi to also print the student id at the end.
    

### 📌 Point

1) Create a Point class that has two attributes, x and y. Remember the constructor.
2) Implement an add method that takes another point, adds this one to itself and returns a new Point that is the result
   of the addition.
3) Implement a method, that calculates the distance from itself to another point using Pythagoras. The other point
   should be given as a parameter. Return the calculated distance as a number.
4) Implement a method, that calculates the distance from the point to the origin (0,0). No parameters are needed.
5) Given p1 = Point(1,2), p2 = Point(2,4) and p3 = Point(5,1). Add all points to p. Calculate the distance of p to
   p4 = Point(10,10) and (0,0). (Results should be `3.6` and `10.6` respectively)

INFO: Do not forget the self parameter for any method.
INFO: Everything should be implemented on the class. No standalone functions are needed (or allowed ;) ).
INFO: Raising a number to a power is done using the `**` operator, e.g. 2 ** 3 == 8. If you want to calculate the square
      root, raise the number to 1/2 for now.

BONUS: Together with the tutors. Overload appropriate operators to make your life easier.

# Backend-1-Ruby
Ruby exercises for Backend 1

These exercises cover weeks 3 and 4 of the Backend 1 class.  When you have completed the exercises for a given week, push the result to github.

Week 3:

(1) Write a program which asks the user for a number of years, and then prints out how many hours are in that many years.  Then it asks for a number of decades, and prints out the number of minutes are in that many decades.  Then it asks for the user's age, and prints out the number of seconds old the user is. Call this program years_to_hours.rb.  

Here is the first part of the program:

puts "Enter a number of years"
years = gets.chomp # this returns a string
years = years.to_i # this converts a string to an integer
hours = years * 365 * 24
puts "That's #{hours} hours."
# Write your code here for the other parts.

(2) Write a program which asks for a person's first name, then middle, then last.  It should store each of these parts in an array. Finally, it should greet the person using their full name.  Call the program full_name.rb.

(3) Write a program called sorted_words.rb.  It should prompt the user for words and add each to an array.  The user should be able to add as many words as they like, until they just hit enter to return a blank word. Then sort the array using the sort method and print it out. 

(4) Write a program with a function add_up(i) .  It is to be passed a positive integer, and it will add all the numbers from 1 to that integer and return the sum.  Call the function three times within the program, and each time print out the return value.  Call the program add_up.rb.
 
Week 4:

(5) Write a method that returns in an array all the numbers between 1 and 100 that are divisible by 2 or 3 or 5. Then call the method in your program and print out what it returns.  Call the program divisible.rb.

(6) Write a program hangman.rb that contains a function called hangman.  The function's parameters are a word and an array of letters.  It returns a string showing the letters that have been guessed.  Call the function from within your program so that you know that it works.

Example: hangman("bob",["b"]) should evaluate to "b_b"
Example: hangman("alphabet",["a","h"]) should return "a__ha___"

(7) Write a program that collects 5 keys and 5 values from the user, and stores them in a hash.  Write a function that accepts the hash as optional parameters and prints out an array of keys and an array of values.  Call the function within your program so you know it works. (Question: Can you find online information on Ruby hash methods that will help with this function?)  Call this program hash_to_array.rb.

(8) Create a program sums.rb with two classes.

(a) a class called Sum1 with an initialize method that takes two parameters and sets the instance variable total to the sum of the two.  Include a line at the top of the class: 

attr_accessor :total

(b) a class called Sum2 with an initialize method that takes two parameters a and b and sets the instance variable a to the parameter a and the instance variable b to the parameter b. Create a method new_total inside Sum2 that returns the sum of the instance variables a and b.

(c) In the mainline program, create instances of Sum1 and Sum2, passing 5 and 6 as parameters on the new statement.  Print out the total for Sum1.  Print out the new_total for Sum2.

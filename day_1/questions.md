## Day 1 Questions

1. How would you print the string `"Hello World!"` to the terminal?

puts "Hello World!"

1. What character is used to indicate comments in a ruby file?

#

1. Explain the difference between an integer and a float?

A float has a decimal point in it and provides more accuracy. An integer will truncate the decimal point (important note, it won't round, just truncate)

1. In the space below, create a variable `animal` that holds the string `"zebra"`

` animal = "zebra" `

1. How would you print the string `"zebra"` using the variable that you created above?

`puts animal`

1. What is interpolation? Use interpolation to print a sentence using the variable `animal`.

Interpolation allows us to evaluate code within a string.
`"There are #{animal}s in the zoo"`

1. What method is used to get input from a user?

gets and we typically do a .chomp to get rid of the newline character on the user input. So gets.chomp will take user input

1. Name and describe two common string methods:
.capitalize
.split 

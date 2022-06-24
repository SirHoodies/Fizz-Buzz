This will print every number from 1-100 but for every number that is divisible by 3, it replaces that number with "Fizz" and if the number is divisible by 5, it replaces it with "Fuzz".
________________________________________________
    for (let number = 0; number < 100; number++){       // first we make the variable "number" which = 0. then we check to see if number(0) is less than 100. If is is (true) then it will add 1 to the number (making number = 1)                                              
        let output = ""                                 // then we set the make and set the variable "output" to "" (which is like a blank slate or 0)
        if (number % 3 ==0) output +="Fizz "            // they we check if the variable "number", when divided by 3 or 5, = 0. and if it does, it sets the output (blank slate) to either "Fizz" or "Buzz" respectivley
        if (number %5 ==0) output +="Buzz "
        console.log(output||number)                     // then the console takes the "output" and prints either "fizz" or "buzz". and if "output" is still blank, it will just print the "number"
    }                                                                  
  ________________________________________________  
  //if number isnt divisible by 3 or 5:
                                                
 console.log(output||number)  = number (true on the right)
              false  true                                                                          
                        
  //if number is divisible by 3 or 5

 console.log(output||number) = output(true but on the left)
              true    true                                                                              

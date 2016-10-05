#>> METHODS
We've seen methods before. We've used them on strings, on arrays, on hashes. Ruby gives us a lot to work with when it comes to the methods they've created for us.		
But wouldn't it be cool if we could create our own methods? It totally would -- and even better, it's totally possible.		

Methods are created like this:
	
	def method(input)
		#some logic goes here
	end

Above, we are defining a method named `method`, which takes an input. Then we present the code that we want that method to run, and close the method with `end`. Every method needs to be sandwiched between `def` and `end`. 

Let's say we want to make a method that will take in a number and then double it. 

	def double(num)
		return num*2
	end

We've called our method `double` and we have it taking in an input `num`. Then our method will return our input times 2, and finish running.		
Now, if we want to use our method, all we have to do is call it.

	double(2)
		>> 4
	
	double(5)
		>>10

We call a method using the name of the method, and we add the input in parentheses next to it.		
A few more examples of possible methods:

	def greet(name)
		"Hello #{name}, how are you?"
	end
	
	greet("robotron")
		>> "Hello robotron, how are you?"
	
-------
	def cats(num)
		"CATS! " * num
	end

	cats(3)
		>> "CATS! CATS! CATS! "

-------

Check out this method, and explain to a partner what you think is happening:

	def weather(temp, city)
		"It is #{temp} degrees outside in #{city}!"
	end
	
	weather(79, Brooklyn)
		>> "It is 79 degrees outside in Brooklyn!"


Discuss this one as well:

	def hello
		return "hello!"
	end
	
	hello
		>> "hello!"


		

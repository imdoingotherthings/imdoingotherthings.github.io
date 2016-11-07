---

layout: post
title: For loop

---


Before I signed up for Bloc's Software Developer Track, I've had trouble wrapping my head around loops. 
Loops are perhaps the toughest concept in code to grasp. While going through the curriculum, I've had multiple opportunities to work with loops. The most common loop that I work with is a FOR loop. 
I use the FOR loop to iterate through data.

For Loop: 
{% highlight javascript %}
	for (var count = 0; count < foo; count++) {
		// code to be executed after it loops through foo
	}
{% endhighlight %}

Walkthrough: 

Foo is being used as a placeholder which stores data. 
var is short for variable, following the variable is the name of the variable which we named count.
After count, is an assignment operation which stores 0. So now the variable that we named count, stores 0.
We use the number 0 to define where we're starting our iteration. So say foo contains 15 elements, if we assigned count to be 1, it would skip the very first element (which is 0) and jump to the second element (which is 1).

Note: in programming, the data starts with 0 instead of 1. 
Example: var num = [14, 34, 91, 0].
If we wanted to grab the very first element which is 14, we would grab it like so, num[0]. 

Following the variable that we initialized in the loop, we have count that is being checked. 
So here it is checking to see if the variable count (which is 0) is less than foo, then we incerement count by 1.
The semi-colons indicate that its finished with that piece of code. In grammar the period means its finished with its sentence. The semi-colon is doing the exact same thing here in our code. 

So, if count continues to be less than foo (foo has 15 elements), then count will continue to iterate until it has touched the very last element in our data. 
After it has checked that code, inside the curly brackets {}, we write code that we want to be executed.
If we write console.log(foo[count]); inside our curly brackets, we would see all of the elements inside of foo.

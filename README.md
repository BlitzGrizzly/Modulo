# Modulo
My implementation of the modulo operator. Does not use a loop.
I was asked to implement a function that performed a modulo calculation, without using the modulo operator. 
This is what I came up with before I realized that there is a common, clever loop solution.
Still, I'm proud I was able to come up with this solution on my own.

While writing this, I quickly noticed that when dividing, the decimal of the quotient multiplied by the denominator equals the remainder. I felt pretty darn clever for spotting this. A few tweaks to make sure the correct sign was returned and figuring out how to deal with rounding errors and I was all set.

Run the program in a browser.
When the program is opened, enter a number into the input field and press the submit button to view the prime table.

When the program has loaded the tests run automatically and the results can be seen in the console.

I am pleased with how I implemented the prime number algorithm.
Originally the algorithm had a time complexity of O(n) as it would calculate the remainder of a number n divided by every number 
less than n. I improved this when I realised that n divided by any number greater than n/2 would produce a reminder between 1 and 2 
and therefore did not need to be checked. The time complexity of the algorithm then became O(n/2), twice as fast as it was originally.

I am also pleased with the method I used to create the prime table. Rather than iterate over a whole 2D-array and calculate each value
I wrote a function that mirrors one side of the array across the diagonal that goes from [0,0] to [n+1, n+1].

After completing the prime number algorithm I looked up a more efficient way to do it, and I believe if I had more
time I was on the right path and could have come close to the algorithm I found. The algorithm I found had a time complexity of
O(√n) as it only check if every number less than the √n was a factor of n.

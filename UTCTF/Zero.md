## Zero
For the Zero challenge we were given a text file called **zero.txt**
![zero_chal](https://github.com/AnthemC/writeups/blob/master/img/zero_chal.png)

Once you download the file you will notice that it all just appears as lorem ipsum filler text. 
![lorem ipsum](https://github.com/AnthemC/writeups/blob/master/img/zero_file.png)

But you might notice, just as the challenge description says the file size is bigger than it should be.
![file size](https://github.com/AnthemC/writeups/blob/master/img/zero_prop.png)

The title of the file is a hint towards the solution. Zero alludes to **zero width characters**.

Now that we have a lead you can use an online steganography tool such as [this](https://330k.github.io/misc_tools/unicode_steganography.html) one on github. We copy and paste the whole file into the right box and hit decode and get the flag.
![solution](https://github.com/AnthemC/writeups/blob/master/img/zero_decode.png)

Flag: **utflag{whyNOT@sc11_4927aajbqk14}**

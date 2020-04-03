## This challenge gives you a wav file and tells you that it is a **SSTV** transmission.

![challenge prompt](https://github.com/AnthemC/writeups/blob/master/img/1frame_chal.png)

Once downloading the file I did a little research and looked around to figure out what SSTV means and found out that its a method of transmitting images over HAM radio.

I found and downloaded a tool called RX-SSTV after searching for SSTV decoders. With this tool you choose the RX option which we know is Martin 1 from the challenge description. Then you play the audio while the program is open and the image will appear in the box on the left once the audio is over.

![Image of RX-SSTV with flag](https://github.com/AnthemC/writeups/blob/master/img/1frame.png)

The flag is:
utctf{6bdfeac1e2baa12d6ac5384cdfd166b0}

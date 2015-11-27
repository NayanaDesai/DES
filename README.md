# DES
Implementation of Data Encryption Standard in Python

How to use it ?

1.Install the BitVector library: https://pypi.python.org/pypi/BitVector (Use it's readme for installation instructions)

2.Go to the destination of .py files in the command line.

3.To encrypt type : python des.py and to decrypt type : python invdes.py

What is the difference between des.py and invdes.py?
->Only one line that reverses the array of keys ! 

    def encrypt(messages):
      k.reverse()#reverse order of keys for each round

References:

[1] https://en.wikipedia.org/wiki/DES_supplementary_material

[2] https://en.wikipedia.org/wiki/Data_Encryption_Standard

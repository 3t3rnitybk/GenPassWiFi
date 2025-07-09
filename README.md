Modified script for continuous generation until manually stopped
If you want to generate as many passwords as possible, you can use 
a script that continuously writes to the file until you manually stop it (Ctrl+C):
How it works:
1-You run the script.
2-It will generate and write passwords to a file continuously.
3-You stop with Ctrl+C when you think you've had enough.
Generating a very large number of passwords (in the order of tens or hundreds of millions, or even billions) is limited in practice by:

Disk storage space (the file will be very large)
Time required for generation and writing
Processing capacity of your computer
Disk space estimate
A 10-character password + a newline character takes up approximately 11 bytes.

For:

10 million passwords → ~110 MB
100 million passwords → ~1.1 GB
1 billion passwords → ~11 GB

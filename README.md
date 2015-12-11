### Making Secure Easy-to-Remember Passwords
##### Philip Braunstein (pbraunstein12@gmail.com)
##### Advised by Ming Chow
##### Fall 2015

#### Overview
This repository contains the scripts and wordlists described in the report
Better\_Passwords.pdf. This README gives a brief description of each of the
scripts.

#### Scripts
`charFracSim.py`: This script deterimines the fraction of the characters common
between two passwords provided on the command line.

`determineOrder.py`: This script randomizes the order in which the password
types should be tested.

`humanPass.py`: This script uses the noun, verb, and adjective word lists to
generate 10 of the MX passwords.

`makeHashes.py`: This script takes a file name as input and writes out a new
file with each of the lines of the file hashed using MD5 without salt.

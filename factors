#!/usr/bin/python3
import sys

file = open(sys.argv[1], "r")
nums = file.readlines()

for i in nums:
    f1 = 2
    while int(i) % f1:
        f1 += 1
    f2 = int(i) // f1
    print("{:d}={:d}*{:d}".format(int(i), f2, f1))

file.close()

#!/usr/bin/python3

import os


commands = [ 'nproc' , 'free -m' , 'lsblk' ]

for cmd in commands:
    os.system(cmd)

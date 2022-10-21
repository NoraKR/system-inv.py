#!/usr/bin/python3

# written by YoGalNora

import os


commands = [ 'nproc' , 'free -m' , 'lsblk' ]

for cmd in commands:
    os.system(cmd)


#!/usr/bin/python
# -*- coding: UTF-8 -*-

from os import system, name
import itertools
import threading
import time
import sys
import datetime
from base64 import b64decode,b64encode
from datetime import date

#expirydate = datetime.date(2021, 10, 1)
expirydate = datetime.date(2021, 8, 30)
today=date.today()
def hero():

    def chalo():
        done = True
        #here is the animation
        def animate():
            for c in itertools.cycle(['|', '/', '-', '\\']) :
                if Good:
                    break
                sys.stdout.write('\rhacking in the parity server for next colour--------- ' + c)
                sys.stdout.flush()
                time.sleep(0.1)
            sys.stdout.write('\rDone!     ')

        t = threading.Thread(target=animate)
        t.start()

        #long process here
        time.sleep(20)
        done = True

    def chalo1():
        done = True
        #here is the animation
        def animate():
            for c in itertools.cycle(['|', '/', '-', '\\']):
                if Good:
                    break
                sys.stdout.write('\rgetting the colour wait --------- ' + c)
                sys.stdout.flush()
                time.sleep(0.1)
            sys.stdout.write('\rDone!     ')

        t = threading.Thread(target=animate)
        t.start()

        #long process here
        time.sleep(20)
        done = True

    def clear():
        # for windows
        if name == 'nt':
            _ = system('cls')
        # for mac and linux(here, os.name is 'posix')
        else:
            _ = system('clear')

    clear()
    y=1
    newperiod=period
    banner='figlet RXCE'
  



if(expirydate>today):
    now = datetime.datetime.now(2021, 1, 9)
    First = now.replace(hour=13, minute=55, second=0, microsecond=0)
    Firstend = now.replace(hour=14, minute=35, second=0, microsecond=0)
    Second = now.replace(hour=15, minute=55, second=0, microsecond=0)
    Secondend = now.replace(hour=16, minute=35, second=0, microsecond=0)
    Third = now.replace(hour=16, minute=55, second=0, microsecond=0)
    Thirdend = now.replace(hour=17, minute=35, second=0, microsecond=0)
    Final = now.replace(hour=17, minute=55, second=0, microsecond=0)
    Finalend = now.replace(hour=18, minute=35, second=0, microsecond=0)

    if (True):
            period=220
            hero()
    elif(now>First and now<Firstend):
            period=280
            hero()
    elif(now>Third and now<Thirdend):
            period=340
            hero()
    elif(now>Final and now<Finalend):
            period=360
            hero()
    else:
        banner='figlet RXCE'
        print("Hi!! Thanks for buying the hack")
        print("----------Your play time-----------")
        print("1st Sept 2021, 11:00 AM- 11:30 AM")
        print("1st Sept 2021, 02:00 PM- 02:30 PM")
        print("1st Sept 2021, 05:00 PM- 05:30 PM")
        print("1st Sept 2021, 08:00 PM- 08:30 PM")
        print("Please play on the given time, and ")
        print("If you think it is an error contact")
        print(" admin on telegram @smsn_knt ")



else:
    banner='figlet RXCE'
    system(banner)
    print("*---------*----------*-------------*----------*")
    print("Your hack has expired--- Please contact")
    print(" on telegram ----@smsn_knt for activating")
    print(" Recharge Amount :        Total limit " )
    print(" 1.     1000 INR -------  1 Day (40 Games")
    print(" 2.     5000 INR -------  7 Days(280 Games")
    print("*---------*----------*-------------*----------*")
    print("Your custom hack can be made request from us.")

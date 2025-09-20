from machine import Pin
from time import sleep
irs=Pin(1,Pin.IN)
led1=Pin(2,Pin.OUT)
led2=Pin(3,Pin.OUT)
while True:
    a=irs.value()
    print(a)
    if a==0:
        led1.value(1)
        led2.value(0)
    else:
        led1.value(0)
        led2.value(1)
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        

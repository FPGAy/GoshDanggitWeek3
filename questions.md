1. What are the hardware registers that cause the LED to turn on and off? (From the processor manual, don’t worry about initialization.)
  -> copy paste the hell out of it
     • User LD3:
       The orange LED is a user LED connected to the I/O PD13 of the STM32F411VET6.
     * so its GPIO port output data register (GPIOD_ODR) 
  -> question to self !!!
    wtf is 8.4.7 GPIO port bit set/reset register (GPIOx_BSRR) (x = A..E and H)

3. What are the registers that you read in order to find out the state of the button?
  -> coppy pasteee
     * B1 USER:
         User and Wake-Up button connected to the I/O PA0 of the STM32F411VE
     * GPIOA_IDR ?

3.Can you read the register directly and see the button change in a debugger or by printing out thes value of the memory at the register’s address?
    * yes i check through the register watch part

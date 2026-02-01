# Design and Verification of Asynchronous FIFO

## Aim
- Verilog Based Verification of Each IP Block

 a single “2 FF synchronizer” can resolve metastability for only one bit. Hence, depending on write and read pointers multiple 2FF synchronizers are required. 
gray code is assured to have only a single bit change from its previous value. Hence, both write and read pointers need to convert first to their equivalent gray code in their corresponding domain and then pass them to an opposite domain. 

data = 8 bits
address = 4 bits 



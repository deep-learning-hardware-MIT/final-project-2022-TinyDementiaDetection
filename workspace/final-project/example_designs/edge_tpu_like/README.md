Edge TPU Architecture
----------------------------
This folder contains an Edge TPU-like architecture. Reference: https://arxiv.org/pdf/2102.10423.pdf

Q&As:
----------------------------
1. How long do the Timeloop simulations take?
  
   Depending on your workload, the simulation takes various amount of time to finish. Generally, they should 
   converge within 30 mins. You can manually stop the exploration when you see things are converging by 
   pressing `ctrl + C`. They sometimes will take much longer to 
   automaticaly stop as we set the converging cretiria to be pretty high to avoid early-stop with subooptimal mappings. Use you own
   judgement.

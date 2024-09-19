# IPCameraFinder
My first cyber project, goal to test a given IPv4 range for IP Camera streams.
# Abstract
The general idea for this project is to take a given range as input, and test each address using the port:path combinations found in port_stream_pairs.txt 
Phase 1 is to just make the basic functions work
Phase 2 add 404/403 log and use those logs to avoid revisiting those non-existent or inaccessible sites
Phase 3 add simple GUI 

# Manifest
Functions needed (as of 9/18/2024)
1. take range input and generate ip list
2. generate url - concatenate pairs with input (use math so)
3. test url - use fetch api to test accessibility and if it exists
4. log successful connections 

   
   

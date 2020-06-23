# Kalman Filter in C

A simple and accurate Kalman filter implementation.  


1. It works stably even for float16 matrices.  
 Because this implementation uses sqrt decomposition.  
  
2. It does NOT depend on the other external library,  
 only using orignal matrix operation library.  

Therefore,  
it is possible to deal with operations even on a weak CPU like embedded system environment.  

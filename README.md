# WARPlab_IF

Matlab code that uses the WARPlab framework to build a 2x2 MIMO wireless network.
The purpose of this project is to build a framework that enables the use of interger-forcing linear receivers in an experimental practical setup using WARP boards. 

The shared code implements the following receivers: 
- integer-forcing (IF) linear receiver, see the file: 
- exact-integer-forcing (eIF) linear receiver, see the file: 
- maximum-likelihood(ML) receiver, see the file: 
- zero-forcing(ZF) linear receiver, see the file: 
- minimum-mean square error(MMSE) linear receivers. 

Each file for each type of receiver contains both the coded version and the uncoded version of the specific linear receiver. As long as they receive the appropriate input variables they (the .m functions) can be run independently. By that I mean you can run just one of the receivers AND/OR you can run the files offline, that is you can run the .m files after the experiment has been done and you saved the workspace. For each file, the coded part is done first and the uncoded part is done last. Please note that the two types of receivers: uncoded and coded, are written independly of eachother. Therefore, one can comment or delete the code corresponding to either of them. 

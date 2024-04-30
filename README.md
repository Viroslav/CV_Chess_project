# Chess Detector and Adviser (CDA)
# 
## The main idea is to help chess players who like to play on a real board, keep track of their moves, help with decisions, and if you are alone, simulate the game with a real person using a computer)


We used classical CV algorithms (like blur+binarization) to detect the board, also ProjectiveTransform and Approximation to get it to the right position. Then we cut it to the squares and train classificator (Neural Network with 5 Convolution layers). After we get the array of prediction and use it with python-chess library to detect the board statement, possible top move, position estimation etc.



## Example of detection and best move-adviser:

![IMG_3071](https://user-images.githubusercontent.com/98733029/209229571-2d5c6d03-f179-4083-bc91-8597f580ab11.JPG)
![OUHRpZsGWoo-PhotoRoom (1)](https://user-images.githubusercontent.com/98733029/209228559-c5c069e0-3677-4662-93a6-d309f3b1bc30.png)

PS. All main code can be found in CV_project.jpynb

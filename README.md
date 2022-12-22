# Chess Detector and advicer.
# 
## The main idea is to help chess players who like to play on a real board, keep track of their moves, help with decisions, and if you are alone, simulate the game with a real person using a computer)


We used classical CV algorithms (like blur+binarization) to detect the board, also ProjectiveTransform and Approximation to get it to the right position. Then we cut it to the squares and train classificator (Neural Network with 5 Convolution layers). After we get the array of prediction and use it with python-chess library to detect the board statement, possible top move, position estimation etc.

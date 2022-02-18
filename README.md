# Oanda-Bot-with-Support-Vector-Machine
OANDA-SVM with Low Open feature 

This is a bot that predicts the Moving Average of a choosen instrument with the help of the Money Flow Index and Low-Open and High-Close as a feature. Also the MFI Indicator is built from values made with the rolling.mean() function. 
Right now the backtest has a serious flaw. It should calculate the return whenever the signal changes from one direction to another, and not at every single step.  

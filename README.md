# ml-assignment-4
# ON REMOVING DROPOUT
# the testing accuracy decreased from 98.07% to 97.86%, this happpened because we add dropout as a way to prevent overfitting. Here we randomly keep some network weights fixed when we would normally update them so that the network doesn't rely too much on very few nodes.
# ON CHANGING HIDDEN LAYERS FROM 1 to 2 
# the testing accuracy decreased from 98.07% to 97.84%. Increasing hidden layers causes your network to overfit to the training set, that is, it will learn the training data, but it won't be able to generalize to new unseen data.
# ON CHANGING EPOCH FROM 5 TO 7
# the testing accuracy increased from 98.07% to 98.24%. Generally on increasing the number of epochs, testing accuracy must increase but if it decreases then it might be due to the fact that there might be overfitting of data.

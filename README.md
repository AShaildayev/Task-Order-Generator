%Task Order Generator

#Order Generator
#Aydar Shaildayev 2013
#Shuffles lists to create task order 
import random #import "random" module

list = [1, 2, 3, 4]; #create a list with 4 elements, 1 through 4

random.shuffle(list)  #shuffle list using "random" module 'shuffle' submodule
print('Shuffled list : ',  list)  #print the shuffled list

random.shuffle(list)  #shuffle list again
print('Shuffled list : ', list)  #print second shuffled list


list_learningG1 = ['1SO1', '2SO1', '3SO1', '4SO1', '5SO1', '6SO1', '7SO1', '8SO1', '9SO1', '10SO1', '1R2R', '2R2R', '3R2R', '4R2R', '5R2R', '6R2R', '7R2R', '8R2R', '9R2R', '10R2R']
#create list for first learning group

random.shuffle(list_learningG1) #shuffle learning group 1 list
print('Reshuffled learning task order Group 1 : ', list_learningG1) # print out shuffled list for first learning group

list_learningG2 = ['1SO2', '2SO2', '3SO2', '4SO2', '5SO2', '6SO2', '7SO2', '8SO2', '9SO2', '10SO2', '1R2R', '2R2R', '3R2R', '4R2R', '5R2R', '6R2R', '7R2R', '8R2R', '9R2R', '10R2R']

random.shuffle(list_learningG2)
print('Reshuffled learning task order Group 1 : ', list_learningG2)

list_learningG3 = ['1SO3', '2SO3', '3SO3', '4SO3', '5SO3', '6SO3', '7SO3', '8SO3', '9SO3', '10SO3', '1R2R', '2R2R', '3R2R', '4R2R', '5R2R', '6R2R', '7R2R', '8R2R', '9R2R', '10R2R']

random.shuffle(list_learningG3)
print('Reshuffled learning task order Group 1 : ', list_learningG3)

list_learningG4 = ['1SO4', '2SO4', '3SO4', '4SO4', '5SO4', '6SO4', '7SO4', '8SO4', '9SO4', '10SO4', '1R2R', '2R2R', '3R2R', '4R2R', '5R2R', '6R2R', '7R2R', '8R2R', '9R2R', '10R2R']

random.shuffle(list_learningG4)
print('Reshuffled learning task order Group 1 : ', list_learningG4)

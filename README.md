# Probability-Simulations-with-Excel
Efficient way to demonstrate and simulate different phenomena of probability theory in Microsoft Excel.
This project consists of works that deal with visualizing the common facts about probability theory with the help of simulation. The simulation is done by using different Excel functionalities. I tried to keep it simple, it might take a little time to look at one file and understand what is going on here, but once anyone understands they will realize how easy and simple it is. It should give someone a new approach to understanding probability theory just like it was in my case.

Here are the statements of the problems that have been simulated in the files of this project:

File_1: Peter tosses a coin four times. If a toss gives the same result as the previous one, Peter shouts aloud. For example, if the four tosses were
HEAD     HEAD     TAIL    TAIL
then he would shout after the second toss (because HEAD follows HEAD) and after the fourth toss (because TAIL follows TAIL D).
Let us introduce the random variables:
X = the number of heads in the sequence of the four tosses,
Y = the number of times Peter shouts during the four tosses.
PROBLEMS TO SOLVE:
1.	Make a list of all possible outcomes of the sequence of the four tosses. Then using this list, solve the following problems:
2.	Determine the distribution of X.
3.	Determine the distribution of Y.
4.	Determine the distribution of (X,Y). Using the table of the distribution of (X,Y), solve the following problems:
5.	Calculate the probability that X = Y.
6.	Calculate the probability that X + Y = 3.
7.	Calculate the probability that X + Y <= 3.
8.	Determine the conditional distributions of Y on the condition that X is given.
9.	Determine the conditional distributions of X on the condition that Y is given.

File_2_part_i: According to an uniform distribution, five people, independently of each other, arrive at a restaurant between noon and 1 pm. 
1. Let X be the time instant when the first arrives. (X is measured in hours. For example, when the first arrives at half past noon, then X=0.5.) Let Y be the time instant when the last arrives. 
2. Let X be the time instant when the second arrives. Let Y be the time instant when the third arrives. 
3. Let X be the time instant when the second arrives. Let Y be the time instant when the last arrives. 
More similar tasks like these

In each case: Put together X and Y to make the point (X,Y) on the plane. Make a simulation of 1000 experiments with Excel and visualize the point cloud. Observe and compare the point clouds.

File_2_part_ii: The following task helps one to make friends with the two-dimensional continuous random variables/distributions:
According to a (continuous) uniform distribution, a point is chosen between 0 and 1. This point is denoted by Y (not X
now). Then, according to a (continuous) uniform distribution, a point is chosen between 0 and Y. This point is denoted by
X. Put together X and Y to make a point (X,Y) on the plane. Make a simulation of 1000 experiments with Excel and
visualize the point cloud.

File_3: 
1.	Assume that the midnight temperature in Budapest in the middle of May follows a normal distribution with an expected value μ = 6 Celsius degrees, and standard deviation σ = 3 Celsius degrees. How much is the probability that the temperature is below 0 Celsius degrees? Then simulate 1000 experiments and calculate the experimental average and standard deviation. Check that the theoretical characteristics are close to the experimental ones. Check also that the relative frequency of a negative temperature is close to the probability.

2.	Let X mean the height; Y mean the weight of a randomly chosen man in a country. Assume that the random variable (X,Y) follows the normal distribution with parameters μ1=180, μ2=80, σ1=15, σ2=10 and r=0.6. With the help of a calculator and the table given here
					
x	   φ(x)		  x	   φ(x)	
0	0,5000		2	0,9772	
0,1	0,5398		2,1	0,9821	
0,2	0,5793		2,2	0,9861	
0,3	0,6179		2,3	0,9893	
0,4	0,6554		2,4	0,9918	
0,5	0,6915		2,5	0,9938	
0,6	0,7257		2,6	0,9953	
0,7	0,7580		2,7	0,9965	
0,8	0,7881		2,8	0,9974	
0,9	0,8159		2,9	0,9981	
1	0,8413		3	0,9987	
1,1	0,8643		3,1	0,9990	
1,2	0,8849		3,2	0,9993	
1,3	0,9032		3,3	0,9995	
1,4	0,9192		3,4	0,9997	
1,5	0,9332		3,5	0,9998	
1,6	0,9452		3,6	0,9998	
1,7	0,9554		3,7	0,9999	
1,8	0,9641		3,8	0,9999	
1,9	0,9713		3,9	1,0000	
2	0,9772	        4	1,0000	

Calculate the probabilities:

P(175 < X < 185 )
P(175 < X < 185 | Y = 75 )
P(175 < X < 185 | Y = 80 )
P(175 < X < 185 | Y = 90 )

Then calculate these probabilities also with the help of Excel. (You will be convinced that Excel is much more convenient.)

3.	(Continuation of the previous problem) 
The conditional probability P(80 < Y < 90 | X = x ) is a function of x. Using Excel, construct a table of the value of this conditional probability for x=160, 161, 162, … , 200, and then make a graph of this function.

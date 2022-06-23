# Tandem-Queue-Simulation
***
***
A service facility consists of two servers in series (tandem), each with its own FIFO queue (see Fig. 1.50). A customer completing service at server 1 proceeds to server 2, while a customer completing service at server 2 leaves the facility. Assume that the interarrival times of customers to server 1 are IID exponential random variables with mean 1 minute. Service times of customers at server 1 are IID exponential random variables with mean 0.7 minute, and at server 2 are IID exponential random variables with mean 0.9 minute. Run the simulation for exactly 1000 minutes and estimate for each server the expected average delay in queue of a customer, the expected timeaverage number of customers in queue, and the expected utilization.
***
![Screenshot 2022-06-23 222552](https://user-images.githubusercontent.com/60145603/175348778-ad9cb03f-58a3-4df3-84c6-82e41392edf5.png)
***
suppose that with probability 0.2, a customer completing service at server 2 is dissatisfi ed with her overall service and must be completely served over again (at least once) by both servers. Defi ne the delay in queue of a customer (in a particular queue) to be the total delay in that queue for all of that customer’s passes through the facility. Simulate the facility for each of the following
cases (estimate the same measures as before):
***
  a) Dissatisfied customers join the tail of queue 1.
***
  b) Dissatisfied customers join the head of queue 1.

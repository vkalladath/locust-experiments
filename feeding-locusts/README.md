# Feeding the locusts
There are times when you want your Locust scripts to use some input data in order to perform the tests.
For example:
* you want to use a list of users and their credentials in order to log in to some service,
* you have a set of form values that need to be submitted,
* you need to upload specific files as a part of requests to your service. 

In this "episode", I'll show how such a problems can be addressed.


# Development environment setup
In order to be able to develop code for this experiment, I need an environment with a working Locust cluster.

I'll be using kubernetes to run the tests (see https://medium.com/locust-io-experiments/locust-io-experiments-running-in-kubernetes-95447571a550 for my setup).
It's equally easy to run the cluster using Docker containers, or even "bare metal" locusts -- if you wish. 


# The code
TBD
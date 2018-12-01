# Simulator for Decentralized Feedforward Massive MU-MIMO Precoding
(c) 2018 Christoph Studer
e-mail: studer@cornell.edu

More information about our research can be found at [http://vip.ece.cornell.edu].

### Important information

If you are using the simulator (or parts of it) for a publication, then you *must* cite our paper:

K. Li, C. Jeon, J. R. Cavallaro, and C. Studer, "Feedforward Architectures for Decentralized Precoding in Massive MU-MIMO Systems", 52nd Annual Asilomar Conference on Signals, Systems, and Computers, Oct. 2018

and clearly mention this in your paper.  

### How to start a simulation:

Simply run

```sh
dprecoder_sim.m
```

which starts a simulation in a massive MU-MIMO system with 16 users, 256 base station antennas, and 16 antenna clusters with  64-QAM. The simulator runs with predefined parameters. You can specify your own system, algorithm, and simulation parameters by passing your own "par" structure (see the simulator for an example). Note that we use default parameters for the considered system configuration; if you want to run the simulation with different parameters, then please refer to the MATLAB code for other parameter settings.

As always, we highly recommend you to execute the code step-by-step (using MATLAB's debug mode) in order to get a detailed understanding of the simulator.

### Version history
* Version 0.1 (Nov. 30, 2018) - studer@cornell.edu  - initial release of the code

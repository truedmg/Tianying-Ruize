## SCDAA Coursework 2022-23
#### Tianying Zhu s1811907,  Ruize Wang s2436072
## Instruction of how to running the code
### 1. Linear quadratic regulator
To plot the Monte Carol simulation graph, first to run the class `class LQR_Riccati_ODE`.

Then, run the function 'dx_(N,T,k,x)', whcih gives the values of x at each time step, the function 'perform(N,T,k,x,r)', which provides the predicted result of the value function, the function 'sim(N,T,k,x,r)', which gives the error between the value function defined in Ex 1.1 and the predicted result of value function.

After these, run the cells below title 'simulation'. The first cell displays the Monte Carol simulation with fixed sample size. The second cell shows the Monte Carol simulation with fixed time steps.

### 2. Supervised learning, checking the NNs are good enough
To plot the training loss of value function and markov control function, the class in Ex1 `class LQR_Riccati_ODE` should be ran firsly.

To plot the training loss of the value function, also need to run the class `Net_DGM` before applying torch Adam optimizer. Then run the cell below class `Net_DGM` to plot.

To plot the training loss of the value function, also need to run the class `FFN` before applying torch Adam optimizer. Then run the cell below class `FNN` to plot.

### 3. Deep Galerkin approximation for a linear PDE
Firstly run the class in Ex1 `class LQR_Riccati_ODE` as the parameters are needed. Then run the class `class Net`, `class Heat` and `class Train`.

To plot the training loss, run the first cell below `class Train`.

### 4. Policy iteration with DGM
Firstly run the class in Ex1 `class LQR_Riccati_ODE` as the parameters are needed. Then run the class `class Net_1`, `class Heat_1` and `class Train_1`.

To plot the comparison with the optimal control form Ex1, run the first cell below `class Train_1`.
### Kindly Mention
We have started this assignment since 4 weeks ago, and we spent most of daliy time to finish all the exercises. We are not pro at coding thus our coding might look very ugly and repeatable. Some function might not work unless you run all since we are really not good at coding.We don't even know how to define a class at the first day. Thus, if you could not run our code using the above steps, please run all. I m not asking for any sympathize, I just want you to run our code properly instead of showing any errors. Alough the coding skill is not good, but i think the logic of coding is worth to have a 'run all' (if you couldn't run the code using the above instructions). :D 

By the way, We have debugged many times in order to avoid 'run all' operation, it should be fine, but things always happens. Thus, it is just a mention.

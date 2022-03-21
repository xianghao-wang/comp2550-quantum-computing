## Assignment 1

**Name: ** **Xianghao Wang**

**UID**: **U7321615**

**Course: ** **COMP2550**

### Part 1 General Questions

#### Question 1: What is the branch in the survey paper you find most interesting and why? (1 mark)

The application of Quantum Approximation Optimisation Algorithm (QAOA) on combinatorial optimisation problems is the most interesting branch in this survey from my perspective. Firstly, QAOA can aid the solving of NP problem. The approximation of the solutions for combinatorial optimization problems, which including NP-complete problems such as Boolean Satisfiability (SAT) problem, could be gained via QAOA **[1]**.  A polynomial algorithm for a speicific NP-complete problem indicates that all NP-complete problems can be solved in polynomial complexity in terms of time **[2]**. Thus, with the development of QAOA, NP-complete problems are possible to be resolved. Secondly, QAOA can be combined with the classical machine learning techniques like reinforcement learning for optimisation **[1]** . With the support of mature and developed machine learning techniques, QAOA could be more feasible on practical problems. Thirdly, from my perspective, combinatorial optimisation problems such as Boolean Satisfiability problem are simple but difficult to find efficient algorithms. Discovering an elegant and natural algorithm is in fact attractive. 



#### Question 2: Write a summary of the branch that you pick in your own words (2 marks)

This branch involves QAOA and combinatorial optimisation problems. Each combinatorial optimisation problem is searching the best solution meeting the requirements of the problem from all possible binary strings in a fixed width. Taking MaxCut problem as an example, it requires to divide the nodes in a graph into two complementary sets $A$ and $B$, and maximise the sum of degree of the edges between these two sets. Each bit of the binary string indicates whether the corresponding node belongs to $A$ or $B$. Then, an objective function can be constructed to evaluate the input binary string, which is used for finding the binary string with maximum total degree of edges cut. QAOA convert the objective function to Ha



<div style="page-break-after: always;"></div>

### References

[1] Cerezo, M., Arrasmith, A., Babbush, R., Benjamin, S.C., Endo, S., Fujii, K., McClean, J.R., Mitarai, K., Yuan, X., Cincio, L. and Coles, P.J., 2021. Variational quantum algorithms. Nature Reviews Physics, 3(9), pp.625-644. https://doi.org/10.1038/s42254-021-00348-9

[2]

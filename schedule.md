# Tentative schedule  

|           | Monday 30/6       | Tuesday 1/7 | Wednesday 2/7| 
| --------- |:----------------- | ----------- | ------------ | 
| Morning   | conference        | conference  | conference   | 
| Afternoon | conference        | conference  | forum        | 
| Evening   | light reception   | Banquet     |              | 

## New Room

for Tuesday and Wednesday: Leture hall 15

## Monday 30/06

<table>
<tr>
 <td>8:30</td>
 <td><b>checkin and coffee</b></td>
</tr>
<tr>
 <td>9:00</td>
 <td><b>Opening, greetings and practical informations</b></td>
</tr>
<tr>
 <td></td>
 <td><b>Keynote 1</b> (chair: Christoph Dürr) </td>
</tr>
<tr>
<td>9:05</td>
 <td>
<b>Some mathematical problems in quantum circuit synthesis and optimization <br><i>Xiaoming Sun</i></b>
<details>
<summary>Abstract</summary>
Quantum circuits, serving as the foundational mathematical framework for quantum algorithm design, have become one of the key research areas in the field of quantum computing. As the field transitions beyond the Noisy Intermediate-Scale Quantum (NISQ) era, the synthesis and optimization of quantum circuits have emerged as critical challenges. While classical circuit complexity primarily focuses on minimizing size and depth, the complexity of quantum circuits demands a multi-objective approach encompassing additional metrics involving the number of auxiliary qubits, different energy levels used, and many other aspects. In this talk, we will discuss a series of new problems and recent research progress in quantum circuit compression, and explore theoretical connections between these problems and classical important problems such as Babai's conjecture about the diameter of Cayley graphs.
</details>
 </td>
</tr>
<tr>
 <td>9:55</td>
 <td><b>Short break</b></td>
</tr>

<tr>
 <td></td>
 <td><b>Morning session</b> (chair: Minming Li) </td>
</tr>

<tr>
<td>10:05</td>
<td> 
Mechanism Design for Auctions with Externalities on Budgets<br>
Yusen Zheng, <i>Yukun Cheng</i>, Chenyang Xu and <i>Xiaotie Deng</i><br>
<details><summary>Abstract</summary>
This paper studies mechanism design for auctions with externalities on budgets, a novel setting where the budgets that bidders commit are adjusted due to the externality of the competitors' allocation outcomes---a departure from traditional auctions with fixed budgets. This setting is motivated by real-world scenarios, for example, participants may increase their budgets in response to competitors' obtained items.  We initially propose a general framework with homogeneous externalities to capture the interdependence between budget updates and allocation, formalized through a budget response function that links each bidder's effective budget to the amount of items won by others.  The main contribution of this paper is to propose a truthful and individual rational auction mechanism for this novel auction setting, which achieves an approximation ratio of $1/3$ with respect to the liquid welfare. This mechanism is inspired by the uniform-price auction, in which an appropriate uniform price is selected to allocate items, ensuring the monotonicity of the allocation rule while accounting for budget adjustments. Additionally, this mechanism guarantees a constant approximation ratio by setting a purchase limit. Complementing this result, we establish an upper bound: no truthful mechanism can achieve an approximation ratio better than $1/2$. This work offers a new perspective to study the impact of externalities on auctions, providing an approach to handle budget externalities in multi-agent systems.</details>
</td>
</tr>
<tr>
<td>10:25</td>
<td> 
Less-excludable Mechanism for DAOs in Public Good Auctions<br>
<i>Jing Chen</i> and <i>Wentao Zhou</i><br>
<details><summary>Abstract</summary>
With the rise of smart contracts, decentralized autonomous organizations (DAOs) have emerged in public good auctions, allowing ``small'' bidders to gather together and enlarge their influence in high-valued auctions. However, models and mechanisms in the existing research literature do not guarantee {\em non-excludability}, which is a main property of public goods. As such, some members of the winning DAO may be explicitly prevented from accessing the public good. This side effect leads to regrouping of small bidders within the DAO to have a larger say in the final outcome. In particular, we provide a polynomial-time algorithm to compute the best regrouping of bidders that maximizes the total bidding power of a DAO. We also prove that such a regrouping is less-excludable, better aligning the needs of the entire DAO and the nature of public goods. Next, notice that members of a DAO in public good auctions often have a positive externality among themselves. Thus we introduce a {\em collective factor} into the members' utility functions. We further extend the mechanism's allocation for each member to allow for {\em partial access} to the public good. Under the new model, we propose a mechanism that is incentive compatible in generic games and achieves higher social welfare as well as less-excludable allocations.</details>
</td>
</tr>
<tr>
<td>10:45</td>
 <td><b>Coffee break</b></td>
</tr>
<tr>
<td>11:10</td>
<td> 
TBDS: Transaction-Based Data Sharing<br>
<i>Wu Xin</i>, Hongyin Chen, Xiaoqi Dong, Jichen Li, <i>Xiaotie Deng</i>, Zhonghai Wu and Bin Xiao<br>
<details><summary>Abstract</summary>
Data sharing is widely regarded as a critical approach to unlocking the value of data, encompassing data rights management, processing, and profit allocation. However, existing methods often suffer from fragmented designs, incompatible assumptions, and security challenges, perpetuating the issue of data silos. To address these limitations, we propose Transaction-Based Data Sharing (TBDS), a comprehensive and modular solution. TBDS adopts a formal-language-based data rights management module, maintaining compatibility across modules and enabling efficient permission verification and state updates. It leverages blockchain and Trusted Execution Environments (TEEs) to ensure secure operations while handling remote attestation internally, eliminating reliance on external parties. Furthermore, TBDS introduces a transaction-driven workflow, where smart contracts facilitate seamless interactions between modules. Finally, we design a chain-based profit allocation mechanism that balances incentives and privacy, ensuring fair and transparent distribution of rewards among participants. We also show that this mechanism improves participants' revenue. With these innovations, TBDS not only addresses the challenges of fragmented designs and security risks but also establishes a scalable and incentive-compatible framework, paving the way for more efficient and secure data-sharing ecosystems.</details>
</td>
</tr>
<tr>
<td>11:30</td>
<td> 
Characterizing Strategyproofness Through Score Functions in Voting Mechanisms<br>
<i>Felipe Furquim</i>, <i>Valentin Dardilhac</i>, Daniel Cordeiro and <i>Johanne Cohen</i><br>
<details><summary>Abstract</summary>
This work focuses on the strategyproofness of voting systems in which voters select multiple options from a set of possibilities. These systems include those that are used for Participatory Budgeting, where elections are held to determine the allocation of a community budget (e.g., city or regional level) for funding various projects. We present a model for analyzing voting mechanisms and the \emph{Constrained Change Property (CCP)}, which serves as a criterion for designing strategyproof voting mechanisms. Additionally, we define a new concept of a social choice function and leverage it to develop a new class of utilitarian voting mechanisms, referred to as \emph{score voting}. We prove that the mechanisms designed with core voting with a neutral score function are equivalent to knapsack voting on the same instance. Furthermore, we demonstrate that a score voting mechanism based on a total score function is strategyproof if and only if its score function satisfies CCP. Building on these findings, we propose an algorithm capable of identifying the closest total score function that ensures the strategyproofness of any given score voting mechanism.</details>
</td>
</tr>
<tr>
<td>11:50</td>
<td> 
Optimal Contract Design for Repurchasing Computing Resources<br> 
Zhengyan Deng, Yusen Zheng, Chenliang Sheng and Shaowen Qin<br>
<details><summary>Abstract</summary>
The rapid advancement of AI and other emerging technologies has triggered exponential growth in computing resources demand. Faced with prohibitive infrastructure costs for large-scale computing clusters, users are increasingly resorting to leased computing resources from third-party providers. However, prevalent overestimation of operational requirements frequently leads to substantial underutilization of the computing resources. To mitigate such inefficiency, we propose a contract-based incentive framework for computing resources repurchasing. Comparing to auction mechanisms, our design enables providers to reclaim and reallocate surplus computing resources through market-driven incentives. Our framework operates in a multi-parameter environment where both clients’ idle resource capacities and their unit valuations of retained resources are private information, posing a significant challenge to contract design. Two scenarios are considered based on whether all clients possess the same amount of idle resource capacity. By transforming the contract design problem into solving a mathematical program, we obtain the optimal contracts for each scenario, which can maximize the utility of computing resources providers while ensuring the requirements of incentive compatibility (IC) and individual rationality (IR). This innovative design not only provides an effective approach to reduce the inefficient utilization of computing resources, but also establishes a market-oriented paradigm for sustainable computing ecosystems.</details>
</td>
</tr>
<tr>
<td>12:10</td>
<td> 
A Comparative Study of Waitlist Mechanisms: Deferral Versus Pay-Per-Offer<br>
Zhou Chen, Qi Qi, Hao Sun and <i>Muyang Zhao</i><br>
<details><summary>Abstract</summary>
This paper investigates waitlist mechanisms for public housing allocation, introducing the pay-per-offer mechanism as a novel alternative to the deferral-based approach. Through a Markov decision process, dynamically arriving items are allocated to waiting agents with heterogeneous values for different items and diverse outside options. Key contributions include analysis of optimal strategies for agents in these mechanisms, evaluation of how evaluation metrics vary based on the distribution of outside options and waitlist parameters. We provides valuable insights into the design and impact of various waitlist mechanisms.</details>
</td>
</tr>


<tr>
<td>12:30</td>
 <td><b>Lunch break</b></td>
</tr>

<tr>
<td></td>
 <td><b>Forum 1. Quantum Computing</b> (chair: Kun He)</td>
</tr>

<tr>
<td>13:30</td>
 <td>
<b>Forum 1-1.</b> Penghui Yao. On the Computational Power of QAC0 with Barely Superlinear Ancillae
<details>
<summary>Abstract</summary>
$\mathrm{QAC}^0$ is the family of constant-depth polynomial-size quantum circuits consisting of arbitrary single qubit unitaries and multi-qubit Toffoli gates. It was introduced by Moore [arXiv: 9903046] as a quantum counterpart of $\mathrm{AC}^0$, along with the conjecture that $\mathrm{QAC}^0$ circuits can not compute PARITY. In this work we make progress on this longstanding conjecture: we show that any depth-$d$ $\mathrm{QAC}^0$ circuit requires $n^{1+3^{-d}}$ ancillae to compute a function with approximate degree $\Theta(n)$, which includes PARITY, MAJORITY and $\mathrm{MOD}_k$. This is the first superlinear lower bound on the size of the ancillae required for computing parity. We further establish superlinear lower bounds on quantum state synthesis and quantum channel synthesis. These lower bounds are derived by giving low-degree approximations to $\mathrm{QAC}^0$ circuits. We show that a depth-$d$ $\mathrm{QAC}^0$ circuit with $a$ ancillae, when applied to low-degree operators, has a degree $(n+a)^{1-3^{-d}}$ polynomial approximation in the spectral norm. This implies that the class $\mathrm{QLC}^0$, corresponding to linear size $\mathrm{QAC}^0$ circuits, has approximate degree $o(n)$. This is a quantum generalization of the result that $\mathrm{LC}^0$ circuits have approximate degree $o(n)$ by Bun, Kothari, and Thaler [SODA 2019]. Our result also implies that $\mathrm{QLC}^0\neq\mathrm{NC}^1$.<br><br>

Biography: Penghui Yao is a professor in the Department of Computer Science and Technology, Nanjing University. He obtained his doctoral degree from Centre for Quantum Technology, National University of Singapore. Prior to joining Nanjing University, He was a postdoctoral researcher at CWI Netherlands;  IQC University of Waterloo and QuICS University of Maryland. His research mainly focuses on quantum algorithms, quantum information theory and quantum computational complexity.
</details>
 </td>
</tr>

<tr>
<td>14:00</td>
 <td>
<b>Forum 1-2.</b> Bujiao Wu. State Similarity in Modular Superconducting Quantum Processors with Classical Communications
<details>
<summary>Abstract</summary>
As quantum devices continue to scale, distributed quantum computing emerges as a promising strategy for executing large-scale tasks across modular quantum processors. A central challenge in this paradigm is verifying the correctness of computational outcomes when subcircuits are executed independently following circuit cutting. In this work, we propose a cross-platform fidelity estimation algorithm tailored for modular architectures. Our method achieves substantial reductions in sample complexity compared to previous approaches designed for single-processor systems. We experimentally implement the protocol on modular superconducting quantum processors with up to 6 qubits to verify the similarity of two 11-qubit GHZ states. Beyond verification, we show that our algorithm enables a federated quantum kernel method that preserves data privacy. As a proof of concept, we apply it to a 5-qubit quantum phase learning task using six 3-qubit modules, successfully extracting phase information with just eight training samples. These results establish a practical path for
scalable verification and trustworthy quantum machine learning of modular quantum processors.

Reference: Wu, Bujiao, et al. "State Similarity in Modular Superconducting Quantum Processors with Classical Communications." arXiv preprint arXiv:2506.01657 (2025).
<br><br>
Biography: Bujiao Wu, an associate researcher at the International Quantum Academy. Her main research areas include the design of quantum algorithms, optimization of quantum circuits, quantum randomized measurements, quantum machine learning, and quantum advantages.
</details>
 </td>
</tr>

<tr>
<td>14:30</td>
 <td>
<b>Forum 1-3.</b> Yiming Huang. Learning unitary process with autoregressive neural network
<details><summary>Abstract</summary>
Characterizing quantum processes is a cornerstone of quantum information science, but conventional techniques like quantum process tomography (QPT) demand extensive resources and suffer from poor scalability. Here, we propose a learning-based approach that leverages the generative model to efficiently learn Hamiltonian dynamics. By decomposing such dynamics into a linear combination of Pauli operators, with the expansion coefficients parameterized by an autoregressive neural network (ARNN), we design an infidelity loss and then train the ARNN to learn such unitary process. Our numerical experiments demonstrate that our proposed model offers a scalable and flexible pathway for characterizing quantum operations with potential applications in quantum computing and quantum information processing.<br><br>
Biography: Yiming Huang, a postdoctoral fellow at the Center on Frontiers of Computing Studies, Peking University, mainly focus on quantum algorithm and optimization for NISQ devices, and leveraging machine learning to tackle problems in quantum chemistry and many-body physics. His work aims to advance the application of quantum computing and machine learning in complex optimization and data processing.
</details>
 </td>
</tr>
<tr>
<td></td>
<td><b>Afternoon session</b> (chair: Thomas Erlebach) </td>
</tr>
<tr>
<td>15:00</td>
<td> 
Complexity Classes for Online Problems with and without Predictions<br>
<i>Magnus Berg</i>, Joan Boyar, Lene M. Favrholdt and Kim S. Larsen<br>
<details><summary>Abstract</summary>
With the developments in machine learning, there has been a surge in interest and results focused on algorithms utilizing predictions, not least in online algorithms where most new results incorporate the prediction aspect for concrete online problems. While the structural computational hardness of problems with regards to time and space is quite well developed, not much is known about online problems where time and space resources are typically not in focus. Some information-theoretical insights were gained when researchers considered online algorithms with oracle advice, but predictions of uncertain quality is a very different matter. We initiate the development of a complexity theory for online problems with predictions, focusing on binary predictions for minimization problems. Based on the most generic hard online problem type, string guessing, we define a family of hierarchies of complexity classes (indexed by pairs of error measures) and develop notions of reductions, class membership, hardness, and completeness. Our framework contains all the tools one expects to find when working with complexity, and we illustrate our tools by analyzing problems with different characteristics. In addition, we show that known lower bounds for paging with predictions apply directly to all hard problems for each class in the hierarchy based on the canonical pair of error measures. Our work also implies corresponding complexity classes for classic online problems without predictions, with the corresponding complete problems.</details>
</td>
</tr>
<tr>
<td>15:20</td>
<td> 
Comparing the Hardness of Online Minimization and Maximization Problems with Predictions<br>
<i>Magnus Berg</i><br>
<details><summary>Abstract</summary>
We build on the work of Berg, Boyar, Favrholdt, and Larsen, who developed a complexity theory for online problems with and without predictions (IJTCS-FAW 2025) where they define a hierarchy of complexity classes that classifies online problems based on the competitiveness of best possible deterministic online algorithms for each problem. Their work focused on online minimization problems and we continue their work by considering online maximization problems. First, we compare the competitiveness of the base online minimization problem from Berg, Boyar, Favrholdt, and Larsen, Asymmetric String Guessing, to the competitiveness of Online Bounded Degree Independent Set. Formally, we show that there exists algorithms of any given competitiveness for Asymmetric String Guessing if and only if there exists algorithms of the same competitiveness for Online Bounded Degree Independent Set, while respecting that the competitiveness of algorithms is measured differently for minimization and maximization problems. Moreover, we give several hardness preserving reductions between different online maximization problems, which imply new membership, hardness, and completeness results for the complexity classes. Finally, we show new positive and negative algorithmic results for (among others) Online Bounded Degree Independent Set, Online Interval Scheduling, Online Set Packing, and Online Bounded Degree Clique.</details>
</td>
</tr>
<tr>
<td>15:40</td>
 <td><b>Coffee break</b></td>
</tr>
<tr>
<td>16:00</td>
<td> 
Oblivious Robots Under Round Robin: Gathering on Rings<br>
Alfredo Navarra and <i>Francesco Piselli</i><br>
<details><summary>Abstract</summary>
Robots with very limited capabilities are placed on the vertices of a graph and are required to move toward a single, common vertex, where they remain stationary once they arrive. This task is referred to as the {\gath} problem. Most of the research on this topic has focused on feasibility challenges in the \emph{asynchronous} setting, where robots operate independently of each other. A common assumption in these studies is that robots are equipped with \emph{multiplicity detection}, the ability to recognize whether a vertex is occupied by more than one robot. Additionally, initial configurations are often restricted to ensure that no vertex hosts more than one robot. A key difficulty arises from the possible symmetries in the robots’ placement relative to the graph's topology. This paper investigates the {\gath} problem on Rings under a \emph{sequential} scheduler, where only one robot at a time is active. While this sequential activation helps to break symmetries, we remove two common assumptions: robots do not have multiplicity detection, and in initial configurations, vertices can be occupied by multiplicities. We prove that such a generalized {\gath} problem cannot be solved under any sequential schedulers. However, we provide a complete characterization of the problem when a sequential \emph{Round Robin} scheduler is used, where robots are activated one at a time in a fixed cyclic order that repeats indefinitely. Furthermore, we fully characterize the {\dgath} problem, the most used variant of {\gath}, in which the initial configurations do not admit multiplicities.</details>
</td>
</tr>
<tr>
<td>16:20</td>
<td> 
The online power cover problem on a line<br>
Zhonghao Liu, Man Xiao, <i>Xiaofei Liu</i> and Weidong Li<br>
<details><summary>Abstract</summary>
In this paper, we study the online power cover problem on a line. Suppose $L$ is a line on the plane, and $S$ is a set of sensors on the line $L$, and each sensor can deploy a power and generate a covered area that can cover users. This problem is to find a minimum power assignment to cover a sequence of users on the line $L$ arriving one by one. In this paper, we first prove that the lower bound is $2$ for this problem even when $|S|=2$. Then, we present an online algorithm with a competitive ratio that is no more than $|S|$ based on the greedy technique. Note that, this algorithm is the best possible online algorithm for this problem with $|S|=2$. Finally, we consider a special case of this problem, in which $S=\{s_0,s_1,s_2\}$ and $d(s_0,s_1)=d(s_1,s_2)$, and present an online algorithm with a competitive ratio that is no more than $\sqrt{2}+1$.</details>
</td>
</tr>

<tr>
<td>16:40</td>
 <td><b>Short break</b></td>
</tr>


<tr>
<td>16:50</td>
<td> 
Multiplication of 0-1 matrices via clustering<br>
<i>Jesper Jansson</i>, Miroslaw Kowaluk, Andrzej Lingas and Mia Persson<br>
<details><summary>Abstract</summary>
We study applications of clustering (in particular the $k$-center clustering problem) in the design of efficient and practical deterministic algorithms for computing an approximate and the exact arithmetic matrix product of two 0-1 rectangular matrices $A$ and $B$ with clustered rows or columns, respectively. Let $\lambda_A$ and $\lambda_B$ denote the minimum maximum radius of a cluster in an $\ell$-center clustering of the rows of $A$ and in a $k$-center clustering of the columns of $B,$ respectively. In particular, when $A$ and $B$ are square matrices of size $n\times n$, we obtain the following results. \begin{enumerate} \item A simple deterministic algorithm that approximates each entry of the arithmetic matrix product of $A$ and $B$ within an additive error of at most $2\lambda_A$ in $O(n^2\ell)$ time or at most $2\lambda_B$ in $O(n^2k)$ time. \item A simple deterministic preprocessing of the matrices $A$ and $B$ in $O(n^2\ell)$ time or $O(n^2k)$ time after which every query asking for the exact value of an arbitrary entry of the arithmetic matrix product of $A$ and $B$ can be answered in $O(\lambda_A)$ time or $O(\lambda_B)$ time, respectively. \item A simple deterministic algorithm for the exact arithmetic matrix product of $A$ and $B$ running in time $O(n^2(\ell+k+\min\{\lambda_A,\lambda_B\}))$. \end{enumerate}</details>
</td>
</tr>
<tr>
<td>17:10</td>
<td> 
Scheduling with Testing: Competitive Algorithms for Minimizing the Total Weighted Completion Time in the Adversarial Model<br>
<i>Felix Buld</i> and Andreas S. Schulz<br>
<details><summary>Abstract</summary>
We establish the first theoretical results for scheduling with testing on a single machine and on identical parallel machines to minimize the total \emph{weighted} completion time in the adversarial model. We present a deterministic algorithm with a competitive ratio of 2.3166 for single-machine scheduling and show that a randomized variant has a competitive ratio of 2.1523. These algorithms, combined with list scheduling, yield competitive ratios of 2.7763 and 2.5110 for identical parallel machine scheduling.</details>
</td>
</tr>
<tr>
<td>17:30</td>
 <td>
<b>Forum.</b> Women in science
 </td>
</tr>



<tr>
<td>18:30</td>
 <td>
  <details>
<summary><b>Light reception</b></summary>
Located in Sorbonne University, Campus les Cordeliers, 15 rue de l'École-de-médecine, 75006 Paris, Métro Odéon, room Marie-Curie. It is at walking distance from the conference site.
</details>
 </td>
</tr>
</table>

## Tuesday 1/07

<table>
<tr>
<td>08:30</td>
<td> 
<b>Coffee</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Keynote 2</b> (chair: Evripidis Bampis) </td>
</tr>
<tr>
<td>9:00</td>
<td> 
<b>Regularization, Heuristics, and Strategy: A Long Journey Towards Understanding a Few Fundamental yet Fuzzy Concepts in Computing<br> 
<i>Shanghua Teng</i></b><br>
<details><summary>Abstract</summary>
"Thinking outside the box" has long been a defining trait of theoretical computer science. As a field, we value elegant theories, enlightening proofs, and insightful — sometimes unexpected — connections. However, we also look beyond theory to the practical world, seeking inspiration, establishing links, and explaining empirical trends. We aim for models that capture the essence of fundamental tasks, and for theories that shed insight on basic phenomena in computing.

In this talk, I will highlight how a long journey towards understanding a few fundamental, yet fuzzy, concepts in computing—specifically, “heuristics” (in algorithm design and AI), "regularization" (in machine learning), and “strategies” (in game and combinatorial game theory)—has led to the development of new conceptual frameworks, algorithmic techniques, and mathematical theories.
<br><br>
Short-Bio: Shang-Hua Teng is a University Professor and Seely G. Mudd Professor of Computer Science and Mathematics at USC. He is a fellow of SIAM, ACM, and Alfred P. Sloan Foundation, and has twice won the Gödel Prize, first in 2008, for developing smoothed analysis, and then in 2015, for designing the breakthrough scalable Laplacian solver. Citing him as, “one of the most original theoretical computer scientists in the world”, the Simons Foundation named him a 2014 Simons Investigator to pursue long-term curiosity-driven fundamental research. He also received the 2009 Fulkerson Prize,  2023 Science & Technology Award for Overseas Chinese from the China Computer Federation, 2022 ACM SIGecom Test of Time Award (for settling the complexity of computing a Nash equilibrium), 2021 ACM STOC Test of Time Award (for smoothed analysis), 2020 Phi Kappa Phi Faculty Recognition Award (2020)  for his book Scalable Algorithms for Data and Network Analysis, 2025 STOC Test of Time Award and 2011 STOC Best Paper Award (for improving maximum-flow minimum-cut algorithms). In addition, he and collaborators developed the first optimal well-shaped Delaunay mesh generation algorithms for arbitrary three-dimensional domains, settled the Rousseeuw-Hubert regression-depth conjecture in robust statistics, and resolved two long-standing complexity-theoretical questions regarding the Sprague-Grundy theorem in combinatorial game theory. For his industry work with Xerox, NASA, Intel, IBM, Akamai, and Microsoft, he received fifteen patents in areas including compiler optimization, Internet technology, and social networks.
</details>
</td>
</tr>
<tr>
<td>09:50</td>
<td>
<b>Short break</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Morning session</b> (chair: Ruilong Zhang) </td>
</tr>
<tr>
<td>10:00</td>
<td> 
Mixed Graph Covering with Target Constraints<br>
Xujin Chen, <i>Xiyuan Deng</i>, Xiaodong Hu and <i>Changjun Wang</i><br>
<details><summary>Abstract</summary>
The <i>target-constrained mixed graph covering</i> (TMGC) problem considers a graph where edges and vertices are each assigned a cost and a weight. The goal is to select a minimum-cost subset of vertices and edges subject to the covering-target constraint that its covered weight (i.e., the total weight of the selected vertices, selected edges, and edges incident to the selected vertices) meets or exceeds a given threshold. This problem models real-world scenarios, like optimizing the removal of facilities (vertices) and roads (edges) in a network while ensuring the value of the remaining network (including the value of remaining facilities and their connecting roads) remains below a specified limit. From a theoretical perspective, this TMGC model extends the weighted partial vertex cover problem in two significant ways: it incorporates covering weights for both edges and vertices, and it allows a direct selection of edges alongside vertices to satisfy the covering target. Despite this increased complexity and generality compared to (the partial version of) the classic vertex cover problem, we develop a 2-approximation primal-dual algorithm for TMGC, whose ratio 2 matches the known lower bound for the simpler vertex cover problem.</details>
</td>
</tr>
<tr>
<td>10:20</td>
<td> 
From MAXCUT to MAXNAESAT: Elegant Proofs and Algorithmic Advances<br>
*Sangram Jena* and K. Subramani<br>
<details><summary>Abstract</summary>
In this paper, we investigate the approximation and parameterized complexities of MAXNAESAT variants. We begin by presenting a simple yet rigorous proof establishing the <b>APX-completeness</b> of the MAXNAE2SAT problem. Notably, <b>APX-completeness</b> holds even when the repetition factor of each variable is bounded by $3$, i.e., each variable appears in at most three clauses in the MAXNAE2SAT instance. Our <b>APX-completeness</b> proof is a strict reduction that directly establishes a new inapproximability bound for the MAXNAE2SAT problem. The decision version of MAXNAE2SAT remains <b>NP-complete</b> when the repetition factor of each variable is bounded by $3$, mirroring the <b>NP-completeness</b> of MAXCUT in cubic graphs. We further establish a tight computational dichotomy by proving that the MAXNAE2SAT problem is solvable in linear time when the repetition factor of each variable is bounded by $2$. Finally, we present a <b>fixed-parameter tractable</b> algorithm for MAXNAE2SAT instances where the repetition factor of each variable is bounded by $3$.</details>
</td>
</tr>
<tr>
<td>10:40</td>
<td>
<b>Coffee break</b>
</td>
</tr>
<tr>
<td>11:10</td>
<td> 
Approximation Algorithms for Individual Preference Facility Location<br>
<i>Shuilian Liu</i>, Yicheng Xu and Yong Zhang<br>
<details><summary>Abstract</summary>
We study the facility location problem in the context of individual fairness to propose the <i>Individual Preference Facility Location</i> (IPFL) problem. In the vanilla facility location problem, the goal is to select a subset of facilities to serve all clients while minimizing total opening and connection costs. IPFL aims to optimize the facility location objective while meeting individual preferences by requiring that each client is served by a facility within its fair radius. The fair radius is defined as the distance between a client and its  $\tau$-th nearest neighbor, where $\tau$ is a carefully designed parameter. IPFL balances facility load by opening more facilities in dense areas. However, a few clients may disproportionately affect the final costs or violate the individual preference constraints. To address this, we extend IPFL to its outlier variant, IPFLO, where up to $m$ clients can remain unserved. As our contribution, we provide 2-approximation algorithms for both IPFL and IPFLO using a dual fitting technique.</details>
</td>
</tr>
<tr>
<td>11:30</td>
<td> 
An LP-rounding based algorithm for soft capacitated facility location problem with submodular penalties<br> 
Hanyin Xiao, Jiaming Zhang, Zhikang Zhang and Weidong Li<br>
<details><summary>Abstract</summary>
The soft capacitated facility location problem (SCFLP) is a classic combinatorial optimization problem with widespread applications in operations research and computer science. Given a facility set $\mathcal{F}$ and a client set $\mathcal{D}$, each facility $i$ has a capacity $u_i$ and an open cost $f_i$, allowing to open multiple times, and each client $j$ has a demand $d_j$. The SCFLP is to find a facility subset in $\mathcal{F}$ and connect each client to the facilities opened, such that the total cost including open cost and connection cost is minimized. SCFLP is NP-hard, motivating research into approximation algorithms. This paper considers a variant: the soft capacitated facility location problem with submodular penalties (SCFLPSP), where some clients may remain unserved at a penalty cost. We focus on the integer splittable case, where a client's demand can be served by multiple facilities in integer amount. Using LP-rounding, we propose a $(\lambda R+4)$-approximation algorithm, where $R=\frac{\max_{i \in \mathcal{F} }f_i}{\min_{i \in \mathcal{F} }f_i},\lambda=\frac{R+\sqrt{R^2+8R}}{2R}$. Notably, when the open cost is uniform, the approximation ratio is 6.</details>
</td>
</tr>
<tr>
<td>11:50</td>
<td> 
The Subinterval Cover Problem<br>
Kelin Luo, <i>Chenran Yang</i>, Zonghan Yang and Yuhao Zhang<br>
<details><summary>Abstract</summary>
In this paper, we introduce the subinterval cover problem. Given a set of interval candidates, each associated with a specific cost factor, we need to select a subinterval from each candidate to cover the entire range. The cost of selecting a subinterval in a candidate interval is determined by multiplying the selected length by the cost factor (the weight). Our goal is to minimize the total cost. This problem has broad applications, such as drone delivery and robot motion planning. Our first finding is that a natural LP formulation of the problem has an unbounded integrality gap, which highlights the challenge of studying this problem. Second, we develop polynomial-time dynamic programming algorithms for two special cases: 1) two distinct cost factors; 2) a constant number of distinct cost factors, and the interval candidates form a laminar set family: each pair of intervals is either disjoint, or one interval contains the other. As a corollary of our dynamic programming algorithm, we design a polynomial-time $\sqrt{w_{\max}/{w_{\min}}}$-approximation algorithm for the general cases, where $w_{\max}$ and $w_{\min}$ are the maximum and minimum weights of the intervals, respectively.</details>
</td>
</tr>
<tr>
<td>12:10</td>
<td> 
The Capacity-Constrained Facility Location Problem with Ordinal Preferences: Algorithmic and Mechanism Design Perspectives<br>
Zifan Gong, Alexander Lam, Momcilo Mrkaic, Yachao Yan and <i>Yingchao Zhao</i><br>
<details><summary>Abstract</summary>
We study a variation of the facility location problem that involves finding ideal locations for capacitated facilities and assigning agents to these facilities. Additionally, each agent has an ordinal ranking over the facilities and incurs a cost related to both the ranking and the distance from their assigned facility. Our work focuses on minimizing the maximum cost and total cost. For these objectives, we show that computing an optimal solution is intractable in general, but we provide exact algorithms that run in polynomial time when the number of facilities is constant. We then move to the mechanism design setting, where the agents' preferences are private information, and design strategy-proof mechanisms which have a bounded approximation for our objectives.</details>
</td>
</tr>
<tr>
<td>12:30</td>
<td>
<b>Lunch break</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Forum 2. Multi-agent Learning, Multi-agent System, Multi-agent Games</b> (chair: Ruilong Zhang)<br>
</td>
</tr>
<tr>
<td>14:00</td>
<td> 
<b>Forum 2-1.</b> From Games to Graphs: Causal Mechanisms for Steering Multi-Agent Outcomes<br> 
<i>Mengyue Yang</i><br>
<details><summary>Abstract</summary>
Multi-agent systems are increasingly deployed in dynamic environments where agents must coordinate their strategies to achieve optimal outcomes. However, conventional game-theoretic approaches often struggle with issues such as multiple Nash equilibria, limited agent controllability, and scalability constraints. In this talk, I will introduce a causal intervention perspective to address these challenges. By leveraging structural causal games and multi-agent influence diagrams, we reformulate coordination problems as inference tasks on causal graphs. This enables localized interventions - so-called pre-policy interventions, that steer agent behavior toward globally desirable equilibria, even when full control over all agents is infeasible. I will discuss how these methods align with human preferences, break cyclic dependencies in strategy updates, and enhance robustness in both simulated environments and real-world applications such as human-AI collaboration. This causal lens offers a principled framework for influencing emergent outcomes in complex multi-agent systems.<br><br>

Bio: Mengyue Yang is a Lecturer in AI at the University of Bristol. Her research interests span causality, reinforcement learning, multi-agent systems, and world modeling. She received her PhD from University College London (UCL), where she developed influential methods for causal representation learning. Recognized as a Rising Star in AI in 2024, Mengyue actively contributes to the academic community by organizing international workshops and exploring interdisciplinary approaches to robust, dynamic decision-making systems.
</details>
</td>
</tr>
<tr>
<td>14:30</td>
<td>
<b>Coffee break</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Afternoon session</b> (chair: Vincent Chau) </td>
</tr>
<tr>
<td>14:50</td>
<td> 
Minimizing Blocking Agents for Stable Matching with Partial Approval Information<br> 
Yitian Gao, Jiaxue Li, <i>Junjie Luo</i> and Yiheng Zhang<br>
<details><summary>Abstract</summary>
We study the stable matching problem with partial information, where agents submit only partial approval preferences, and the goal is to find a matching that is as stable as possible in the worst-case scenario. Unlike previous studies that focus solely on the Stable Marriage setting and measure stability by the number of blocking pairs, we explore another well-explored stability measure: the number of blocking agents. Additionally, we extend our analysis to both the Stable Roommates and Hospital/Residents problems. Our findings offer a comprehensive view of the computational complexity across these problem variants, highlighting interesting contrasts between blocking agents and blocking pairs, as well as among the three stable matching settings.</details>
</td>
</tr>
<tr>
<td>15:10</td>
<td> 
Pure Nash Equilibria of Weighted Picking Sequence Protocol is WEF1 for Two Agents<br> 
Rufan Bai, Huahua Miao, Xiaowei Wu, <i>Cong Zhang</i> and Shengwei Zhou<br>
<details><summary>Abstract</summary>
We consider the problem of allocating a set of indivisible goods to a set of strategic agents with arbitrary weights. While <i>truthful</i> mechanism is hard to guarantee any non-trivial fairness, Amanatidis et al. (WINE 2021 and MOR 2024) studied the fairness guarantees of the equilibria of the <i>Round-Robin</i> mechanism. They show that when all agents have the same weight, every pure Nash equilibrium of Round-Robin leads to an envy-free up to one item (EF1) allocation, with respect to agents' <i>true valuations</i>. In this paper, we investigate the weighted setting where agents are asymmetric and study the <i>weighted picking sequence protocol</i>, which is a natural extension of <i>Round-Robin</i> in the weighted setting. More specifically, we show that the <i>weighted picking sequence protocol</i> always has pure Nash equilibria and all the corresponding allocations are weighted EF1 with respect to the <i>true valuation functions</i> for two agents.</details>
</td>
</tr>
<tr>
<td>15:30</td>
<td>
<b>Coffee break</b>
</td>
</tr>
<tr>
<td>16:00</td>
<td> 
A Payoff-Based Policy Gradient Method in Stochastic Games with Long-Run Average Payoffs<br>
<i>Junyue Zhang</i> and <i>Yifen Mu</i><br>
<details><summary>Abstract</summary>
Despite the significant potential for various applications, stochastic games with long-run average payoffs have received limited scholarly attention, particularly concerning the development of learning algorithms for them due to the challenges of mathematical analysis. In this paper, we study the stochastic games with long-run average payoffs and present an equivalent formulation for individual payoff gradients by defining advantage functions which will be proved to be bounded. This discovery allows us to demonstrate that the individual payoff gradient function is Lipschitz continuous with respect to the policy profile. Leveraging these insights, we devise a payoff-based gradient estimation approach and integrate it with the Regularized Robbins-Monro method from stochastic approximation theory to construct a bandit learning algorithm suited for stochastic games with long-run average payoffs. Additionally, we prove that if all players adopt our algorithm, the policy profile employed will asymptotically converge to a Nash equilibrium with probability one, provided that all Nash equilibria are globally neutrally stable and a globally variationally stable Nash equilibrium exists. This condition represents a wide class of games, including monotone games.</details>
</td>
</tr>
<tr>
<td>16:20</td>
<td> 
Regularized Minimax-V Learning for Solving Randomly Terminating Two-player Zero-sum Markov Games<br>
<i>Xinxiang Guo</i> and <i>Yifen Mu</i><br>
<details><summary>Abstract</summary>
In this paper, we investigate randomly terminating two-player zero-sum Markov games. This game model differs from infinite-horizon discounted zero-sum Markov games and can be used to model many practical scenarios; however, related work on such games is still insufficient. We propose the regularized minimax-V learning algorithm and prove that the value sequence generated by this algorithm converges to the minimax value function with an appropriate choice of regularization parameter sequence. This algorithm applies the Euclidean regularization technique to accelerate the convergence in a different way compared with previous literature. Through simulation experiments, we demonstrate the convergence of regularized minimax-V learning algorithm in the ratio game and a randomly generated Markov game. To the best of our knowledge, for randomly terminating two-player zero-sum Markov games, this paper presents the first accelerated NE-solving algorithm.</details>
</td>
</tr>
<tr>
<td>16:40</td>
<td>
<b>Short break</b>
</td>
</tr>
<tr>
<td>16:50</td>
<td> 
Improved Approximation of Maximin Share Fair Allocation under Generalized Assignment Constraints<br> 
<i>Bo Li</i>, Ankang Sun and Md.Habibur Rahman Sifat<br>
<details><summary>Abstract</summary>
Generalized assignment is one of the constraints that has been widely studied in fair allocation problems. Existing research has mostly focused on (approximate) envy-freeness. In this work, we consider the maximin share (MMS) fairness. It has been observed that under generalized assignment constraints, the agents' valuations are fractionally subadditive and thus a $\frac{3}{13}(\approx 0.230)$-approximate MMS fair allocation exists, as shown by Akrami et al. [NeurIPS 2023]. In this paper, we improve the approximation ratio to $\frac{4}{15} \approx 0.266$. For the case of two agents, we improve the approximation to $\frac{2}{3}$, and prove that this bound is tight.</details>
</td>
</tr>
<tr>
<td>17:10</td>
<td> 
Fair Value Distribution in Cooperative Committee Election<br>
<i>Ying Qin</i>, Zeyu Ren, Zihe Wang and Jie Zhang<br>
<details><summary>Abstract</summary>
We consider a scenario where a group of agents needs to elect a committee to lead them in accomplishing a project. They elect a committee to maximize social welfare, and the question is how to distribute the total value of the project to every agent. This scenario encodes a cooperative game setting where the reward of the chosen coalition must be distributed fairly. First, we establish the axiomatic foundation of solution concepts in this cooperative committee election game. We show that a natural extension of Shapley value to this game does not meet the classical axioms when the values of different coalitions are binary. We then propose a value distribution rule that satisfies all the desired properties. Furthermore, we prove that this rule is unique in meeting these properties and also satisfies an additional monotonicity property. When the values of the coalitions can take any general values, we decompose the game into a linear combination of simple games. This decomposition is unique, allowing us to extend our value distribution rule to solve this general class of games.</details>
</td>
</tr>

<tr>
<td>18:30</td>
<td>
<details><summary><b>Gala dinner</b></summary>
Restaurant Macéo, 15 Rue des Petits Champs, 75001 Paris<br>
 45 minutes walk from Jussieu
<br>
 or Métro line 7 from Jussieu to Pyramides in 22 minutes
</details>
</td>
</tr>
</table>


## Wednesday 2/07

<table>
<tr>
<td>08:30</td>
<td>
<b>Coffee</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Keynote 3</b> (chair: Vincent Chau) </td>
</tr>
<tr>
<td>09:00</td>
<td>
<b>On stability in simple cooperative games <br>
<i>Gabrielle Demange</i></b>
<details><summary>Abstract</summary>
TBA
</details>
</td>
</tr>
<tr>
<td>09:50</td>
<td>
<b>Short break</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Morning before break session</b> (chair: Christoph Dürr) </td>
</tr>
<tr>
<td>10:00</td>
<td> 
Finding a Set of Long Common Substrings with Repeats from $m$ Input Strings<br>
Tiantian Li, <i>Lusheng Wang</i>, and Daming Zhu<br>
<details><summary>Abstract</summary>
In this paper, we propose two string problems, and study algorithms and complexity of various versions for those problems. Let $S=\{s_1, s_2, \ldots, s_m\}$ be a set of $m$ strings. A {\it common substring of $S$} is a substring appearing in every string in $S$. Given a set of $m$ strings $S=\{s_1, s_2, \ldots, s_m\}$ and a positive integer $k$, we want to find a set $C$ of $k$ common substrings of $S$ such that the $k$ common substrings in $C$ appear in the same order and have no overlap among the $m$ input strings in $S$, and the total length of the $k$ common substring in $C$ is maximized. This problem is referred to as the {\it longest total length of $k$ common substrings from $m$ input strings} ($LCSS(k,m)$ for short). The other problem we study here is called the {\it longest total length of a set of common substrings with length more than $l$ from $m$ input string} ($LSCSS(l,m)$ for short). Given a set of $m$ strings $S=\{s_1, s_2, \ldots, s_m\}$ and a positive integer $l$, for $LSCSS(l,m)$, we want to find a set of common substrings of $S$, each is of length more than $l$, such that the total length of all the common substrings is maximized. We show that both problems are NP-hard when $k$ and $m$ are variables. We propose dynamic programming algorithms with time complexity $O(k$ $n_1n_2)$ and $O(n_1n_2)$ to solve $LCSS(k, 2)$ and $LSCSS(l, 2)$, respectively, where $n_1$ and $n_2$ are the lengths of the two input strings. We then design an algorithm for $LSCSS(l,m)$ when every length $>l$ common substring appears once in each of the $m-1$ input strings. The running time is $O(n^2_1m)$, where $n_1$ is the length of the input string with no restriction on length $>l$ common substrings. Finally, we propose a fixed parameter algorithm for $LSCSS(l, m)$, where each length $> l$ common substring appears $m -1 + c$ times among the $m- 1$ input strings (other than $s_1$). In other words, each length $> l$ common substring may repeatedly appear at most $c$ times among the $m-1$ input strings $\{s_2, s_3, \ldots, s_m\}$. The running time of the proposed algorithm is $O((n_12^c)^2m)$, where $n_1$ is the input string with no restriction on repeats. The $LSCSS(l, m)$ is proposed to handle whole chromosome sequence alignment for different strains of the same species, where more than $98$.</details>
</td>
</tr>
<tr>
<td>10:20</td>
<td> 
$k$-Universality of Regular Languages Revisited<br>
Duncan Adamson, Pamela Fleischmann, <i>Annika Huch</i>, Tore Koß and Florin Manea<br>
<details><summary>Abstract</summary>
A subsequence of a word $w$ is a word $u$ such that $u = w[i_1] w[i_2] \cdots w[i_k]$, for some set of indices $1 \leq i_1 < i_2 < \dots < i_k \leq \vert w \vert$. A word $w$ is $k$-subsequence universal over an alphabet $\Sigma$ if every word over $\Sigma$ up to length $k$ appears in $w$ as a subsequence. In this paper, we revisit the problem $k$-ESU of deciding, for a given integer $k$, whether a regular language, given either as nondeterministic finite automaton or as a regular expression, contains a $k$-universal word.  [Adamson et al., ISAAC 2023] showed that this problem is NP-hard, even in the case when $k=1$, and an FPT algorithm w.r.t. the size of the input alphabet was given. In this paper, we improve the aforementioned algorithmic result and complete the analysis of this problem w.r.t. other parameters. That is, we propose a more efficient FPT algorithm for $k$-ESU, with respect to the size of the input alphabet, and propose new FPT algorithms for this problem w.r.t.~the number of states of the input automaton and the length of the input regular expression. We also discuss corresponding lower bounds. Our results significantly improve the understanding of this problem.</details>
</td>
</tr>
<tr>
<td>10:40</td>
<td>
<b>Coffee break</b>
</td>
</tr>
<tr>
<td></td>
<td><b>Morning after break session</b> (chair: Felix Buld) </td>
</tr>
<tr>
<td>11:10</td>
<td> 
Large-Scale Contextual Market Equilibrium Computation through Deep Learning<br>
<i>Yunxuan Ma</i>, Yide Bian, Hao Xu, Weitao Yang, Jingshu Zhao, Zhijian Duan, Feng Wang and <i>Xiaotie Deng</i><br>
<details><summary>Abstract</summary>
Market equilibrium is one of the most fundamental solution concepts in economics and social optimization analysis. Existing works on market equilibrium computation primarily focus on settings with relatively few buyers. Motivated by this, our paper investigates the computation of market equilibrium in scenarios with a large-scale buyer population, where buyers and goods are represented by their contexts. Building on this realistic and generalized contextual market model, we introduce MarketFCNet, a deep learning-based method for approximating market equilibrium. We start by parameterizing the allocation of each good to each buyer using a neural network, which depends solely on the context of the buyer and the good. Next, we propose an efficient method to unbiasedly estimate the loss function of the training algorithm, enabling us to optimize the network parameters through gradient. To evaluate the approximated solution, we propose a metric called Nash Gap, which quantifies the deviation of the given allocation and price pair from the market equilibrium. Experimental results indicate that MarketFCNet delivers competitive performance and significantly lower running times compared to existing methods as the market scale expands, demonstrating the potential of deep learning-based methods to accelerate the approximation of large-scale contextual market equilibrium.</details>
</td>
</tr>
<tr>
<td>11:30</td>
<td> 
Optimal Hiring Strategy in Auction-Based Crowdsourcing Systems<br>
<i>Hongtao Liu</i>, Weiran Shen and Yiheng Shen<br>
<details><summary>Abstract</summary>
We consider an auction-based crowdsourcing system. A requester is faced with a binary choice question and decides to hire workers to answer the question. The workers can ask prices for answering the question and the requester can choose to hire which workers based on their skills and ask prices. We model the problem as a mechanism design problem and characterize the optimal hiring policy. We show that the problem of computing the accuracy of a given set of workers is \#P-hard. However, we prove that choosing at most $k$ workers into committee can achieve at least $1/\lceil n/k \rceil$ of the optimal utility. Finally, we also provide a polynomial algorithm for computing the optimal hiring strategy when the number of workers' skill levels is constant.</details>
</td>
</tr>
<tr>
<td>11:50</td>
<td> 
Exact Algorithms for the Maximum $k$-Balanced Weighted Biclique Problem<br>
Jingyi Liu, Jianxin Wang, Qilong Feng and Feng Shi<br>
<details><summary>Abstract</summary>
The Maximum $k$-Balanced Weighted Biclique problem looks for a biclique in the given vertex-weighted bipartite graph such that the weight of the biclique is maximized, and the gap between the weights of the two independent vertex sets of the biclique is at most the given value $k$. Within the paper, we propose an exact algorithm for the problem with a new perspective: feedback vertex set. Specifically, our approach begins by conducting branch operations on the vertices with large degree and the ones in the feedback vertex set of the considered bipartite graph $G$, then calls a polynomial-time algorithm proposed for a related problem to each resulting graph that is acyclic. Our algorithm is shown to have time complexity $O(\min\{1.325^n, 2^{2\delta(G)}\} n^4 W^4_{max})$, where $n$ and $W_{max}$ are the number and maximum weight of the vertices in $G$, respectively, and $\delta(G)$ is the minimum cardinality (i.e., number of vertices) of a feedback vertex set for $G$. Furthermore, our algorithm can be adapted to solve the Maximum Balanced Biclique problem (i.e., $k=0$ and $G$ is unweighted) with time complexity $O(\min\{1.325^n, 2^{2\delta(G)}\} n^2\log^6 n)$, which is better than the best-known time complexity $O(1.3803^n n^2)$, especially if $G$ satisfies $\delta(G) \le n/5$.</details>
</td>
</tr>
<tr>
<td>12:10</td>
<td> 
Domination in Diameter-Two Graphs and the 2-Club Cluster Vertex Deletion Parameter<br>
Faisal Abu-Khzam and <i>Lucas Isenmann</i><br>
<details><summary>Abstract</summary>
The $s$-club cluster vertex deletion number of a graph, or sccvd, is the minimum number of vertices whose deletion results in a disjoint union of $s$-clubs, or graphs whose diameter is bounded above by $s$. We launch a study of several domination problems on diameter-two graphs, or 2-clubs, and study their parameterized complexity with respect to the 2ccvd number as main parameter. We further propose to explore the class of problems that become solvable in sub-exponential time when the running time is independent of some input parameter. Hardness of problems for this class depends on the Exponential-Time Hypothesis. We give examples of problems that are in the proposed class and problems that are hard for it.</details>
</td>
</tr>
<tr>
<td>12:30</td>
<td>
<b>Lunch break</b>
</td>
</tr>
<tr>
<td></td>
<td> 
<b>Forum 3. Young Researcher Forum</b> (chair: Yurong Chen)<br>
</td>
</tr>
<tr>
<td>14:00</td>
<td> 
<b>Forum 3-1.</b> Breaking the Sorting Barrier for Directed Single-Source Shortest Paths<br> 
<i>Xinkai Shu</i><br>
<details><summary>Abstract</summary>
We give a deterministic $O(m \log^{2/3} n)$-time algorithm for single-source shortest paths (SSSP) on directed graphs with real non-negative edge weights in comparison-addition model. This is the first result to break the $O(m + n \log n)$ time bound of Dijkstra algorithm on sparse graphs, showing that Dijkstra's algorithm is not optimal for SSSP.<br><br>
 
Biography: Xinkai Shu is a postdoctoral researcher at Max Planck Institute for Informatics. He obtained his PhD in Computer Science at The University of Hong Kong, supervised by Prof. Zhiyi Huang. Before that he obtained his bachelor's degree from Yao Class, Tsinghua University. His research interest is online algorithms, algorithmic game theory and fundamental graph algorithms.
</details>
</td>
</tr>
<tr>
<td>14:30</td>
<td> 
<b>Forum 3-2.</b> Can You Link Up With Treewidth?<br> 
<i>Jiaheng Wang</i><br>
<details><summary>Abstract</summary>
In a fundamental paper in parameterized complexity theory, Marx constructed k-vertex graphs H of maximum degree 3 such that n^o(k/log k) time algorithms for detecting colorful H-subgraphs would refute the Exponential-Time Hypothesis (ETH). This result is widely used to obtain almost-tight conditional lower bounds for parameterized problems under ETH.

We give a new, fully self-contained and elementary proof of this result avoiding arguments involving expander graphs, which were required in previous papers. In our proof, we introduce a novel graph parameter of independent interest, the linkage capacity, and then use a simple construction of communication networks credited to Beneš to obtain such hard patterns.

Our technique only requires elementary divide-and-conquer arguments that feature in first-year undergraduate introduction courses to discrete mathematics and computer science.

This paper has appeared at STACS'25. Joint work with Radu Curticapean (Regensburg, ITU Copenhagen), Simon Döring (Saarland, MPI) and Daniel Neuen (MPI). 
<br><br>
Biography: Jiaheng Wang is currently a postdoctoral researcher at the University of Regensburg. He worked as a postdoctoral research associate at the University of Edinburgh from 2023 to 2024. Prior to this, he obtained his PhD degree in 2023 from the University of Edinburgh, supervised by Dr. Heng Guo. Even earlier, he obtained his BSc degree (summa cum laude) in 2020 from Peking University as a member of the Turing Class. His research interest lies in multiple topics in theoretical computer science, with a focus on algorithms and complexity for counting problems. 
</details>
</td>
</tr>
<tr>
<td>15:00</td>
<td> 
<b>Forum 3-3.</b> Universal Online Contention Resolution with Preselected Order<br> 
<i>Junyao Zhao</i><br>
<details><summary>Abstract</summary>
Online contention resolution scheme (OCRS) is a powerful technique for online decision making, which given a matroid and a prior distribution of active elements, selects a subset of active elements that satisfies the matroid constraint in an online fashion. OCRS has been studied mostly for product distributions of active elements in the literature. Recently, universal OCRS, that works even for correlated distributions, has gained interest, because it naturally generalizes the classic notion, and its existence in the random-order arrival model turns out to be equivalent to the matroid secretary conjecture. However, currently very little is known about how to design universal OCRSs for any arrival model. In this work, we consider a natural and relatively flexible arrival model, where the OCRS is allowed to preselect (i.e., non-adaptively select) the arrival order of the elements, and within this model, we design simple and optimal universal OCRSs that are computationally efficient. In the course of deriving our OCRSs, we also discover an efficient reduction from universal online contention resolution to the matroid secretary problem for any arrival model, answering a question posed by Dughmi (2020).<br><br>

Bio: Junyao Zhao is an FSMP postdoctoral fellow at IRIF (CNRS & Université Paris Cité). Before coming to Paris, he completed his Ph.D. studies in computer science at Stanford University, where he was advised by Aviad Rubinstein. He is broadly interested in algorithmic game theory, optimization, and learning. His recent research focuses on topics including simplicity vs. efficiency in algorithmic mechanism design, beyond-worst-case analysis, and strategic robustness of online learning algorithms.</details>
</td>
</tr>
<tr>
<td>16:00</td>
<td> 
have a safe trip home
</td>
</tr> 

</table> 

                                                                                                                       

# Locations

- The conference is located in Sorbonne University, Campus Pierre et Marie Curie, 4 place Jussieu, 75005 Paris, Métro Jussieu, tower 26, floor 1, room 26-25/109
- Tuesday and Wednesday will be located in lecture hall 15
- The light reception is located in Sorbonne University, Campus les Cordeliers, 15 rue de l'École-de-médecine, 75006 Paris, Métro Odéon, room Marie-Curie. It is at walking distance from the conference site.
- The gala dinner will be in the Restaurant Macéo, 15 Rue des Petits Champs, 75001 Paris. 45 minutes walk from Jussieu. Or Métro line 7 from Jussieu to Pyramides in 22 minutes


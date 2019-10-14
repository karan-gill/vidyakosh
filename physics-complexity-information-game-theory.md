# Knowledge Theory

## Need for Knowledge Theory

*   We need a theory of information and knowledge itself.
*   How much information is out there?
*   How much info does a field contain?

## Broken Symmetry

*   [More Is Different](http://robotics.cs.tamu.edu/dshell/cs689/papers/anderson72more_is_different.pdf?fbclid=IwAR36sefOnWPBmvhivZwGl7GFSoTLvNifwldqTOdJ7moF9A60jfAPuc7TsBc) -- P. W. Anderson -- Science 1972 -- 
    *   Physics is the study of symmetry
    *   Things cannot be reduced -- properties of the whole cannot be deduced from properties of the constituents

## Limits to Knowledge

*   Another information bound is that of complexity in descriptions of the environment. As science progresses, our theories get more and more detailed. It takes longer and longer for someone to reach the cutting edge. At some point, theories will get so complex that it is simply too hard to understand and advance them anymore. We solve this problem through specialization.

# Informational Physics

## Concepts

*   Negentropy: Entropy is disorder, whether it’s the difference between a tidy and untidy room or between a solved and unsolved Rubic Cube. Negative entropy is the reduction of entropy. A system’s entropy (such as a room) always increases (the room becomes untidy, never tidy). The only way for a system to reduce its entropy is to do work (you clean your room) by expending energy (now you’re tired). But why is this concept of negative entropy important? Because it’s the best definition of life I’ve seen. Any system that reduces its entropy by doing work and transferring that entropy to the environment is alive. Hence, bacteria are alive, you are alive, and yes even society is alive. Because society maintains its order and reduces entropy.
*   Energy - The next constraint is energy. To maintain order any system needs energy to run. When a system runs out of an energy source, it cannot maintain order and disintegrates.
*   Information based
    *   “information is physical” landuaer
    *   “physics is informational” wheeler

## Reality is Information

*   Wheeler - It from Bit.
*   Rovelli - Relational Quantum Mechanics.

# Game Theory

## Information & Systems

*   Scaling laws -> multi-level selection -> info flows between agents -> game theory
*    - game theoretic consideration: after agents reach a level of self-determination, if inequality gets too high, individual redistributive pressures act
*    - information transmitted across entire system, each layer abstracts info to next layer
*    - game theoretic constraints: the interests of a free agent do not align with interests of the group. examples are ponzi schemes, parasites, sacrifice, soldiers etc., subprime mortgages.
*    - Thus society is hierarchical but when the hierarchy concentrates power into few people, then their selfish motives overpower group objectives to bring the group down. Hence any complex society must be democratic to reinforce group objectives.
*    - information constraints, every agent must understand enough to pass judgement on decisions in a democratic polity. examples are gay marriage, nuclear power, GM food, marijuana.
*    - increasing specialization is inevitable and goes against this
*    - ultimate information constraint is when it takes an entire lifetime to reach the cutting edge
*   ultimate constraint is energy ofcourse but in practice the bounding constraints are game theory and information abstraction

## Cooperation

*   Mechanisms for the evolution of cooperation: in selection, direct reciprocity, indirect reciprocity, network reciprocity and group selection. Source: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3279745/pdf/nihms49939.pdf
*   Cellular Automata & Game Theory. See parts of http://www.dhushara.com/CA/

### Price of Anarchy

*   Optimization by oracles is possible given enough information processing to arrive at correct decision: GI bill gave millions of US soldiers free education, a house, and a job.

## Incompleteness / Inefficiency

*   Price of Anarchy : http://www.cs.princeton.edu/~zdvir/apx11slides/rough-slides.pptx and https://www.cs.ubc.ca/~kevinlb/teaching/cs532l%20-%202013-14/Lectures/Price_of_Anarchy.pdf
    *   Computer networks: https://www.math.leidenuniv.nl/scripties/OlsthoornMaster.pdf

## Biology

*   Embryo/mother battle: Embryo tries to extract as many nutrients as possible while mother must keep nutrients for future kids. Hence, the placenta.
*   Slime molds -- This happens because the nuclei in the 'plasmodium' form are the products of many pairwise fusions between amoeboid haploid individuals. When genetically divergent nuclei come together in the plasmodium form, cheaters have been shown to emerge. However, genetic homogeneity among fusing amoeboid serves to maintain the multicellular plasmodium.

## Multi-level selection

*   Negentropic systems (negentropy as just discussed above) we notice that they are made up of negentropic components which may be made up of negentropic components. So society is made of organizations which are made of people which are made of cells which are made of subcellular structures which are encoded by genes. This is a hierarchy of negentropic systems. We have hierarchies of negentropic components governed by game theory mediated by information flows between them. Each negentropic system, at every level of hierarchy, has its model of the world and some information available to it.

## Phase Transitions

*   Slime molds, locusts, human mobs all form when individuals are threatened and collective action provides a clearly beneficial, optimal solution.

# ML and Evolution

## Dropout and Ev

Paper: http://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf 

One possible explanation for the superiority of sexual reproduction is that, over the long term, the criterion for natural selection may not be individual fitness but rather mix-ability of genes. The ability of a set of genes to be able to work well with another random set of genes makes them more robust. Since a gene cannot rely on a large set of partners to be present at all times, it must learn to do something useful on its own or in collaboration with a small number of other genes. According to this theory, the role of sexual reproduction is not just to allow useful new genes to spread throughout the population, but also to facilitate this process by reducing complex co-adaptations that would reduce the chance of a new gene improving the fitness of an individual. Similarly, each hidden unit in a neural network trained with dropout must learn to work with a randomly chosen sample of other units. This should make each hidden unit more robust and drive it towards creating useful features on its own without relying on other hidden units to correct its mistakes. However, the hidden units within a layer will still learn to do different things from each other. One might imagine that the net would become robust against dropout by making many copies of each hidden unit, but this is a poor solution

## MWUA and evo

Source: Papadimitriou - Algorithms, complexity, and the sciences

the equations of population genetic dynamics are mathematically equivalent to positing that each locus selects a probability distribution on alleles according to a particular rule which, in the context of the theory of algorithms, game theory, and machine learning, is known as the multiplicative weight updates algorithm (MWUA). MWUA is known in computer science as a simple but surprisingly powerful algorithm (see ref. 5 for a survey). Moreover, there is a dual view of this algorithm: each locus may be seen as selecting its new allele distribution at each generation so as to maximize a certain convex combination of (i) cumulative expected fitness and (ii) the entropy of its distribution on alleles. This connection between evolution, game theory, and algorithms seems to us rife with productive insights; for example, the dual view just mentioned sheds new light on the maintenance of diversity in evolution

# Complexity

## Principles

*   all systems get more complex over time
    *   impossible to roll back complexity
    *   thus, complexity gets too much at some point
    *   system must restart from scratch (revolution in society)
    *   OR system must add an hierarchy (neocortex + mammlian+ limbic in humans) or (religions and people in society)
        *   Hierarchies add complexities of information flow
        *   autonomy of agents increases at every level of hierarchy -- from cell to human to priest to king
    *   ultimately systems try to capture all possible information about an environment
    *   all systems are nonlinear and scale imperfectly

## Complexity from Simple Interactions

*   Caltech researchers have shown experimentally how a simple [network](https://phys.org/tags/network/) of identical synchronized nanomachines can give rise to out-of-sync, complex states.
    *   https://phys.org/news/2019-03-physicists-surprisingly-complex-states-emerging.html#jCp
*   Climate is extremely complex. An example is the explanation for polynyas [ref](https://www.livescience.com/65693-mysterious-antarctic-ice-holes-explained.html). Stronger winds and subsequent upwelling of water -> more saline ocean surface water -> made mixing easier -> major storms mixed ocean waters more easily -> water subsurface water upwelled to melt [ref](https://www.livescience.com/65693-mysterious-antarctic-ice-holes-explained.html)
*   Accidental satellite collision can lead to avalanche action: 2019-09-04 “A European satellite dodged one belonging to SpaceX over the Pacific Ocean on Monday morning, hopping around the other spacecraft after a communication glitch left SpaceX unresponsive to follow-up messages.”

### Feedback Loops

* Systems are closed or open.
* For stability, systems need feedback.
  * The Hygiene Hypothesis.
  * Backpropagation in machine learning.

## Scaling Laws

*   Scaling laws dictate airplane evolution: Constructal law has also dictated the main design features needed for aircraft to succeed; the engine mass has remained proportional to the body size, the wing size has been tied to the fuselage length, and the fuel load has grown in step with the total weight. "The same design features can be seen in any large land animal," said Bejan. "Larger animals have longer lifespans and travel farther distances, just as passenger airplanes have been designed to do. For example, the ratio of the engine to aircraft size is analogous to the ratio of a large animal's total body size to its heart, lungs and muscles." "The Evolution of Airplanes," is authored by A. Bejan, J.D. Charles and S. Lorente. https://phys.org/news/2014-07-law-physics-airplane-evolution.html 

## Evolution of Complexity

### Societes Compete Through Random Generation and Amplification

*   Genetics: A species constantly generates individually with random traits and then amplifies the traits that survive.
*   Memetics: A society constantly generates random ideas and amplifies the ideas that survive.

### Entities Compete and Inherit

*   Musical instruments inherit and are selected through ease of use, musical pleasure, and aesthestic value in performance.
*   Software libraries  inherits practices from each other and compete with each other.

### Inevitable complexity increase due to Path Dependence leads to inevitable ultimately Failing

*   Boeing aircraft kept in service for decades by weird modifications starts failing in a complex way: https://www.latimes.com/local/california/la-fi-boeing-max-design-20190315-story.html 
    *   folding metal stairs attached to the fuselage that passengers climbed to board before airports had jetways. Ground crews hand-lifted heavy luggage into the cargo holds in those days, long before motorized belt loaders were widely available.
    *   That low-to-the-ground design was a plus in 1968, but it has proved to be a constraint that engineers modernizing the 737 have had to work around ever since. The compromises required to push forward a more fuel-efficient version of the plane — with larger engines and altered aerodynamics — led to the complex flight control software system that is now under investigation in two fatal crashes over the last five months.
    *   Boeing has had a good record modernizing the 737. But he said, “They may have pushed it too far.”
    *   To handle a longer fuselage and more passengers, Boeing added larger, more powerful engines, but that required it to reposition them to maintain ground clearance. As a result, the 737 can pitch up under certain circumstances. Software, known as the Maneuvering Characteristics Augmentation System, was added to counteract that tendency.It was that software that is believed to have been involved in a Lion Air crash in Indonesia in October.
        *   In the 737-300, which came after the original planes sold in West Germany, Boeing came up with an unusual fix: It created a flat bottom on the nacelle (the shroud around the fan), creating what pilots came to call the “hamster pouch.”
        *   “They made it work,” said Ditchey, whose America West was one of the original customers of the 737-300.
        *   But the LEAP engines required an even bigger change. Boeing redesigned the pylons, the structure that holds the engine to the wing, extending them farther forward and higher up. It gave the needed 17 inches of clearance. The company also put in a higher nose landing gear.
        *   The change, however, affected the plane’s aerodynamics. Boeing discovered the new position of the engines increased the lift of the aircraft, creating a tendency for the nose to pitch up.
        *   The solution was MCAS, which ordered the stabilizer to push down the nose if the “angle of attack” — or angle that air flows over the wings — got too high. The MCAS depends on data from two sensors.
    *   The software erroneously thought the aircraft was at risk of losing lift and stalling — because of a malfunctioning sensor — and ordered the stabilizer at the rear to put it into a series of sharp dives that ultimately caused the plane to crash into the Java Sea.
*   Revolutions in societies

## Systems of Complex Agents (like Society)

*   Trade-off between centralized power that can globally optimize and distributed power that prevents exploitation of power centers.
*   A democracy implies that every agent in the system must weigh in on the final decision. This raises the question of information flows. For anti-tobacco legislation to become a priority, a majority of voters must understand the issue and its importance. This is why it took decades to pass anti-smoking laws. Because information had to flow from research to the general public. Similarly so for passing laws on global warming, immigration or any other issue. For them to pass, they must occupy public consciousness. In order to do so, people must access and understand information. Thus, a democracy ensures that progress is limited by how fast information can flow and be understood. This is the “information bound”. So game theory leads to democracy, and democracy leads to an information bound. Ultimately, when information becomes too complex, progress will grind to a halt. Systems try to solve this problem using small world networks.

## Examples

*   See Economics doc for economic complexity.

# Computation

## Abstracting real-world

*   The Matrix
*   Wired: Mirror world concept where things exist in cyberspace
*   Eve Online
    *   Battle of b-r5rb

## Real & Cyber Interactions

*   Incel community was founded as a positive support community but evolved into a angry, hate group. The original founder passed on the group, and had no idea what happened to it. She was aghast.
*   sotkc market flash crash
*   stuxnet
*   flash mobs
*   anonymous

## Game Theory of the Internet

*   internet defends itself, is alive - sopa example

## Simulations

*   In a description, returns do not scale with description complexity. You have to make your description more and more complex to improve your description. Ultimately, you realize you need a simulation from first principles. Ex. using bisection to iteratively find a root.

## Incompleteness Theorems

*   Incompleteness theorem has different manifestations in different fields.
    *   Price of anarchy
    *   Uncertainty principle
    *   Halting problem

# Network Theory

*   Slime molds replicate highway networks: Transport networks are ubiquitous in both social and biological systems. Robust network performance involves a complex trade-off involving cost, transport efficiency, and fault tolerance. Biological networks have been honed by many cycles of evolutionary selection pressure and are likely to yield reasonable solutions to such combinatorial optimization problems. Furthermore, they develop without centralized control and may represent a readily scalable solution for growing networks in general. In the picture shown below, researchers have carefully placed oat flakes in the pattern of Japanese cities around Tokyo. The slime mold Physarum polycephalum was introduced, eventually connecting the flakes with an efficient network to distribute nutrients throughout the single celled organism.
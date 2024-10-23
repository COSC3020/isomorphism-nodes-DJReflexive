# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

# My Proof

Consider an example where graph A is larger than graph B.

A requirement for isomorphism is that there must exist a bijection from A to B. Since A is larger, A to B cannot be one-to-one, and therefore there is no bijection. This means it is impossible for A and B to be isomorphic.

The inverse is also true, where B is larger than A. The difference being that instead of the relationship missing the one-to-one property, it is missing the onto property. This also leads to no bijection, and it is still impossible for A and B to be isomorphic.

# Sources

- TA Ali: For reviewing my assignment and making sure things looked good - he suggested no changes for any of this.

# Plagiarism Acknowledgement

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
## OVERVIEW

Causal inference provides a set of tools and principles that allows one to combine data and substantive knowledge about the environment to reason with questions of counterfactual nature -- i.e., what would have happened had reality been different, even when no data about this unrealized reality is available. Reinforcement Learning is concerned with finding a policy that optimizes a specific function (e.g., reward, regret) in interactive and uncertain environments. These two disciplines have evolved independently and with virtually no interaction between them. In fact, they operate over different aspects of the same building block, i.e., counterfactual relations, which makes them umbilically tied.
In this tutorial, we introduce a unified treatment putting these two disciplines under the same theoretical umbrella. We then show that a number of natural and pervasive classes of learning problems emerge when this connection is fully established (which cannot be seen individually from either discipline). This new understanding leads to a broader view of what counterfactual learning is and suggests the great potential for the study of causality and reinforcement learning side by side, which we name causal reinforcement learning (CRL, for short).

### GOALS

The goals of the tutorial are (1) to introduce the modern theory of causal inference, (2) to connect reinforcement learning and causal inference (CI), introducing causal reinforcement learning, and (3) show a collection of pervasive, practical problems that can only be solved one the connection between RL and CI is established. The implications in decision-making and explainability are direct, so we feel that the tutorial should be compelling for large part of the community.


### TARGET AUDIENCE

This tutorial is targeted at researchers working on the foundations of learning, intelligence, and decision-making as well as in applied areas, including robotics and reinforcement learning researchers. After the tutorial, attendees should be familiar with the basic concepts, principles, and algorithms to solve modern problems involving causal reinforcement learning. In particular, they should develop a basic understanding of the differences between typical (a-causal) reinforcement tools and the new generation of causal reinforcement learning machinery. The desired knowledge is basic (undergraduate level) knowledge of reinforcement learning and graphical models.


## OUTLINE

<table>
  <tr>
    <td>Part</td>
    <td>Subject</td>
    <td>Material</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Foundations of Causal Inference</td>
    <td>
      <ul>
        <li>Review of Graphical Models</li>
        <li>Structural Causal Models (vs
Bayes nets, Deep nets, Decision
trees)</li>
        <li>Pearl’s 3-layer scientific hierarchy</li>
      </ul>
  </td>
  </tr>
  <tr>
    <td colspan="3">This module introduces some basic results in causal inference and the 3-layer inferential hierarchy proposed by Pearl and collaborators. This formalism allows us to have a more general view of the scope of ML, and induces a new classes of problems, more aligned with how causal inference is used in the sciences.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Causal Reinforcement Learning</td>
    <td>
      <ul>
        <li>Relationship between Causality and RL.</li>
        <li>Individual-level decision-making</li>
        <li>When is Human needed in the loop: A causal approach</li>
        <li>Generalized off-policy learning</li>
        <li>Counterfactual data-fusion</li>
      </ul>
  </td>
</tr>
  <tr>
    <td colspan="3">In this module, we discuss some of the fundamental connections between these fields, and explain how RL can be made more robust and general through causal machinery. we discuss the problems or generalized off-policy learning, where interventions should be performed, counterfactual randomization, and data- fusion. Overall, we show how counterfactual reasoning can be embedded in RL systems to make decision-making more personalized, efficient, and robust.
    </td>
  </tr>
</table>


## References

-  **Structural Causal Bandits with Non-manipulable Variables** S. Lee, E. Bareinboim AAAI-19. In Proceedings of the 33rd AAAI Conference on Artificial Intelligence, 2019. 
- **Counterfactual Randomization: Rescuing Experimental Studies from Obscured Confounding**
A. Forney, E. Bareinboim.
AAAI-19. In Proceedings of the 33rd AAAI Conference on Artificial Intelligence, 2019. 
- **Structural Causal Bandits: Where to Intervene?**
S. Lee, E. Bareinboim 
NeurIPS-18. In Proceedings of the 32nd Annual Conference on Neural Information Processing Systems, 2018. 
- **Counterfactual Data-Fusion for Online Reinforcement Learners**
A. Forney, J. Pearl, E. Bareinboim. 
ICML-17. In Proceedings of the 34th International Conference on Machine Learning, 2017. 
- **Transfer Learning in Multi-Armed Bandits: A Causal Approach**
J. Zhang, E. Bareinboim. 
IJCAI-17. In Proceedings of the 26th International Joint Conference on Artificial Intelligence, 2017. 
- **Bandits with Unobserved Confounders: A Causal Approach**
E. Bareinboim, A. Forney, J. Pearl. 
NeurIPS-15. In Proceedings of the 28th Annual Conference on Neural Information Processing Systems, 2015.


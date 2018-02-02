# capflow
Isabelle proof for CapFlow 

CapFlow is a capability-based information flow control model. Formal specifications and verifications are provided by this repo.

- [Dynamic_model](http://htmlpreview.github.io/?https://github.com/capflow/capflow/blob/master/Dynamic_model.html): An abstract security model with dynamic information flow policies. Information flow security properties are defined in this model. This file contains dynamic unwinding conditions, dynamic noninterference theory and an inference framework.
- [CapFlow](http://htmlpreview.github.io/?https://github.com/capflow/capflow/blob/master/Capflow.html): A concrete execution model based-on capability. This model is instantiated from Dynamic_model and inherites the security properties of the abstract model. This file specifies kernel events and provides formal security proofs of CapFlow.
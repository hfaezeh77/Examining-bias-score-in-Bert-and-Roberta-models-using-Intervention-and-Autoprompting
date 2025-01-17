# Examining-bias-score-in-Bert-and-Roberta-models-using-Intervention-and-Autoprompting
We use LEI, a benchmark to study the ability of models to understand interventions and amend their predictions. For example, consider the question in Fig. 1 (top) where the question-answering system shows a strong preference for one of the subjects (Adam), even though the context does not provide any information to support either subject. We then add bias-mitigating ethical interventions, as shown in Fig. 1 (middle). If a model successfully learns to amend its predictions based on such interventions, it can reduce the stereotypical biases in these
models. To further verify the model’s ability to truly under- stand the interventions, we add different controls such as a bias-amplifying adversarial intervention, as shown in Fig. 1 (bottom), where the model is expected to behave in a biased manner. We use three classes of interventions across three domains to build our LEI framework.

<p align="center">
  <img src="Fig 1.png" width="500"/>
</p>


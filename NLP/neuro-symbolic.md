# NLP - Neuro-Symbolic Hybrids
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Neural Datalog Through Time: Informed Temporal Modeling via Logical Specification](http://proceedings.mlr.press/v119/mei20a/mei20a.pdf)|Paper|ICML|Used a temporal deductive database to track structured facts over time|
|[Neural Finite State Transducers: Beyond Rational Relations](https://aclanthology.org/N19-1024.pdf)|Paper|NAACL|Allow the arcs’ scores to depend on their context in the path of FST with RNN.|
|[Weighting Finite-State Transductions With Neural Context](https://aclanthology.org/N16-1076.pdf)|Paper|NAACL| Use a stacked LSTM for transducer and experimented on reinflection and lemmatization. Arc weight comes from inner product of embedding char focuses and embedding of other properties (types, history)
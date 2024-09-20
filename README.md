# EPplus
Verified Performance-Optimal Causally Consistent Database Transactions

## Improving isolation guarantees and performance evaluation
Our Eiger-PORT+ protocol improves the upper bound of isolation guarantees achievable by performance-optimal read-only transactions in the presence of transactional writes from the previously conjectured TCC (Transactional Causal Consistency) to TCCv (TCC with convergence). Additionally, Eiger-PORT+ outperforms the state-of-the-art. Evaluation results are available under the [eiger-port-plus_evaluation](https://github.com/lucamul/EIGER-PORT-PLUS) submodule.

## Usage
- To compile the Isabelle theories, install the latest version of Isabelle/HOL at https://isabelle.in.tum.de/index.html.
- Modeling and Verification of our novel Eiger_PORT+ protocol can be found in [EP+.thy](VerIso/EP+.thy) and [EP+_Proof.thy](VerIso/EP+_Proof.thy). To directly access the reduction and refinement proofs, run [EP+_Reduction.thy](VerIso/EP+_Reduction.thy) and [EP+_Refinement_Proof.thy](VerIso/EP+_Refinement_Proof.thy) theories respectively.
- To see the progress on loading theories check Isabelle's "Theories" panel.
- To inspect the proof state, please make sure "Proof state" box is checked in Isabelle's "Output" tab.
  * To only see the lemmas or theorems statement, place the cursor on them and look at Isabelle's Output tab.
  * To see the lemma statement and proof in the original theory where it is proven, Ctrl + Click on its name. (Cmd + Click for mac users)

## Authors
- Shabnam Ghasemirad

- Dr. Christoph Sprenger

- Dr. Si Liu

- Luca Multazzu

- Prof. David Basin

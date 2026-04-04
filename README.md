# QPerceptron

This is a personal project to explore the implementation of a **perceptron** in both classical and quantum settings. It started after reading Turing's classic paper:

Turing, A. M. (1950). *Computing machinery and intelligence*. *Mind*, 59(236), 433–460. [DOI link](https://doi.org/10.1093/mind/LIX.236.433)

Turing suggested that a discrete classical machine cannot fully simulate a brain. This led me to think about how one of the simplest machine learning models, the **perceptron**, could be implemented in a quantum computer using Qiskit.
> [!WARNING]
> The file: [notes](https://github.com/szacnd/qperceptron/blob/main/notes.pdf) is a cleaned-up version of my writing (draft notes), prepared with the help of ChatGPT to give it a more "academic" tone. Each question, afirmation, equation, proposition, lemma, and corollary presented is based on my own interpretation of the references (below) and should not be treated (unless you wish to spend time examining it) as a formally validated paper. If, by any chance, you find a mistake or incorrect information, please email me—I would be very grateful for the opportunity to update my code, notes, and, of course, to learn more.

>[!NOTE]
> This project emerged from a preliminary and exploratory study process, involving independent reading of the literature and personal reflection on the subject. Through this experience, I developed a strong interest in further pursuing topics at the intersection of **quantum computing**, **optimization**, and **machine learning**.
>
> The repository should therefore be understood as an *archival record* of this learning process. Unless explicitly stated, its contents are not intended to be continuously revised or maintained, but rather preserved as a reference point for this stage of study.
>
> Readers interested in these topics are strongly encouraged to consult the references listed below and to independently explore and develop their own ideas. As noted above, the accompanying notes reflect personal interpretations and have not undergone formal validation; constructive feedback is always welcome.

---

## Purpose

- Understand how a classical perceptron works from scratch.
- Explore quantum perceptron models [6] and their linear algebra structure.
- Compare classical vs quantum perceptron outputs.
- Investigate, for myself, under what circumstances quantum perceptrons differ or coincide with classical ones.

This project is a **personal learning journey**, not intended as a guide for others.

---

## Landmarks

- Implement a **classical perceptron** from scratch.
- Implement a **quantum perceptron** using Qiskit.
- Compare results and explore why quantum and classical perceptrons may produce similar outcomes.

---

## References

[1] F. Rosenblatt, *The perceptron: A probabilistic model for information storage and organization in the brain*, Psych. Rev., 65(6):386–408, 1958.  
[2] J. Biamonte et al., *Quantum machine learning*, Nature, 549(7671):195–202, 2017.  
[3] M. Schuld et al., *An introduction to quantum machine learning*, Contemp. Phys., 56(2):172–185, 2015.  
[4] M. Cerezo et al., *Variational quantum algorithms*, Nat. Rev. Phys., 3:625–644, 2021.  
[5] M. Nielsen & I. Chuang, *Quantum Computation and Quantum Information*, 2010.  
[6] N. Wiebe et al., *Quantum perceptron models*, arXiv:1602.04799, 2016.  
[7] M. Schuld & N. Killoran, *Quantum machine learning in feature Hilbert spaces*, PRL, 122(4):040504, 2019.  
[8] V. Havlíček et al., *Supervised learning with quantum-enhanced feature spaces*, Nature, 567:209–212, 2019.  
[9] M. Schuld et al., *Circuit-centric quantum classifiers*, PRA, 101(3):032308, 2020.  
[10] M. P. Cuéllar, *What we can do with one qubit in quantum machine learning*, Quantum Mach. Intel., 6:76, 2024.  
[11] I. V. Grossu, *Single qubit neural quantum circuit for solving exclusive-or*, MethodsX, 8:101573, 2021.

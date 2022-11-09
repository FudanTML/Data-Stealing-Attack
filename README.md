# Data_Stealing_Attack

### Problem Statement

Data stealing attacks or data extraction attacks aim to derive and infer (parts of) the training data from a trained network. Deep neural networks are thriving in a variety of fields. Computer vision, without a doubt, is one of the most important areas receiving great attention from academic and industrial society. In this project, you are encouraged to steal training data from well-trained computer vision networks.

### Project Goals 

- **Data stealing attack:** In this task, you are asked to come up with your method to attack a trained network and propose a way to evaluate your work.

- **Identification of the holdouts:** To this day, attackers cannot reconstruct all the training data pixel-by-pixel. After you propose your data stealing attacks, you may have your theory of why data stealing attacks work on DNN classifiers. To help with understanding what neural networks memorized during training, the identification of images that are hard to steal is due. In this task, you are required to identify images or one class from CIFAR-10 that are least likely to be reconstructed (by your method or any method available online) and share your mathematical proofs or explanations in this matter.

`Code:` You may follow the following or any other materials you find online as an example
- [DLG [1]](https://github.com/mit-han-lab/dlg)
- [InvGrad [2]](https://github.com/JonasGeiping/invertinggradients)

### Recommended Readings

[i] Carlini N, Liu C, Erlingsson Ú, et al. The secret sharer: Evaluating and testing unintended memorization in neural networks. USENIX Security 19\
[ii] Yin H, Molchanov P, Alvarez J M, et al. Dreaming to distill: Data-free knowledge transfer via deepinversion. CVPR 2020\
[iii] Haim N, Vardi G, Yehudai G, et al. Reconstructing training data from trained neural networks. arXiv:2206.07758 2022.\

### Reference 

[1]Zhu L, Liu Z, Han S. Deep leakage from gradients. NeurIPS 2019\
[2]Geiping J, Bauermeister H, Dröge H, et al. Inverting gradients-how easy is it to break privacy in federated learning? NeurIPS 2020\

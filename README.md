# AML_Project5 - Distributed Learning

This project explores the performance of various optimizers—SGDM, LARS, LAMB, and LocalSGD—in both centralized and distributed training settings. Using a modified LeNet-5 architecture on the CIFAR-100 dataset, we evaluate how optimizer choice and batch size impact training accuracy, convergence, and scalability.

The corresponding report can be found [here](./s335057_s323502_project5.pdf). 

The SGDM code and centralized benchmarks can be found in the [Centralized directory](./Centralized).   
The code and results for the large batch optimizers LARS and LAMB can be found in the [LargeBatch Directory](./LargeBatch).   
The code and results for the localSGD can be found in [LocalSGD](./LocalSGD).

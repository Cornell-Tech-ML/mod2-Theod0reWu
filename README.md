[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

## Simple Dataset
Datapoints: 50 <br>
Settings:
* 2 hidden layers
* .05 Learning Rate
* 500 epochs
  
Result:
* 50/50 correct
* Time per epoch: 0.060 seconds
  
![image](https://github.com/user-attachments/assets/9d542fa3-8248-4eb9-bda1-124ccd95eba7)

## Diag Dataset
Datapoints: 75 <br>
Settings:
* 2 hidden layers
* .1 Learning Rate
* 500 epochs
  
Result:
* 75/75 correct
* Time per epoch: 0.086 seconds

![image](https://github.com/user-attachments/assets/fe4805e8-88d5-4e6d-ade9-149d5a578a22)

## Split Dataset
Datapoints: 50 <br>
Settings:
* 12 hidden layers
* 0.1 Learning Rate
* 500 epochs
  
Result:
* 49/50 correct
* Time per epoch: .6 seconds

![image](https://github.com/user-attachments/assets/82c6a635-33bb-43ec-ac70-9103d0dc6fa9)

## XOR Dataset
Datapoints: 50 
Settings:
* 16 hidden layers
* 0.1 Learning Rate
* 500 epochs
  
Result:
* 48/50 correct
* Time per epoch: .978 seconds
![image](https://github.com/user-attachments/assets/055e6953-749d-4e72-a145-116194f4ed0f)




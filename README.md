1. train-steps=1000
```
Completion time of the training task: 
    real    37m1.290s
    user    133m29.996s
    sys     6m28.572s
Average examples per second during training
    59.0316 (62.0026)
Final accuracy of evaluation
    0.4859
Loss of the model: 
    1.1060545
```

2. train-steps=2000
```
Completion time of the training task: 
    real    37m10.331s
    user    133m47.632s
    sys     6m47.940s
Average examples per second during training
    58.7608 (62.0397)
Final accuracy of evaluation
    0.5591
Loss of the model: 
    0.83666766
```

3. train-steps=1000, checkpoint-num-steps=500
The checkpoints stil occurs in step 280 560 840 1000. It does not works to change checkpoint-num-steps. Thus the results should be the same as question 1.
It can be observe that it will take some time to save the checkpoint and continue to the next steps. So the more frequent the checkpoints the more time should be taken for the training run. 

5.

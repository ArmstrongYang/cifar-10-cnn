Result of ResNet-50 (we run it 5 times and show “best” as in the following table)  
see [HTD](https://github.com/BIGBALLON/HTD) for more details if you are interested.

| Network               | Methods    | runs            | **CIFAR-10**  | **CIFAR-100** |
|:----------------------|:----------:|:---------------:|:-------------:|:-------------:|
| ResNet-50             |step decay  |  med. of 5 runs | 93.09%        | 70.25%        |
| ResNet-50             |cos         |  med. of 5 runs | 93.42%        | 70.07%        |
| ResNet-50             |HTD         |  med. of 5 runs | **93.58%**    | **70.81%**    |

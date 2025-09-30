# Intel CPU-based instances
#### Custom Intel Xeon 1 processors(Skylake)
#### Custom Intel Xeon 2 processors(Cascade Lake)

| EC2 Gen5 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| M5/R5/R5b/i3en/D3/D3en/Vt1/T3 instances | 8175M/8259CL | 3.1GHz|
| C5/hpc5i instances| 8175M | 3.4GHz|
| P4 instances|  P-8275CL | 3.0GHz|
| Z1d  instances|8151 | 4.0GHz |
| M5zn/X2iezn instances|8252c| 4.5GHz |
| U1-1 instances| 8176M/8280L| 2.1GHz/2.7Ghz |


#### Custom Intel Xeon 3 processors（Icelake）
| EC2 Gen6 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| M6i/C6i/R6i/d/n/hpc6id/i4i/X2idn/X2iedn instances| 8375c | 3.5GHz|


#### Custom Intel Xeon 4 processors（Sapphire Rapids)
| EC2 Gen7 instance types | CPU | All core turbo frequency |
|-------------------------|-----|--------------------------|
| C/M/R 7i-flex/C/M/R 7i/p5en instances | 8488C | 3.2GHz |
| r7iz instances | 6455B | 3.9GHz |
| u7i instances | 84xxH | 2.9GHz |

<small>* u7i refers to the HPE3200</small>



#### Custom Intel Xeon 5 processors（Emerald Rapids)
| EC2 Gen7 instance types| CPU | All core turbo  frequency|
|---------|---------|---------|
| I7ie/p6 Instances | 8559C | 3.2GHz|


#### Custom Intel Xeon 6 processors(Granite Rapids)
| EC2 Gen8 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| R/M8i/R/M8i-flex instances| 6975P-C| 3.9GHz|

# AMD CPU-based instances
#### Custom AMD EYPC Zen1 processors(Naples)
| EC2 Gen5 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| M5a/R5a/T3a instances| 7571| 2.5GHz|

#### Custom AMD EYPC Zen2 processors(Rome)
| EC2 Gen5 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| C5a/hpc5a/G4ad/G5 instances| 7R32| 3.3GHz|

#### Custom AMD EYPC Zen3 processors(Milan)
| EC2 Gen6 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| C6a/M6a/R6a/HPC6a/G6/G6e/p5/p5e instances| 7R13| 3.6GHz|


#### Custom AMD EYPC Zen4 processors(Genoa)
| EC2 Gen7 instance types| CPU | All core turbo frequency|
|---------|---------|---------|
| C7a/M7a/R7a/hpc7a instances| 9R14| 3.7GHz|

# Graviton&ARM CPU-based instances
| EC2 instance types| CPU | frequency|
|---------|---------|---------|
| A1 Instances | AWS Graviton1 | 2.3GHz |
| CRM 6g/is4gen/im4gn/I4g/t4g Instances | AWS Graviton2 | 2.5GHz |
| CRM 7g Instances | AWS Graviton3 | 2.6GHz |
| c7gn,HPC7g Instances | AWS Graviton3e | 2.6GHz |
| CRM 8g/I8g Instances | AWS Graviton4 | 2.8GHz（2.7GHz for 48xlarge） |
| p6/p6e Instances | Nvidia Grace | 3.0GHz |


> **📝 Notes**
> 
> 1. New instances require compatibility with the new OS; otherwise, it may lead to performance regression.
> 2. For frequency-sensitive applications, the new-generation instances may perform worse than the older ones.  
>    (For example: 7i instance/3.2GHz vs 6i instance/3.5GHz)
> 
> For any questions, please contact me via email: **frank622@gmail.com**


# EXP.NO.5-Simulation-of-Signal-Sampling-Using-Various-Types
5.Simulation of Signal Sampling Using Various Types such as
    i) Ideal Sampling
    ii) Natural Sampling
    iii) Flat Top Sampling

# AIM
To perform Simulation of Signal Sampling Using Various Types such as
    i) Ideal Sampling
    ii) Natural Sampling
    iii) Flat Top Sampling
    
# SOFTWARE REQUIRED
Python Software 
-> Numpy Library
-> Matplotlib Library
-> Scipy Library (for signal processing)

# ALGORITHMS
IDEAL SAMPLING:

Define the input signal 
𝑥
(
𝑡
)
x(t) and sampling period 
𝑇
𝑠
T 
s
​
 .

Generate a train of impulses at intervals of 
𝑇
𝑠
T 
s
​
 .

Approximate impulses using narrow pulses or Dirac delta-like logic in code.

Multiply 
𝑥
(
𝑡
)
x(t) by the impulse train to obtain ideally sampled signal.

Plot both original and sampled signals for comparison.

NATURAL SAMPLING:

Define the input signal 
𝑥
(
𝑡
)
x(t) and sampling period 
𝑇
𝑠
T 
s
​
 .

Set pulse width 
𝜏
τ such that 
𝜏
<
𝑇
𝑠
τ<T 
s
​
 .

Generate a periodic pulse train with width 
𝜏
τ and period 
𝑇
𝑠
T 
s
​
 .

Multiply 
𝑥
(
𝑡
)
x(t) by the pulse train.

Plot and analyze the natural sampled output waveform.

FLAT TOP SAMPLING:

Define the input signal 
𝑥
(
𝑡
)
x(t) and sampling period 
𝑇
𝑠
T 
s
​
 .

Set the pulse width 
𝜏
τ such that 
𝜏
<
𝑇
𝑠
τ<T 
s
​
 .

Generate a periodic pulse train of width 
𝜏
τ.

At each sampling instant, sample the value of 
𝑥
(
𝑡
)
x(t) and hold that value constant for duration 
𝜏
τ.

Plot the original and flat top sampled signals for comparison.

# PROGRAM
IDEAL SAMPLING


![ideal sampling](https://github.com/user-attachments/assets/c6b3db33-e0c3-43b0-86e7-96b0e21ca19a)

NATURAL SAMPLING


![NATURAL SAMPLING 1](https://github.com/user-attachments/assets/19d53515-7c69-480e-8953-ed69f2a470c1)
![NATURAL SAMPLING 2](https://github.com/user-attachments/assets/0841bdff-af08-4caa-ad04-85ce38e6ab09)

FLAT TOP SAMPLING


![FLAT TOP SAMPLING](https://github.com/user-attachments/assets/c830b3af-d549-40ab-bb1c-9fdc31ee7a93)



# OUTPUT
IDEAL SAMPLING


![ideal sampling output](https://github.com/user-attachments/assets/5440d9f3-dfdb-46b4-9284-b8e5db891ed5)

NATURAL SAMPLING


![NATURAL SAMPLING OUTPUT](https://github.com/user-attachments/assets/6e99a4d4-1f87-45ab-b3d4-3a211b63829a)

FLAT TOP SAMPLING


![FLAT TOP SAMPLING OUTPUT](https://github.com/user-attachments/assets/37bf2bf2-f4a6-44cd-b5d9-e0e28e118e28)



 
# RESULT / CONCLUSIONS
The Construction or Re-construction of various types of signal sampling using python are successfully verified.

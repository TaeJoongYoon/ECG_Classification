# ECG Classification

This project is machine learning algorithm to classify/detect arrhythmia.

I use DNNClassifier in tensorflow.



### Arrhythmia Type List
- N = 'N', 'L', 'R', 'e', 'j'

- SVEB = 'A', 'a', 'J', 'S'

- VEB = 'V', 'E'

- F = 'F'

- Q = '/', 'f'

  

### Arrhythmia Annotation
- N = Normal beat

- L = Left bundle branch block beat

- R = Right bundle branch block beat

- e = Atrial escape beat

- j = Nodal (junctional) escape beat

- A = Atrial premature beat

- a = Aberrated atrial premature beat

- J = Nodal (junctional) premature beat

- S = Supraventricular premature or ectopic beat (atrial or nodal)

- V = Premature ventricular contraction

- E = Ventricular escape beat

- F = Fusion of ventricular and normal beat

- / = Paced beat

- f = Fusion of paced and normal beat

  

### The Number of Each Arrhythmia Type
- N = 10001

- L = 8075

- R = 7259

- e = 16

- j = 229

- A = 2546

- a = 150

- J = 83

- S = 2

- V = 7130

- E = 106

- F = 803

- / = 7028

- f = 982

  

 **I take types(N, L, R, A, V, /) because quantity of others are not suitable** 



### Environment

---

1. python 3.5.2
2. tensorflow-gpu 1.10.0
3. intel i7-7700K
4. GeForce GTX 1080 x 2 



### Usage

---

1. Run ***ECG_Classification.ipynb***
2. That's all

### Result

---

![Result](./README/result.png)


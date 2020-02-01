# ttodcc_errata

---

# Overview
**Unofficial** and Unfinished Errata for Christos Papadimitriou, *The Theory of Database Concurrency Control*, 1986.

![cover](https://user-images.githubusercontent.com/47991351/72767770-8119ac80-3c38-11ea-94e3-40cfc4efc4f3.jpg)

# Usage
If you find something wrong, you can search this page or Issues.

If find in Issue, you can moderate the proposed fix or propose a new fix.
If not, you can add a new issue.

For probable fix, you can create a merge request to errata.


---
# Errata

---
## Chapter 1 INTRODUCTION

## Chapter 2 CORRECTNESS

## 2.2 FINAL-STATE SERIALIZABILITY
### - p.21 Excample 2.1 argumented schedule  [#4](https://github.com/supisula/ttodcc_errata/issues/4)
->  
![image](https://user-images.githubusercontent.com/47991351/73112112-6d2fbc80-3f50-11ea-9eaa-185cbee6000f.png)


### - p.21 1st paragraph after Excample 2.1 (continued)  [#1](https://github.com/supisula/ttodcc_errata/issues/1)
"... graph-theoretic characterization of finite-state equivalence ..."  
->  
"... graph-theoretic characterization of **final**-state equivalence ..."


### - p.22 The center node of D(s), Figure 2.1  [#18](https://github.com/supisula/ttodcc_errata/issues/18)
"A_3:K(x)"  
->  
"A_3:**R**(x)"


## 2.4 VIEW SERIALIZABILITY
### - p.34 3rd line from the bottom  [#3](https://github.com/supisula/ttodcc_errata/issues/3)
![error](https://user-images.githubusercontent.com/47991351/73115390-99573780-3f68-11ea-8483-918200f1131d.png)  
->  
![correct](https://user-images.githubusercontent.com/47991351/73115402-ac6a0780-3f68-11ea-9300-4c8234c06b7e.png)



## 2.5 TTHE COMPLEXITY OF VIEW SERIALIZABILITY
### - p.36 Figure 2.4  [#5](https://github.com/supisula/ttodcc_errata/issues/5)  [#6](https://github.com/supisula/ttodcc_errata/issues/6)
->  
![Figure 2.4](https://user-images.githubusercontent.com/47991351/73111647-7750bb80-3f4e-11ea-8c23-fc22aceb7b95.png)



### - p.36 1st paragraph from the top  [#7](https://github.com/supisula/ttodcc_errata/issues/7)
![error](https://user-images.githubusercontent.com/47991351/73115474-a6c0f180-3f69-11ea-93d1-ce719daac799.png)  
->  
![correct](https://user-images.githubusercontent.com/47991351/73115479-b3454a00-3f69-11ea-8e3e-4be1143f8169.png)



## 2.6 CONFLICT SERIALIZABILITY
### p.47 3rd paragraph from the top  [#15](https://github.com/supisula/ttodcc_errata/issues/15)
"(recall Section 1.3),"  
->  
"(recall Section **1.2**),"



## Chapter 3 MORE ON CORRECTNESS
N/A

## Chapter 4 SCHEDULERS
N/A

## Chapter 5 THE PERFORMANCE OF SCHEDULERS
N/A

## Chapter 6 THE THEORY OF LOCKING
N/A

## Chapter 7 DISTRIBUTED CONCURRENCY CONTROL
N/A


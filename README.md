# ttodcc_errata

---

# Overview
**Unofficial** Errata for Christos Papadimitriou, *The Theory of Database Concurrency Control*, 1986.

![cover](https://user-images.githubusercontent.com/47991351/72767770-8119ac80-3c38-11ea-94e3-40cfc4efc4f3.jpg)

# Usage
If you find something wrong, you can search this page or Issues.

If find in Issue, you can moderate the proposed fix or propose a new fix.
If not, you can add a new issue.

For probable fix, you can create a merge request to errata.


---
# Errata

## Chapter 1 INTRODUCTION
N/A

## Chapter 2 CORRECTNESS

### 2.2 FINAL-STATE SERIALIZABILITY
#### - p.21 Excample 2.1 argumented schedule
The layout of the argumented schedule s^ is broken.  
The write step W(y) of A3 should be before W(y) of A2.

![image](https://user-images.githubusercontent.com/47991351/73112112-6d2fbc80-3f50-11ea-9eaa-185cbee6000f.png)

[#4](https://github.com/supisula/ttodcc_errata/issues/4)

#### - p.21 1st paragraph after Excample 2.1 (continued)
"... graph-theoretic characterization of finite-state equivalence ..."  
->  
"... graph-theoretic characterization of **final**-state equivalence ..."

[#1](https://github.com/supisula/ttodcc_errata/issues/1)

### 2.4 VIEW SERIALIZABILITY
#### - p.34 3rd line from the bottom
![error](https://user-images.githubusercontent.com/47991351/73115390-99573780-3f68-11ea-8483-918200f1131d.png)  
->  
![correct](https://user-images.githubusercontent.com/47991351/73115402-ac6a0780-3f68-11ea-9300-4c8234c06b7e.png)

[#3](https://github.com/supisula/ttodcc_errata/issues/3)

### 2.5 TTHE COMPLEXITY OF VIEW SERIALIZABILITY
#### - p.36 Figure 2.4
- The second Choice from the top lacks arrowheads. [#5](https://github.com/supisula/ttodcc_errata/issues/5)
- No need for left arrowhead of center arc. [#6](https://github.com/supisula/ttodcc_errata/issues/6)

![Figure 2.4](https://user-images.githubusercontent.com/47991351/73111647-7750bb80-3f4e-11ea-8c23-fc22aceb7b95.png)

#### - p.36 1st paragraph from the top
"We say that *D* is *compatible* with *P* if *A* \subset *B*, and for each choice (*u*,*v*,*w*) \in C either (*u*,*v*) \in *A* or (*v*,*w*) \in *A*"  
->  
"We say that *D* is *compatible* with *P* if *A* \subset *B*, and for each choice (*u*,*v*,*w*) \in C either (*u*,*v*) \in ***B*** or (*v*,*w*) \in ***B***"

[#7](https://github.com/supisula/ttodcc_errata/issues/7)


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

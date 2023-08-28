---
alias: 
tags: acad sem4 dbms unit3
---

## [[3.1 Higher Normal Forms ]]
## [[3.2 Inference Rules for Functional Dependencies ]]
## [[3.3 Transactions]]
[[3.4 Locking and Deadlocks]]


Important Questions::::
```
When a set of functional dependencies F said to be minimal? Give an algorithm for finding a minimal cover G for F.

Construct minimal cover F for set of functional dependencies 
E: {B → A, D → A, AB → D}
G: {A →BCDE, CD → E}.

Explain Armstrong’s inference rules with proof.

What do you understand by attribute closure? Give an example.

What are the anomalies occur due to interleaved execution? Explain them with example.

Why concurrency control is needed? Explain types of problems that may occur when two simple transactions run concurrently.
 
What are ACID properties? Explain.

What is a schedule? Explain with example conflict Serializable schedule.  

Consider the three transactions T1, T2 and T3 and schedules S1 and S2, given below. Determine whether each schedule is serializable or not. If a schedule is serializable, write down the equivalent serial schedule(S).
T1 : R1(X) ;R1(Z); W1(X);
T2 : R2(Z) ;R2(Y); W2(Z);W2(Y);
T3 : R3(X) ;R3(Y); W3(Y);
S1:R1(X) ;R2(Z); R1(Z);R3(X); R3(Y);W1(X); W3(Y);R2(Y); W2(Z);W2(Y); 
S2:R1(X) ;R2(Z); R3(X);R1(Z); R2(Y);R3(Y); W1(X);W2(Z); W3(Y);W2(Y);

Briefly explain the two phase locking protocol used in concurrency control.

When deadlock and starvation problem occur? Explain how these problems can be resolved.
```
# CHAPTER 1 Introduction to Groups

## 1 .1 Basic Axioms and Examples

>[!definition] Definition
>1. A binary operation $^ { \star }$ on a set $\pmb { G }$ is a function $\star : G \times G \to G$ . For any $a , b \in G$ we shall write ${ \pmb a } \star { \pmb b }$ for $\star ( a , b )$ . 
>2. A binary operation $^ \star$ on a set $\pmb { G }$ is associative if for all $a , b , c \in G$ we have $a \star ( b \star c ) = ( a \star b ) \star c$ . 
>3. If $\star$ is a binary operation on a set $G$ , we say elements $\pmb { a }$ and $\pmb{b}$ of $\pmb { G }$ commute if $a \star b = b \star a$ . We say $\star$ (or G) is commutative if for all a $, b \in G$ , $a \star b = b \star a$
>^def

>[!instance] Examples
>(1) $^ +$ (usual addition) is a commutative binary operation on $\mathbb { Z }$ (or on $\mathbb { Q } , \mathbb { R } .$ , or $\mathbb { C }$ respectively).   
(2) $\times$ (usual multiplication) is a commutative binary operation on $\mathbb { Z }$ (or on $\mathbb { Q } , \mathbb { R }$ , or $\mathbb { C }$ respectively).   
(3) - (usual subtraction) is a noncommutative binary operation on $\mathbb { Z } ,$ , where $- ( a , b ) =$ ${ \pmb a } - { \pmb b }$ . The map $a \mapsto - a$ is not a binary operation (not binary).   
(4) - is not a binary operation on $\mathbb { Z } ^ { + }$ (nor $\mathbb { Q } ^ { + }$ , $\mathbb { R } ^ { + } )$ ) because for ${ \mathfrak { a } } , b \in \mathbb { Z } ^ { + }$ with ${ a < b }$ , $a - b \notin \mathbb { Z } ^ { + }$ , that is, - does not map $\mathbb { Z } ^ { + } \times \mathbb { Z } ^ { + }$ into $\mathbb { Z } ^ { + }$ .   
(5) Taking the vector cross-product of two vectors in 3-space ${ \mathbb { R } } ^ { 3 }$ is a binary operation which is not associative and not commutative.
>^ins

>[!comment] aclazy
>vector cross-product of two vectors?
>^com

Suppose that $^ { \star }$ is a binary operation on a set $\pmb { G }$ and $\pmb { H }$ is a subset of $\pmb { G }$ . If the restriction of $\star$ to $H$ is a binary operation on $H ,$ , i.e. , for all $a , b \in H ,$ , $a \star b \in H$ , then $\pmb { H }$ is said to be closed under $^ { \star }$ · Observe that if $^ { \star }$ is an associative (respectively, commutative) binary operation on $\pmb { G }$ and $^ { \star }$ restricted to some subset $\pmb { H }$ of $\pmb { G }$ is a binary operation on $H _ { \cdot }$ , then $^ { \star }$ is automatically associative (respectively, commutative) on $\pmb { H }$ as well.

>[!definition] Definition
>1. A group is an ordered pair $( G , \star )$ where $\pmb { G }$ is a set and $^ { \star }$ is a binary operation on $\pmb { G }$ satisfying the following axioms:
>	1. $( a \star b ) \star c = a \star ( b \star c )$ , for all $a , b , c \in G$ , i.e. , $\star$ is associative, 
>	2. there exists an element $^ e$ in $\pmb { G }$ , called an identity of $\pmb { G }$ , such that for all $a \in G$ we have $a \star e = e \star a = a$ ,   
>	3. for each $a \in G$ there is an element $\displaystyle { \pmb { a } } ^ { - 1 }$ of $G _ { : }$ , called an inverse of $\pmb { a }$ such that $a \star a ^ { - 1 } = a ^ { - 1 } \star a = e$ .
>2. The group $( G , \star )$ is called abelian (or commutative ) if $a \star b = b \star a$ for all $a , b \in G$ .
>^def

We shall immediately become less formal and say $\pmb { G }$ is a group under $\star$ if $\left( G , \star \right)$ is a group (or just $\pmb { G }$ is a group when the operation $\star$ is clear from the context). Also, we say $\pmb { G }$ is a finite group if in addition $\pmb { G }$ is a finite set. Note that definition 1.2 ensures that a group is always nonempty.

>[!instance] Examples
>1. $\mathbb { Z } , \mathbb { Q } , \mathbb { R }$ and $\mathbb { C }$ are groups under $^ +$ with $e = 0$ and $\pmb { a } ^ { - 1 } = - \pmb { a }$ , for all $\pmb { a }$
>2. $\mathbb { Q } - \{ 0 \} , \mathbb { R } - \{ 0 \} , \mathbb { C } - \{ 0 \} , \mathbb { Q } ^ { + } , \mathbb { R } ^ { + }$ $\mathbb { R } ^ { + }$ are groups under $\times$ with $e = 1$ and $a ^ { - 1 } = { \frac { 1 } { a } } ,$ for all $\pmb { a } .$ Note however that Z - {0} is not a group under $\times$ because although $\times$ a  is an associative binary operation on $\mathbb { Z } - \{ 0 \}$ , the element 2 (for instance) does not have an inverse in $\mathbb { Z } - \{ 0 \}$ .
>^ins
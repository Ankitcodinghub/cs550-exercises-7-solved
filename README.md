# cs550-exercises-7-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Exercises 7 Solved](https://www.ankitcodinghub.com/product/cs550-solved-7/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118163&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Exercises 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Exercises 7

Exercise 1 (Iterating sp and wp). This question is inspired by relationships in a transition system. Let S be a non-empty set of states and r ⊆ S × S.

As usual, define

• for every P ⊆ S, sp(P,r) = {x′ | ∃x ∈ P.(x,x′) ∈ r}

• for every Q ⊆ S, wp(r,Q) = {x | ∀x′.(x,x′) ∈ r → x′ ∈ Q}

Let C = 2S = {X | X ⊆ S} be the set of all sets of states. Let also: Init ⊆ S and Good ⊆ S. Define:

• F : C → C as F(X) = Init ∪ sp(X,r)

• B : C → C as B(Y ) = Good ∩ wp(r,Y )

• l = Si≥0 Fi(∅)

• h = Ti≥0 Bi(S)

The ordering relation we consider is ⊆ relation on C. For each of the following determine if the property holds or not. If it holds, prove it. If it doesn’t, give a counterexample.

1. F is monotonic

2. B is monotonic

3. l is the least fixed point of F.

4. h is the greatest fixed point of B.

5. l ⊆ h.

6. l ⊆ Good implies Init ⊆ h

7. Init ⊆ h implies l ⊆ Good

1

Exercise 2 (Fix points in lattices). Consider a complete lattice with the set of elements L and the partial order ⊑. (Remember that in a complete lattice, every set X ⊆ L has the least upper bound and the greatest lower bound.)

Let G : L → L be a monotonic function with respect to ⊑. Let

Fix = {x ∈ L | G(x) = x}

be the set of all fixed points. Let x,y ∈ Fix be two fixed points. Prove or disprove:

1. x ⊔ y ⊑ G(x ⊔ y)

2. G(x ⊔ y) ⊑ x ⊔ y

3. x ⊔ y ∈ Fix

4. Let B = {b ∈ Fix | x ⊑ b∧y ⊑ b}. Then B has the least element, that is, an element z ∈ B such that ∀b ∈ B. z ⊑ b (Possibly difficult.)

Exercise 3 (Abstract interpretation). Consider a program on two integer variables, that is the set of states is C = 2Z×Z. We want to represent these states in an abstract domain such that this set of state is represented exactly for the first variable, and as intervals for the second variables.

1. Express the lattice A corresonding to this domain.

2. Give expressions for α : C → A and γ : A → C and show that this form a Galois Connection.

Exercise 4 (Program analysis). Consider the program that manipulates two integer variables x and y. Consider any assignement of the form x = e, where e is a linear combination of integer variables, for example

x = 2 ∗ x − 5 ∗ y

Consider an abstract analysis with intervals for both variables. Describe an algorithm that given the syntax tree of e, and intervals for x (noted [ax,bx]) and y (noted [ay,by]) computes the new interval [a,b] for x after the assignement statement.

2

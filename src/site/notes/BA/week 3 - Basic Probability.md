---
{"dg-publish":true,"permalink":"/ba/week-3-basic-probability/","title":"Basic Probability - 1","created":"2026-02-06T19:04:13.450+05:30","updated":"2026-02-16T06:35:34.966+05:30"}
---

# What is Probability?

A probability is the **numeric value** representing the **chance, likelihood, or possibility** that a particular event will occur.

The **probability of an event A**, denoted by **P(A)**, is a number between 0 and 1 that represents the likelihood of A occurring.

- If $P(A)$ = 0, the event A is **impossible**.
- If $P(A)$ = 1, the event A is **certain** to occur.
- If $$0 \leq P(A) \leq 1$$ the event A is possible but not guaranteed.

## Comparison of Probability Types

| **Aspect**     | **A Priori Probability**                          | **Empirical Probability**                                             | **Subjective Probability**                                 |
| -------------- | ------------------------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------- |
| **Definition** | Based on prior knowledge or theoretical reasoning | Based on observed data from experiments or historical records         | Based on personal judgment, intuition, or belief           |
| **Example**    | Probability of rolling a 4 on a fair die = 1/6    | After flipping a coin 100 times and getting 53 heads, P(heads) = 0.53 | An expert estimates 70% chance of rain based on experience |

$\boxed{\text{Examples:  }}$

Categorize These Scenarios into Probability Types

1. A teacher flipped a coin 200 times in class and observed 112 heads. She calculated the probability of getting heads as 112/200 = 56%.

2. A financial analyst reviews a company's performance, market trends, and economic conditions, then estimates there's a 75% chance the stock price will increase next quarter.

3. When rolling a standard six-sided die, you determine that the probability of rolling a number greater than 4 is 2/6

$\boxed{Solutions:}$
1. Empirical probability
2. Subjective probability
3. A prior probability

## Formula
$$

P(occurrence) = \frac{\text{Number of favourable outcomes}}{\text{Total Number of outcomes}}

$$

$\boxed{Example:}$ 

Standard deck of cards
26 red cards, 26 black cards (52 total)
$$P(black card) = \frac{26}
{52} = 0.50$$

## Key definitions

- **Sample space**: Collection of all possible events
- **Event**: Each possible outcome of a variable
- **Simple event**: Described by a single characteristic
- **Joint event**: Has two or more characteristics
- **Complement of A (A′)**: All events that are not part of A

$\boxed{Example:}$

Rolling a Die 🎲

- Sample Space
	**All possible outcomes when you roll a die:**

	Sample Space = {1, 2, 3, 4, 5, 6}

- Event
	**Any outcome or group of outcomes**
	
	- Event A = Getting an even number = {2, 4, 6}
	- Event B = Getting a number greater than 4 = {5, 6}

- Simple Event
	**Described by ONE characteristic only**
	
	- Simple Event 1 = Rolling a 3 = {3}
	- Simple Event 2 = Rolling a 5 = {5}
	- Simple Event 3 = Getting an even number = {2, 4, 6}

- Joint Event
	**Has TWO or MORE characteristics (must satisfy multiple conditions)**
	
	**Joint Event = Getting an even number AND greater than 3**
	- Even numbers: {2, 4, 6}
	- Greater than 3: {4, 5, 6}
	- **Both conditions:** {4, 6}
	So the joint event = {4, 6}

- Complement of A (A′)
	**Everything that is NOT in event A**
	
	If Event A = Getting an even number = {2, 4, 6}
	Then A′ = NOT getting an even number = {1, 3, 5}
	
	**Notice:** A + A′ = {2, 4, 6} + {1, 3, 5} = {1, 2, 3, 4, 5, 6} = Sample Space ✓

![](https://i.postimg.cc/tg1v5Q2V/image.png)

# Venn Diagrams & Set Notations

## Set Notations

Set notation is used in mathematics to essentially list numbers, objects or outcomes. 

### Basic Set Symbols

| **Notation** | **Meaning**                                          | **Example**                     |
| ------------ | ---------------------------------------------------- | ------------------------------- |
| { }          | Set brackets                                         | A = {1, 2, 3}                   |
| S or U or Ω  | Sample space / Universal set (all possible elements) | P(Ω) = 1                        |
| ∈            | "Is an element of" / "belongs to"                    | 2 ∈ A means "2 is in set A"     |
| ∉            | "Is not an element of"                               | 5 ∉ A means "5 is not in set A" |
| ∅ or { }     | Empty set (no elements)                              | B = ∅                           |

## Set Operations, Formulas and Venn Diagrams

### 1. Intersection

| **Notation**        | **Name**        | **Meaning**                             |
| ------------------- | --------------- | --------------------------------------- |
| A ∩ B               | AND             | Elements in BOTH A and B (overlap)      |
#### Venn Diagram
<img src="https://i.postimg.cc/Wb57nKyx/image.png" alt="A descriptive text" width="30%">

### 2. Union

| **Notation** | **Name** | **Meaning**                             |
| ------------ | -------- | --------------------------------------- |
| A ∪ B        | OR       | Elements in A or B or both (total area) |
#### Venn Diagram
<img src="https://i.postimg.cc/JhLtB7qJ/image.png" alt="A descriptive text" width="30%">

#### Formula (General Addition Rule)
$$
P(A ∪ B) = P(A) + P(B) − P(A ∩ B)
$$

### 3. Complement

| **Notation** | **Name** | **Meaning**       |
| ------------ | -------- | ----------------- |
| A′ or Aᶜ     | NOT A    | Elements NOT in A |
#### Venn Diagram
<img src="https://i.postimg.cc/cL90dsbT/image.png" alt="A descriptive text" width="30%">

#### Formula 
$$
P(A^′) = 1 − P(A)
$$

### 4. Only A

| **Notation**    | **Name**    | **Meaning**                |
| --------------- | ----------- | -------------------------- |
| A − B or A ∩ B′ | A but not B | Elements in A but NOT in B |
#### Venn Diagram
<img src="https://i.postimg.cc/KjJstYBY/image.png" alt="A descriptive text" width="30%">

#### Formula
$$
P(A − B)=P(A) − P(A ∩ B)
$$

### 5.Symmetric Difference

| **Notation**   | **Name** | **Meaning**                     |
| -------------- | -------- | ------------------------------- |
| A Δ B or A ⊕ B | XOR      | Elements in A or B but NOT both |
#### Venn Diagram
<img src="https://i.postimg.cc/G23FGxQ8/image.png" alt="A descriptive text" width="30%">

#### Formula
$$
P(A Δ B)=P(A) + P(B) − 2P(A ∩ B)
$$
$$
P(A Δ B)=P(A ∪ B) − P(A ∩ B)
$$

### 6.Neither

| **Notation**        | **Name**        | **Meaning**                 |
| ------------------- | --------------- | --------------------------- |
| (A ∪ B)′ or A′ ∩ B′ | NOT A and NOT B | Elements in neither A nor B |
#### Venn Diagram
<img src="https://i.postimg.cc/9zHztWh6/image.png" alt="A descriptive text" width="30%">

#### Formula
$$
P(A ∪ B)^′=1 − P(A ∪ B)
$$

$\boxed{Example :}$

- **Universal Set S** = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
- **A** = {2, 4, 6, 8}
- **B** = {6, 7, 8, 9}

| **Operation**            | **Notation**        | **Result**          | **Elements**        |
| ------------------------ | ------------------- | ------------------- | ------------------- |
| **Intersection**         | A ∩ B               | Overlap             | {6, 8}              |
| **Union**                | A ∪ B               | Combined            | {2, 4, 6, 7, 8, 9}  |
| **Complement of A**      | A′                  | Not in A            | {1, 3, 5, 7, 9, 10} |
| **Complement of B**      | B′                  | Not in B            | {1, 2, 3, 4, 5, 10} |
| **Only A**               | A − B or A ∩ B′     | A but not B         | {2, 4}              |
| **Only B**               | B − A or B ∩ A′     | B but not A         | {7, 9}              |
| **Symmetric Difference** | A Δ B               | Either but not both | {2, 4, 7, 9}        |
| **Neither**              | (A ∪ B)′ or A′ ∩ B′ | Outside both        | {1, 3, 5, 10}       |

![](https://i.postimg.cc/QxfjDS8M/image.png)
![](https://i.postimg.cc/c179TcMR/image.png)


![](https://i.postimg.cc/ncj3VhZp/image.png)
![](https://i.postimg.cc/SNNrdbKS/image.png)

# Probability Types

**Contingency Table: Customer Behavior**

|                  | **Purchased** | **Did Not Purchase** | **Total** |
| ---------------- | ------------- | -------------------- | --------- |
| **Planned**      | 200           | 50                   | 250       |
| **Did Not Plan** | 100           | 650                  | 750       |
| **Total**        | 300           | 700                  | 1000      |

## 1. Simple (Marginal) Probability

**Definition:** Probability of a single event occurring (found in margins/totals of table)

**Example:**
$$\begin{align}
P(\text{Planned}) &= \frac{250}{1000} = 0.25 \\
P(\text{Did Not Plan}) &= \frac{750}{1000} = 0.75 \\
P(\text{Purchased}) &= \frac{300}{1000} = 0.30 \\
P(\text{Did Not Purchase}) &= \frac{700}{1000} = 0.70
\end{align}$$

## 2. Joint Probability

**Definition:** Probability of TWO events occurring together (at the same time)

**Notation:** $P(A \cap B)$ or $P(A \text{ AND } B)$

**Formula:**
$$P(A \cap B) = \frac{\text{Frequency of both A and B}}{\text{Total}}$$

**Example:**
$$\begin{align}
P(\text{Planned} \cap \text{Purchased}) &= \frac{200}{1000} = 0.20 \\
P(\text{Planned} \cap \text{Did Not Purchase}) &= \frac{50}{1000} = 0.05 \\
P(\text{Did Not Plan} \cap \text{Purchased}) &= \frac{100}{1000} = 0.10 \\
P(\text{Did Not Plan} \cap \text{Did Not Purchase}) &= \frac{650}{1000} = 0.65
\end{align}$$

## 3. Marginal Probability (Using Joint Probabilities)

**Definition:** Total probability of an event by summing all its joint probabilities

**Formula:**
$$P(A) = P(A \cap B_1) + P(A \cap B_2) + P(A \cap B_3) + \cdots + P(A \cap B_k)$$

**Example:**
$$\begin{align}
P(\text{Planned}) &= P(\text{Planned} \cap \text{Purchased}) + P(\text{Planned} \cap \text{Did Not Purchase}) \\
&= 0.20 + 0.05 = 0.25 \quad \checkmark
\end{align}$$
$$\begin{align}
P(\text{Purchased}) &= P(\text{Planned} \cap \text{Purchased}) + P(\text{Did Not Plan} \cap \text{Purchased}) \\
&= 0.20 + 0.10 = 0.30 \quad \checkmark
\end{align}$$

![](https://i.postimg.cc/VLqD0Hrz/image.png)
![](https://i.postimg.cc/gkJVRyMG/image.png)
![](https://i.postimg.cc/dVZGNsPX/image.png)

# Important Concepts

## Mutually Exclusive Events

**Definition:** Two events that CANNOT happen at the same time

**Characteristic:**
$$\text{If A and B are mutually exclusive: } $$
$$P(A \cap B) = 0$$
$$P(A \cup B) = P(A) + P(B)$$

**Examples:**
- Coin flip: Getting heads AND tails (mutually exclusive)
- Student status: Being a freshman AND being a senior (mutually exclusive)

**Visual:**
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYmAWIqJaxG_5fVLzjQLtEYOpCWyJooG_8mw&s)

## Collectively Exhaustive Events

**Definition:** Events that cover ALL possible outcomes (nothing left out)

**Characteristic:**
$$\text{If } B_1, B_2, \ldots, B_k \text{ are collectively exhaustive: } $$
$$P(B_1) + P(B_2) + \cdots + P(B_k) = 1$$

**Examples:**
- {Heads, Tails} when flipping a coin - exhaustive
- {Pass, Fail} for a test - exhaustive
- {Planned, Did Not Plan} - exhaustive

**Visual:**
<img src="https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/exhaustive-events-1634887073.png" alt="A description of the image" width="40%">

## Mutually Exclusive AND Collectively Exhaustive

**When BOTH conditions apply:**

Events that:
1. Don't overlap (mutually exclusive)
2. Cover everything (collectively exhaustive)

**Characteristic:**
$$P(B_1 \cap B_2 \cap B_3 \cap ...\cap B_k) = 0 \quad \text{(no overlap)}$$
$$P(B_1) + P(B_2) + \cdots + P(B_k) = 1 \quad \text{(covers everything)}$$

**Example:**

{Planned, Did Not Plan}
- Mutually exclusive: Can't be both ✓
- Collectively exhaustive: Everyone is one or the other ✓


**Why important for marginal probability:**

When $B_1, B_2, \ldots, B_k$ are mutually exclusive and collectively exhaustive:
$$P(A) = P(A \cap B_1) + P(A \cap B_2) + \cdots + P(A \cap B_k)$$

This is guaranteed to give the total probability of A

**Visual:**
<img src="https://cdn1.byjus.com/wp-content/uploads/2021/07/exhaustive-events.png" alt="A description of the image" width="60%">

$\boxed{Exercise:}$

Given Table:

| | **Pass** | **Fail** | **Total** |
|------------|------|------|---------|
| **Studied** | 70 | 10 | 80 |
| **Didn't Study** | 15 | 5 | 20 |
| **Total** | 85 | 15 | 100 |

Questions:

1. Find $P(\text{Studied})$ - Simple probability
2. Find $P(\text{Pass})$ - Simple probability  
3. Find $P(\text{Studied} \cap \text{Pass})$ - Joint probability
4. Find $P(\text{Pass})$ using joint probabilities
5. Are {Studied, Didn't Study} mutually exclusive?
6. Are {Pass, Fail} collectively exhaustive?

$\boxed{Answers:}$

1. $P(\text{Studied})$= $\frac{80}{100} = 0.80$

2. $P(\text{Pass})$ = $\frac{85}{100} = 0.85$

3. $P(\text{Studied} \cap \text{Pass})$= $\frac{70}{100} = 0.70$

4. $P(\text{Pass})$ using joints:
   $$\begin{align}
   P(\text{Pass}) &= P(\text{Studied} \cap \text{Pass}) + P(\text{Didn't Study} \cap \text{Pass}) \\
   &= \frac{70}{100} + \frac{15}{100} \\
   &= \frac{85}{100} = 0.85 \quad \checkmark
   \end{align}$$

5. Yes, mutually exclusive - A student cannot both study and not study
   *$$P(\text{Studied} \cap \text{Didn't Study}) = 0$$*

6. Yes, collectively exhaustive - Every student either passed or failed
   $$P(\text{Pass}) + P(\text{Fail}) = 0.85 + 0.15 = 1.00 \quad \checkmark$$

![](https://i.postimg.cc/Lsc1T2wy/image.png)
![](https://i.postimg.cc/nz2m9MBV/image.png)
![](https://i.postimg.cc/3J4yYtSd/image.png)

# Conditional Probability

#### Definition:

**Conditional probability** is the probability of an event occurring given that another event has already occurred.

#### Notation

$P(A|B)$  reads as "probability of A given B"

#### Formula

$$P(A|B) = \frac{P(A ∩ B)} {P(B)}$$
$$P(B|A) = \frac{P(A ∩ B)} {P(A)}$$
#### Extra Formulas

$$P(A'|B) = 1-P(A|B)$$
$$P(B'|A) = 1-P(B|A)$$

## Key Properties

#### Multiplication Rule:
$$
\begin{array}{c|c}
\textbf{Using } P(A \mid B) & \textbf{Using } P(B \mid A) \\ \hline
P(A \mid B) = \dfrac{P(A \cap B)}{P(B)} 
& 
P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} \\[8pt]

P(A \mid B)\,P(B) = P(A \cap B) 
& 
P(B \mid A)\,P(A) = P(A \cap B) \\[8pt]

P(A \cap B) = P(A \mid B)\,P(B) 
& 
P(A \cap B) = P(B \mid A)\,P(A)
\end{array}
$$

$$
P(A ∩ B) = P(A|B) × P(B) = P(B|A) × P(A)
$$


#### Law of Total Probability:

If $B₁, B₂, ..., Bₙ$ form a partition of the sample space:

$$
P(A) = Σ P(A|Bᵢ) × P(Bᵢ)
$$

#### Independence: 

**Independent** means the outcome of one event **has no effect** on the other.

Events A and B are independent if:

$$
P(A|B) = P(A)
$$

Knowing B occurred doesn't change the probability of A.

**Alternative test for independence:**

$$
P(A ∩ B) = P(A) × P(B)
$$
$$
P(A ∩ B'∩ C) = P(A) × P(B')× P(C)
$$

![](https://i.postimg.cc/cHcLnWSY/image.png)
![](https://i.postimg.cc/kGkg2d1V/image.png)
![](https://i.postimg.cc/XY6v34yq/image.png)

## Decision Tree
#### Definition and Structure

<img scr="">![](https://media.geeksforgeeks.org/wp-content/uploads/20250626155553066708/_what_is_a_decision_tree_.webp)

**Alternative to contingency tables for visualizing probabilities**

![](https://images.nagwa.com/figures/explainers/568173987072/21.svg)

#### Key Principles

##### Multiplication Rule (Along Branches)

To find the probability of a sequence of events, **multiply** the probabilities along the path:

$$
P(A ∩ B) = P(A) × P(B|A)
$$

##### Addition Rule (Across Branches)

To find the probability of multiple paths leading to the same outcome, **add** the probabilities:

$$
P(Outcome) = Σ P(\text{path to outcome})
$$

##### Total Probability Must Equal 1

At each branch point, all probabilities leaving that node must sum to 1:

$$
P(A) + P(A') = 1
$$


![](https://www.mathsisfun.com/data/images/probability-tree-coin3.svg)

![](https://i.postimg.cc/CMPFTmMQ/image.png)
![](https://i.postimg.cc/9M0m1fsB/image.png)
![](https://i.postimg.cc/NGWX9hrN/image.png)

# Bayes’ Theorem

#### Purpose

describes how to update our beliefs about the likelihood of an event based on new evidence.

#### Basic Formula

For two events A and B, Bayes' Theorem states:

$$\text{Posterior} = \frac{\text{Likelihood} \times \text{Prior}}{\text{Evidence}}$$

$$
P(A|B) = \frac{P(B|A) \times{P(A)}} {P(B)}
$$


**Where:**

- **P(A|B)** = Posterior probability (probability of A given that B has occurred)
- **P(B|A)** = Likelihood (probability of B given that A has occurred)
- **P(A)** = Prior probability (initial probability of A)
- **P(B)** = Marginal probability (total probability of B)

##### Derivation of Bayes’ Theorem from Conditional Probability

$$
\begin{array}{c|c}
\textbf{Using } P(A \mid B) & \textbf{Using } P(B \mid A) \\ \hline

P(A \mid B) = \dfrac{P(A \cap B)}{P(B)} 
& 
P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} \\[10pt]

P(A \cap B) = P(A \mid B)\,P(B) 
& 
P(A \cap B) = P(B \mid A)\,P(A) \\[10pt]

\end{array}
$$
$$
\begin{aligned}
P(A \mid B)\,P(B) &= P(B \mid A)\,P(A) \\[8pt]
\dfrac{P(A \mid B)\,P(B)}{P(B)} &= \dfrac{P(B \mid A)\,P(A)}{P(B)} \\[10pt]
P(A \mid B) &= \dfrac{P(B \mid A)\,P(A)}{P(B)}
\end{aligned}
$$

##### Extended Form

When event B can occur with either A or not-A (denoted A'):

$$
P(A|B) = \frac{P(B|A) × P(A)}{P(B|A) × P(A) + P(B|A') × P(A')}
$$
Also:

where $B_1, B_2, . . . , B_k$ are mutually exclusive and collectively exhaustive

$$
P(B_i|A) = \frac{P(A|B_i) × P(B_i)}{P(A|B_1) × P(B_1) + P(A|B_2) × P(B_2)+...+P(A|B_k) × P(B_k)}
$$

#### Examples

$\boxed{Example 1:}$

**Problem:** A disease affects 1% of the population. A test for the disease is 95% accurate (correctly identifies 95% of sick people and correctly identifies 95% of healthy people). If you test positive, what's the probability you actually have the disease?

**Given:**

$$
\begin{array}{l}
P(\text{Disease}) = 0.01 \\
P(\text{Healthy}) = 0.99 \\
P(\text{Positive}|\text{Disease}) = 0.95 \\
P(\text{Positive}|\text{Healthy}) = 0.05 \text{ (false positive rate)}
\end{array}
$$

$\boxed{Solution1:}$

$$
\begin{align}
P(\text{Disease}|\text{Positive}) &= \frac{P(\text{Positive}|\text{Disease}) \cdot P(\text{Disease})}{P(\text{Positive}|\text{Disease}) \cdot P(\text{Disease}) + P(\text{Positive}|\text{Healthy}) \cdot P(\text{Healthy})} \\[10pt]
&= \frac{0.95 \times 0.01}{(0.95 \times 0.01) + (0.05 \times 0.99)} \\[10pt]
&= \frac{0.0095}{0.0095 + 0.0495} \\[10pt]
&= \frac{0.0095}{0.059} \\[10pt]
&\approx 0.161 \text{ or } 16.1\%
\end{align}
$$


$\boxed{Example 2:}$

**Problem:** 60% of emails are spam. The word "free" appears in 80% of spam emails but only 10% of legitimate emails. If an email contains the word "free," what's the probability it's spam?

**Given:**

$$
\begin{array}{l}
P(\text{Spam}) &= 0.60 \\
P(\text{Legitimate}) &= 0.40 \\
P(\text{"free"}|\text{Spam}) &= 0.80 \\
P(\text{"free"}|\text{Legitimate}) &= 0.10
\end{array}
$$

$\boxed{Solution2:}$

$$
\begin{aligned}
P(\text{Spam}|\text{"free"}) &= \frac{P(\text{"free"}|\text{Spam}) \times P(\text{Spam})}{P(\text{"free"}|\text{Spam}) \times P(\text{Spam}) + P(\text{"free"}|\text{Legitimate}) \times P(\text{Legitimate})} \\[10pt]
&= \frac{0.80 \times 0.60}{(0.80 \times 0.60) + (0.10 \times 0.40)} \\[10pt]
&= \frac{0.48}{0.48 + 0.04} \\[10pt]
&= \frac{0.48}{0.52} \\[10pt]
&\approx 0.923 \text{ or } 92.3\%
\end{aligned}
$$


$\boxed{Example 3:}$

**Problem:** A factory has three machines (A, B, C) that produce 30%, 45%, and 25% of the total output respectively. The defect rates are 2%, 3%, and 4% for machines A, B, and C. If a randomly selected item is defective, what's the probability it came from machine B?

**Given:**

$$
\begin{aligned}
P(A) &= 0.30 \\
P(B) &= 0.45 \\
P(C) &= 0.25 \\
P(\text{Defective}|A) &= 0.02 \\
P(\text{Defective}|B) &= 0.03 \\
P(\text{Defective}|C) &= 0.04
\end{aligned}
$$

$\boxed{Solution3:}$

First, find P(Defective):

$$
\begin{aligned}
P(\text{Defective}) &= P(\text{Defective}|A) \times P(A) + P(\text{Defective}|B) \times P(B) + P(\text{Defective}|C) \times P(C) \\[10pt]
&= (0.02 \times 0.30) + (0.03 \times 0.45) + (0.04 \times 0.25) \\[10pt]
&= 0.006 + 0.0135 + 0.01 \\[10pt]
&= 0.0295
\end{aligned}
$$

Now apply Bayes' Theorem:

$$
\begin{aligned}
P(B|\text{Defective}) &= \frac{P(\text{Defective}|B) \times P(B)}{P(\text{Defective})} \\[10pt]
&= \frac{0.03 \times 0.45}{0.0295} \\[10pt]
&= \frac{0.0135}{0.0295} \\[10pt]
&\approx 0.458 \text{ or } 45.8\%
\end{aligned}
$$


![](https://i.postimg.cc/g0m96Zkt/image.png)
![](https://i.postimg.cc/g0SXG1Wt/image.png)
![](https://i.postimg.cc/sfZQRn01/image.png)

# Counting Rules
## Counting rule 1 
For Mutually exclusive and collectively exhaustive events:
<img src="https://cdn1.byjus.com/wp-content/uploads/2021/07/exhaustive-events.png" alt="A description of the image" width="70%">
And **same number of events are coming in each trial**.

$$
\text{Number of outcomes}= k^n
$$
where,
- k = number of different outcomes per trial
- n = number of trials

$\boxed{Example}$

Tossing a coin 5 times

- k = 2 (heads or tails)
- n = 5 (five tosses)
$$
\text{Number of outcomes} = 2^5 = 32
$$

## Counting rule 2

**Number of events differs from trial to trial**:

$$
\text{Number of outcomes}= (k_1)\times(k_2)...(k_n)
$$
where:
$$
k_i=\text{number of events on trial i}
$$
$\boxed{Example}$

License plates (3 letters, 3 numbers)
- First letter: 26 choices
- Second letter: 26 choices
- Third letter: 26 choices
- First number: 10 choices (0-9)
- Second number: 10 choices
- Third number: 10 choices
$$
Total: (26)(26)(26)(10)(10)(10) = 17, 576, 000
$$

## Counting rule 3 - Factorials

**Number of ways to** **arrange $n$ items in order**: 
$\text{n factorial}$

$$n!=n\times(n-1)\times(n-2)\times...\times2 \times1$$
$$5! = 5 \times 4 \times 3 \times 2 \times 1 = 120$$ $$3! = 3 \times 2 \times 1 = 6$$
 $$0! = 1$$
$\boxed{Example}$

Arranging 6 books on a shelf

$$
6! = 6 × 5 × 4 × 3 × 2 × 1
= \text{720 different arrangements}
$$

## Counting rule 4 - Permutations

**Number of ways to arrange $x$ objects from $n$ objects in order**:

$$_nP_r = \frac{n!}{(n-r)!}$$
Expanded Form:

$$_nP_r = n \times (n-1) \times (n-2) \times \cdots \times (n-r+1)$$

$\boxed{Example}$

6 books, but only room for 4 on shelf

$$_6P_4 = \frac{6!}{(6-4)!} = \frac{6!}{2!} = \frac{6\times5\times4\times3\times2\times1}{2\times1} = 360$$

## Counting Rule 5 - Combinations

**Number of ways to arrange $x$ objects from $n$ objects , order does not matter**:

$$_nC_r = \frac{n!}{r!(n-r)!}$$
$$_nC_r = \frac{_nP_r}{r!}$$

$\boxed{Example}$

Selecting 4 books from 6, order irrelevant
$$_6C_4 = \frac{6!}{4!(6-4)!} = \frac{6!}{4! \cdot 2!} = \frac{6\times5}{2\times 1} = 15$$

## Permutations vs. Combinations 

| Aspect                   | Permutations                                                 | Combinations                                               |
| ------------------------ | ------------------------------------------------------------ | ---------------------------------------------------------- |
| **Order**                | Order **MATTERS**                                            | Order **DOES NOT MATTER**                                  |
| **Formula**              | $$_nP_r = \frac{n!}{(n-r)!}$$                                | $$_nC_r = \frac{n!}{r!(n-r)!}$$                            |
| **Alternative Notation** | $$_nP_r$$                                                    | $$_nC_r$$                                                  |
| **Expanded Form**        | $$n \times (n-1) \times (n-2) \times \cdots \times (n-r+1)$$ | $$\frac{n \times (n-1) \times \cdots \times (n-r+1)}{r!}$$ |
| **Result Size**          | Larger                                                       | Smaller                                                    |

![](https://i.postimg.cc/0jJX4ky6/image.png)
![](https://i.postimg.cc/sDYMMMz7/image.png)
![](https://i.postimg.cc/mgVhSKhv/image.png)

# Summary

## 1. Key Probability Concepts

### Basic Probability Rules

$$0 \leq P(A) \leq 1$$

**Types of Probabilities:**
- **Simple Probability**: Probability of a single event
- **Joint Probability**: Probability of two or more events occurring together
- **Marginal Probability**: Total probability of an event across all conditions

### General Addition Rule

$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$

**When to use:**
- Finding probability of "A **OR** B"
- Union of events
- Subtract intersection to avoid double-counting

## 2. Conditional Probability

### Formula

$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

**Reads as:** "Probability of A given B"

### Independence

Events A and B are independent if:

$$P(A|B) = P(A)$$

**OR equivalently:**

$$P(A \cap B) = P(A) \times P(B)$$

### Multiplication Rules

**For Independent Events:**

$$P(A \cap B) = P(A) \times P(B)$$

**For Dependent Events:**

$$P(A \cap B) = P(A) \times P(B|A)$$

## 3. Bayes' Theorem

**Purpose:** Revise probabilities based on new information

**Process:** Prior Probability → Posterior Probability

$$P(A|B) = \frac{P(B|A) \times P(A)}{P(B)}$$

## 4. Counting Rules Summary

| Rule | Formula | When to Use | Example |
|------|---------|-------------|---------|
| **Rule 1** | $$k^n$$ | Same # of outcomes each trial | Coin flips, dice rolls |
| **Rule 2** | $$(k_1)(k_2) \cdots (k_n)$$ | Different # of outcomes per trial | Menu choices, outfits |
| **Rule 3** | $$n!$$ | Arrange all n items | Arranging books |
| **Rule 4** | $$_nP_x = \frac{n!}{(n-x)!}$$ | Arrange x from n (order matters) | Race positions, passwords |
| **Rule 5** | $$_nC_x = \frac{n!}{x!(n-x)!}$$ | Select x from n (order doesn't matter) | Committees, teams |

### Key Decision: Does Order Matter?
```
Does order matter?
├─ YES → Use Permutations (Rule 4)
└─ NO  → Use Combinations (Rule 5)
```

## 5. Permutations vs. Combinations

| Aspect | Permutations | Combinations |
|--------|--------------|--------------|
| **Order** | Matters | Doesn't matter |
| **Formula** | $$_nP_x = \frac{n!}{(n-x)!}$$ | $$_nC_x = \frac{n!}{x!(n-x)!}$$ |
| **Result** | Larger number | Smaller number |
| **Keywords** | Arrange, order, sequence, rank | Choose, select, group, committee |
| **Example** | PIN codes, race positions | Lottery, team selection |

**Relationship:**

$$_nC_x = \frac{_nP_x}{x!}$$

## 6. Common Mistakes to Avoid

### Mistake 1: Confusing AND vs. OR

- **AND** = Intersection (∩) → Multiply if independent
- **OR** = Union (∪) → Add then subtract intersection

$$
\begin{aligned}
P(A \text{ AND } B) &= P(A \cap B) \\
P(A \text{ OR } B) &= P(A) + P(B) - P(A \cap B)
\end{aligned}
$$

### Mistake 2: Assuming Independence

**Always verify:**

$$P(A|B) = P(A) \quad \text{?}$$

$$P(A \cap B) = P(A) \times P(B) \quad \text{?}$$

### Mistake 3: Conditional Probability Confusion

$$P(A|B) \neq P(B|A)$$

Always identify the condition properly!

### Mistake 4: Permutations vs. Combinations

- Read carefully: does order matter?
- Remember: $$_nP_x > _nC_x$$ for same n and x

## 7. Problem-Solving Strategy

### Step-by-Step Approach:

**Step 1:** Identify the type of probability question
- Simple? Joint? Conditional?

**Step 2:** Organize the data
- Contingency table
- Decision tree
- Venn diagram

**Step 3:** Select appropriate formula
- Addition rule?
- Multiplication rule?
- Bayes' theorem?

**Step 4:** Calculate carefully
- Show all steps
- Check that probabilities sum to 1

**Step 5:** Interpret results in context
- What does the answer mean?
- Does it make intuitive sense?

## 8. Practice Tips

### Visual Tools:
- **Venn diagrams** for visualizing relationships
- **Decision trees** for sequential events
- **Contingency tables** for organizing data

### Check Your Work:
- Do probabilities sum to 1?
- Is answer between 0 and 1?
- Does it make intuitive sense?

### Practice Different Types:
- Simple and joint probabilities
- Conditional probabilities
- Bayes' theorem problems
- Counting problems

### Understand the Logic:
- Don't just memorize formulas
- Know **when** to use each formula
- Understand **why** formulas work


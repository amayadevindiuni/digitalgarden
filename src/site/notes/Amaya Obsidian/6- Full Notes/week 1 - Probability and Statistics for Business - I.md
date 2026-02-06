---
{"dg-publish":true,"permalink":"/amaya-obsidian/6-full-notes/week-1-probability-and-statistics-for-business-i/","title":"week 1 - Probability and Statistics for Business - I","tags":["lecture","#set_theory","#basic_probability","#sem_1_Probability_and_Statistics_for_Business_part_1"],"created":"2026-01-19T12:30:49.440+05:30","updated":"2026-02-06T18:39:29.014+05:30"}
---

# week 1
- [[#1. Statistic categorization]]
	- [[#1.1 Descriptive statistics]]
	- [[#1.2 Inferential statistics]]
- [[#2. Individuals, variables, and observations]]
	- [[#2.1 Types of variables]]
		- [[#2.1.1 Types of Categorical (Qualitative) Variables]]
		- [[#2.1.2 Types of Numerical (Quantitative) Variables]]
	- [[#2.2 The Four Scales of Measurement]]
-  [[#3. Summary Statistics]]
	-  [[#3.1 Measure of Location (Central Tendency)]]
		- [[#3.1.1. Simple Arithmetic Mean]]
		- [[#3.1.2 Weighted Arithmetic Mean]]
		- [[#3.1.3 Combined/Composite Arithmetic Mean]]
		- [[#3.1.4 Standard Geometric Mean ($G$)]]
		- [[#3.1.5 Geometric Mean (An Alternative Version) $G_{Alt}$]]
		- [[#3.1.6 Harmonic Mean ($H$)]]
		- [[#3.1.7 Relationship with Other Means]]
		- [[#3.1.8 Mode (Mo)]]
		- [[#3.1.9 Median (Md)]]
	- [[#3.2 Quartiles ( $Q_i$, $i = 1, 2, 3$ )]]
	- [[#3.3 Grouped Data Distributions]]
		- [[#3.3.1 Class Interval and Class Limits]]
		- [[#3.3.2 Class Boundaries / True class limits]]
		- [[#3.3.3 Size (Width) of a Class Interval ($c_i$)]]
	- [[#3.4 Measures of Central Tendency for Grouped Data]]
		- [[#3.4.1 Mean ( $ bar{X}$ )]]
		- [[#3.4.2 Mode ($Mo$) – Modal Class Method]]
		- [[#3.4.3 Quartiles ( $Q_i, i = 1, 2, 3$ )]]
		- [[#3.4.4 Deciles ( $D_i, i = 1, 2, dots, 9$ )]]
		- [[#3.4.5 Percentiles ($P_i, i = 1, 2, dots, 99$)]]
	- [[#3.5 Measures of Dispersion]]
		- [[#3.5.1 Range]]
		- [[#3.5.2 Interquartile Range (IQR)]]
		- [[#3.5.3 Semi-Interquartile Range (SIQR)]]
		- [[#3.5.4 Mean Deviation (MD)]]
		- [[#3.5.5 Mean Absolute Deviation (MAD)]]
		- [[#3.5.6 Median Absolute Deviation]]
		- [[#3.5.7 Variance]]
		- [[#3.5.8 Standard Deviation]]
		- [[#3.5.9 Coefficient of Variation (CV)]]
		- [[#3.5.10 Variance for Grouped Data]]

---
# 1. Statistic categorization
categorized into two main parts
- **Descriptive statistics**
- **Inferential statistics**
---
## 1.1 Descriptive statistics
Gives an idea about the data we already have and gives a summary of all the features we can get from a given data. it consists,
- data collection
- organization
- presentation
- analysis

Examples:
- getting average height of all the students in the class when we know all the heights
---
## 1.2 Inferential statistics
Get insights of a large population using a sample of that population, in this we **examine a representative subset(sample) of the population**

Probability measures how likely an event is to occur it's a way of quantifying uncertainty.

Example:
- When we need to find the average height of the whole school, we will only measure the heights of a smaller group which represents the population and get insights from that.

![Cat Image](https://i.postimg.cc/3xBTVnrk/Pasted-image-20260120102719.png)

---
# 2. Individuals, variables, and observations
- **Individuals**: the entities being studied (people, objects, events, etc.) 
- **Variable**: Characteristic of individual (columns of a table)
- **Observations**: the data collected from those individuals (rows of a table)

<img src="https://www.statology.org/wp-content/uploads/2020/11/obs5.png" alt="A description of the image" width="600" >

---
## 2.1 Types of variables 
Two types
- **Categorical variable (Qualitative)**
- **Numerical variable (Quantitative)**

| Feature    | Categorical Variable (Qualitative)                                      | Numerical Variable (Quantitative)                                      |
| ---------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| Definition | Represents **groups or categories** that cannot be measured numerically | Represents **quantitative values** that can be measured and calculated |
| Data Type  | Text or labels (sometimes coded as numbers)                             | Numbers (integers or decimals)                                         |
| Examples   | Gender (Male/Female), Eye color (Blue/Brown), Blood type (A/B/AB/O)     | Age (25, 30), Height (170 cm), Salary ($5000)                          |

### 2.1.1 Types of Categorical (Qualitative) Variables

| Type                     | Definition                                                                    | Examples                                                                   |
| ------------------------ | ----------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Nominal**              | Categories with **no specific order**                                         | Colors: Red, Blue, Green; Blood type: A, B, AB, O                          |
| **Ordinal**              | Categories with a **specific order**, but **uneven differences** between them | Ratings: Low, Medium, High; Education level: High School, Bachelor, Master |
| **Dichotomous / Binary** | Only **two categories**                                                       | Yes/No; Male/Female; Pass/Fail                                             |
|                          |                                                                               |                                                                            |

### 2.1.2 Types of Numerical (Quantitative) Variables

| Type         | Definition                                                 | Examples                             |
| ------------ | ---------------------------------------------------------- | ------------------------------------ |
| **Interval** | Continuous scale with **equal gaps**, but **no true zero** | Temperature in Celsius or Fahrenheit |
| **Ratio**    | Continuous scale with **equal gaps** and a **true zero**   | Height, Weight, Age, Salary          |
A **true zero** means that **the zero point on the scale represents the complete absence of the quantity being measured**.

0°C does **not** mean “no temperature,” just a point on the scale. So it has no true zeros.

---
## 2.2 The Four Scales of Measurement

| Scale        | Key Features                                                                                                                      | Notes / Examples                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Nominal**  | - Two or more categories<br>- No intrinsic order                                                                                  | Examples: Gender (Male/Female), Blood type (A/B/AB/O)                                    |
| **Ordinal**  | - Two or more categories<br>- Categories can be ordered/ranked<br>- Magnitude between values not equal                            | Examples: Education level (High School < Bachelor < Master), Ratings (Low, Medium, High) |
| **Interval** | - Measured on a continuous scale<br>- No absolute zero<br>- Differences between adjacent values are equal<br>- Ratios not defined | Examples: Temperature in Celsius or Fahrenheit                                           |
| **Ratio**    | - Interval variable with **absolute zero**<br>- Ratios between values are defined                                                 | Examples: Height, Weight, Age, Salary                                                    |
![](https://i.postimg.cc/QxXG5vrT/image.png)

---
# 3. Summary Statistics

used in **descriptive statistics**, for
- summarize a set of observations
- communication information simply and quickly 
---
## 3.1 Measure of Location (Central Tendency)

Tells us where the center or typical value of the data set lies

we use following to as main measurements in central tendency :
- Mean -> the average
- Median -> the middle value
- Mode -> the most frequent value

**Example:**

$2,4,6,8,10$
$Mean = (2+4+6+8+10)/5 = 6$
$Median = 6$
$Mode = None$

This tells us that the data is centered around 6.

### 3.1.1. Simple Arithmetic Mean

Notation:
- Mean of a population = $\mu$
- Sample mean (when sample observations are known)= $\bar{x}$
- Sample mean (when sample observation is unknown)=$\bar{X}$
- Count of Numbers in the population = N
- Count of numbers in the sample = n

Given the population values:
$$
\mu=\frac{1}{N}\sum_{i=1}^{N} X_i
$$
$$
\mu=\frac{(X_1 + X_2 + \cdots + X_N)}{N}
$$
Given a sample(values unknown):
$$
\bar{X}=\frac{1}{n}\sum_{i=1}^{n} X_i
$$
$$
\bar{X}=\frac{(X_1 + X_2 + \cdots + X_n)}{n}
$$
Given a sample(values known):
$$
\bar{x}=\frac{1}{n}\sum_{i=1}^{n} X_i
$$
$$
\bar{x}=\frac{(x_1 + x_2 + \cdots + x_n)}{n}
$$

### 3.1.2 Weighted Arithmetic Mean

Simple arithmetic gives equal importance to all the observations in a data set.

But when relative importance of the items in the distribution is not the same, we need to use this

Given $X_1,X_2,...,X_n$ are samples and $w_1,w_2,...,w_n$ are the weights corresponding to the observations  then,
$$
\bar{X_w}=\frac{\sum_{i=1}^nw_iX_i}{\sum_{i=1}^nw_i}
$$
$$
\bar{X_w}=\frac{w_1X_1+w_2X_2+...+w_nX_n}{w_1+w_2+...+w_n}
$$

Exercise:

A student’s final marks in Mathematics, English, Statistics and Computer are 92, 76, 95, and 80 respectively. If the respective credits received for these courses are 2,
1, 3 and 4, determine an appropriate average mark.

$$
\begin{aligned}
\text{Weighted Mean}
&= \frac{(92 \times 2) + (76 \times 1) + (95 \times 3) + (80 \times 4)}{2 + 1 + 3 + 4} \\
&= \frac{184 + 76 + 285 + 320}{10} \\
&= \frac{865}{10} \\
&= 86.5
\end{aligned}
$$

### 3.1.3 Combined/Composite Arithmetic Mean

Simple arithmetic means of two or more related groups can be combined into a composite mean

![](https://i.postimg.cc/bvkV6tCZ/image.png)

Given $\bar{X_1},\bar{X_2},...,\bar{X_k}$ are set of simple arithmetic means of $k$  related groups and $n_1,n_2,...,n_k$ are the respective sample size then,
$$
\bar{X_c}=\frac{\sum_{i=1}^kn_i\bar{X_i}}{\sum_{i=1}^kn_i}
$$
$$
\bar{X_c}=\frac{n_1\bar{X_1}+n_2\bar{X_2}+...+n_k\bar{X_k}}{n_1+n_2+...+n_k}
$$
Exercise:

There are three branches of a company, employing 100, 20, and 80 persons respectively. If the arithmetic means of the monthly salaries paid by the three
companies are Rs. 50000, 60000, and Rs. 80000 respectively, find the arithmetic mean
of the salaries of all the employees of the three companies.
$$
\begin{aligned}
\text{Combined Mean}
&= \frac{(100 \times 50000) + (20 \times 60000) + (80 \times 80000)}
{100 + 20 + 80} \\
&= \frac{5{,}000{,}000 + 1{,}200{,}000 + 6{,}400{,}000}{200} \\
&= \frac{12{,}600{,}000}{200} \\
&= 63{,}000
\end{aligned}
$$

### 3.1.4 Standard Geometric Mean ($G$)
![](https://i.postimg.cc/MpkHQn4W/image.png)
![](https://i.postimg.cc/xC7nV7D7/image.png)

Primarily used to determine overall growth rates or averages of percentages over time
This can only be used in positive numbers

Used for a set of$k$ positive observations $(X_1​,X_2​,...,X_k​)$:
$$
G = \left( \prod_{i=1}^{k} X_i \right)^{\frac{1}{k}}
$$
$$
G = \left( X_1 \times X_2 \times X_3 \times \cdots \times X_k \right)^{\frac{1}{k}}
$$
$$G = \sqrt[k]{x_1 \cdot x_2 \cdot \dots \cdot x_k}$$
_(This notation means you multiply all the numbers together and then take the $k^{th}$  root, where_ $k$ _is the count of numbers in the set)

Exercise: 

The economic growth rate of a country for the last three years is 4%, 2%, and 8%. What is the overall growth rate?

- Convert percentages to growth factors
$$
\text{Growth Factor} = 1 + \frac{\text{Rate}}{100}
$$
$$
X_1 = 1.04,\quad X_2 = 1.02,\quad X_3 = 1.08
$$

- Apply the geometric mean formula

$$
G = \left( 1.04 \times 1.02 \times 1.08 \right)^{\frac{1}{3}}
$$

- Multiply the values

$$
1.04 \times 1.02 \times 1.08 = 1.145664
$$

- Take the cube root

$$
G = (1.145664)^{\frac{1}{3}} \approx 1.046
$$

- Convert back to a percentage growth rate

$$
\text{Overall Growth Rate} = (1.046 - 1) \times 100\% = 4.6\%
$$

**The overall economic growth rate over the three years is approximately 4.6%**


### 3.1.5 Geometric Mean (An Alternative Version) $G_{Alt}$

This version is used when dealing with growth rates that may include **negative numbers** (as long as they are greater than -1)

If the values are $X_1, X_2, ..., X_k$, the alternative geometric mean is:

$$
G_{\text{Alt}} = \left( \prod_{i=1}^{k} (X_i + 1) \right)^{\frac{1}{k}} - 1
$$

Exercise: 

The economic growth rate of a country for the last three years is 4%, -2%,
and 8%. What is the overall growth rate?
Three yearly growth rates: 4%, -2%, 8%  

- Convert to growth factors:  
$$
\text{Growth Factor} = 1 + \frac{\text{Rate}}{100}
$$
$$
1.04, \ 0.98, \ 1.08
$$

- Multiply them:  
$$
1.04 \times 0.98 \times 1.08 = 1.100736
$$

- Take the cubic root:  
$$
GM = (1.100736)^{1/3} \approx 1.0321
$$

- Convert to percentage:  
$$
1.0321 - 1 = 0.0321\times 100\% \approx 3.21\%
$$

The **average yearly growth rate** is **3.21%**.


### 3.1.6 Harmonic Mean ($H$)
![](https://i.postimg.cc/8CQZ9m0Z/image.png)
![](https://i.postimg.cc/L51qcL7V/image.png)
![](https://i.postimg.cc/nz50x8Fw/image.png)

This is especially useful when dealing with **rates or units**, for example, calculating **average speed**.

For a set of $k$ observations $X_1, X_2, ..., X_k$, the harmonic mean is:

$$
H = \frac{k}{\frac{1}{X_1} + \frac{1}{X_2} + ... + \frac{1}{X_k}} = \frac{k}{\sum_{i=1}^{k} \frac{1}{X_i}}
$$

Where:  
- $k$ = number of observations  
- $X_i$ = each observation  

Exercise: 

The speeds of three deliveries (in km per hour) of a fast bowler are 60, 90, and 100. What is the average speed?

- Write the harmonic mean formula

$$
H = \frac{3}{\frac{1}{60} + \frac{1}{90} + \frac{1}{100}}
$$

- Find the reciprocals

$$
\frac{1}{60} = 0.01667
$$

$$
\frac{1}{90} = 0.01111
$$

$$
\frac{1}{100} = 0.01
$$

- Add the reciprocals

$$
0.01667 + 0.01111 + 0.01 = 0.03778
$$

 - Divide to find the harmonic mean

$$
H = \frac{3}{0.03778} \approx 79.4
$$
Final Answer

$$
\boxed{\text{Average speed} \approx 79.4 \text{ km/h}}
$$


### 3.1.7 Relationship with Other Means
For any set of positive numbers with **at least two different values**, the following inequality holds:

$$
H < G < \bar{X}
$$

Where:  
- $H$ = harmonic mean  
- $G$ = geometric mean  
- $\bar{X}$= arithmetic mean  

==This shows that the harmonic mean is always the **smallest** of the three averages.==

Exercise: 

Calculate the simple arithmetic mean, geometric mean, and harmonic mean
of 2, 4, 4, and 8.

$$
\bar{X} = \frac{\sum X}{k}
$$

$$
\bar{X} = \frac{2 + 4 + 4 + 8}{4} = \frac{18}{4} = 4.5
$$

$$
G = \left( \prod_{i=1}^{k} X_i \right)^{\frac{1}{k}}
$$

$$
2 \times 4 \times 4 \times 8 = 256
$$

$$
G = 256^{\frac{1}{4}} = 4
$$

$$
H = \frac{k}{\displaystyle \sum_{i=1}^{k} \frac{1}{X_i}}
$$

$$
\frac{1}{2} = 0.5,\quad
\frac{1}{4} = 0.25,\quad
\frac{1}{4} = 0.25,\quad
\frac{1}{8} = 0.125
$$

$$
0.5 + 0.25 + 0.25 + 0.125 = 1.125
$$

$$
H = \frac{4}{1.125} \approx 3.56
$$

- Conclusion

$$
\boxed{H = 3.56 \;<\; G = 4 \;<\; \bar{X} = 4.5}
$$

This confirms that the **harmonic mean is the smallest**, followed by the **geometric mean**, and the **arithmetic mean is the largest**.


### 3.1.8 Mode (Mo)
The **mode** is the value of a variable that occurs **most frequently** in a distribution.

**Types of Mode:**
- **Unimodal:** Only one mode in the series.  
- **Bimodal:** Two modes in the series.  
- **Trimodal:** Three modes in the series.  
- **Multimodal:** More than three modes in the series.

Exercise:

12 students in a class have the following shoe sizes. What is the mode?
$$
8, 9, 8, 7, 9, 8, 10, 8, 6, 8, 9, 10
$$

- Count the frequency of each value

| Shoe Size | Frequency |
|-----------|-----------|
| 6         | 1         |
| 7         | 1         |
| 8         | 5         |
| 9         | 3         |
| 10        | 2         |
- Identify the mode

	- The **mode** is the value with the **highest frequency**.  
	-  Here, **8 occurs 5 times**, which is more than any other value.


### 3.1.9 Median (Md)
The **median** is the middle value of a data set after arranging the observations in ascending order.

Let $n$  be the total number of observations.

- Case 1: When $n$ is ==odd==

$$
\text{Median position} = \frac{n + 1}{2}
$$

The median is the value at the  
$$
\frac{n + 1}{2}\text{th}
$$
position.

- Case 2: When $n$ is ==even==

The median lies between the two positions:

$$
\frac{n}{2}\text{th} \quad \text{and} \quad \left(\frac{n}{2} + 1\right)\text{th}
$$

The median is the **average** of the values at these two positions.

Examples:

Example 1: Odd Number of Observations

$$
3,\;5,\;7,\;9,\;11
$$
$$
\frac{n + 1}{2} = \frac{5 + 1}{2} = 3
$$

The 3rd value is:
$$
\boxed{\text{Median (Md)} = 7}
$$

Example 2: Even Number of Observations

$$
2,\;4,\;6,\;8
$$
$$
\frac{n}{2} = 2
\quad \text{and} \quad
\frac{n}{2} + 1 = 3
$$

$$
4 \text{ and } 6
$$
$$
\boxed{\text{Median (Md)} = \frac{4 + 6}{2} = 5}
$$

---
## 3.2 Quartiles ( $Q_i$, $i = 1, 2, 3$ )

**Quartiles** are values that divide an **ordered data set** into **four equal parts**.
Each part contains **25%** of the total number of observations.

- \( $Q_1$\): First quartile (lower quartile)
- \( $Q_2$ \): Second quartile (median)
- \( $Q_3$ \): Third quartile (upper quartile)

<img src="https://www.snexplores.org/wp-content/uploads/sites/3/2019/11/860-header-quartile-Presentation1.jpg" alt="" width="400" >

### Formula for the Location of Quartiles

Let \( $N$ \) be the total number of observations.
Location of the $i^{th}$ quartile

$$
L(Q_i) = \frac{i}{4}(N + 1)
$$  
$$
Q_i=\frac{i}{4}(N + 1)\text{th item}
$$

Exercise:

12 students in a class have the following weights (kg):
$$
68,\;59,\;81,\;47,\;92,\;48,\;56,\;83,\;65,\;67,\;79,\;77
$$
Find $Q_1, Q_2,$ and $Q_3$.

- Arrange the data in ascending order

$$
47,\;48,\;56,\;59,\;65,\;67,\;68,\;77,\;79,\;81,\;83,\;92
$$

-  Identify the number of observations

$$
N = 12
$$
#### First Quartile $Q_1$ 
- Location

$$
L(Q_1) = \frac{1}{4}(12 + 1) = \frac{13}{4} = 3.25
$$

This lies between the **3rd and 4th items**.

3rd item \( = 56 \)  
4th item \( = 59 \)

- Value of $Q_1$

$$
Q_2 = \frac{56 + 59}{2} = 56.75
$$

#### Second Quartile $Q_2$ — Median

- Location

$$
L(Q_2) = \frac{2}{4}(12 + 1) = \frac{13}{2} = 6.5
$$

This lies between the **6th and 7th items**.

6th item \( = 67 \)  
7th item \( = 68 \)

- Value of $Q_2$

$$
Q_2 = \frac{67 + 68}{2} = 67.5
$$

#### Third Quartile $Q_3$

- Location

$$
L(Q_3) = \frac{3}{4}(12 + 1) = \frac{39}{4} = 9.75
$$

This lies between the **9th and 10th items**.

9th item \( = 79 \)  
10th item \( = 81 \)

- Value of $Q_3$

$$
Q_3 = 79 + 0.75(81 - 79) = 80.5
$$

$$
\boxed{
Q_1 = 56.75,\quad
Q_2 = 67.5,\quad
Q_3 = 80.5
}
$$
#### Interpretation

- 25% of students weigh **less than 56.75 kg**
- 50% of students weigh **less than 67.5 kg**
- 75% of students weigh **less than 80.5 kg**
---
## Advantages and Disadvantages of Mean, Median, and Mode

| Measure | Advantages | Disadvantages |
|---------|------------|---------------|
| **Mean** | - Can be used with interval and ratio data<br>- Has useful statistical properties (e.g., for variance, standard deviation)<br>- Easy to understand and interpret | - Affected by extreme values (outliers)<br>- May not appear in the actual data<br>- Requires interval/ratio scale data<br>- Works best with symmetric distributions |
| **Median** | - Can be used with ordinal data<br>- Unaffected by extreme values<br>- Easy to calculate<br>- Symmetric data not required | - Restricted statistical uses<br>- May not appear in the actual data |
| **Mode** | - Can be used with nominal data<br>- Easy to calculate | - Restricted statistical uses<br>- Limited use for analysis |

---
## 3.3 Grouped Data Distributions 

When dealing with **large masses of raw data**, it is often convenient to **classify the data into groups or classes**.  

- **Frequency $f$ : The number of individuals or observations in each class.  
- **Grouped data distribution**: A table showing **classes** and their corresponding **frequencies**.

Example Table – Weights of 600 University Students

| Class   | Frequency $f_i$ |
| ------- | --------------- |
| 30 - 39 | 7               |
| 40 - 49 | 126             |
| 50 - 59 | 278             |
| 60 - 69 | 123             |
| 70 - 79 | 62              |
| 80 - 89 | 4               |

### 3.3.1 Class Interval and Class Limits

- **Class Interval**: A symbol defining a class (e.g., 40–49).  
- **Class Limits**: The smallest and largest numbers in a class:
  - **Lower Class Limit (LCL)**: Smaller number (e.g., 40)  
  - **Upper Class Limit (UCL)**: Larger number (e.g., 49)  
  
```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2026.2.5 - 23.03pm.drawing",
	"width": 350,
	"aspectRatio": 2.3333333333333335
}
```

- **Open Class Interval**: A class that has **no lower or upper limit** indicated.

### 3.3.2 Class Boundaries / True class limits
If measurements are recorded to the nearest unit:

- The interval 40–49 includes all values from **39.5 to 49.5**.  
	- **Lower Class Boundary (LCB)**: 39.5  
	- **Upper Class Boundary (UCB)**: 49.5  

| Class   | Frequency $f_i$ |
| ------- | --------------- |
| 30 - 39 | 7               |
| 40 - 49 | 126             |
| 50 - 59 | 278             |
| 60 - 69 | 123             |
| 70 - 79 | 62              |
| 80 - 89 | 4               |

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2026.2.5 - 23.10pm.drawing",
	"width": 350,
	"aspectRatio": 2.3333333333333335
}
```

| Classes with Class Boundaries | Frequency $f_i$ |
| ----------------------------- | --------------- |
| 29.5 - 39.5                   | 7               |
| 39.5 - 49.5                   | 126             |
| 49.5 - 59.5                   | 278             |
| 59.5 - 69.5                   | 123             |
| 69.5 - 79.5                   | 62              |
| 79.5 - 89.5                   | 4               |

### 3.3.3 Size (Width) of a Class Interval ($c_i$)

- **Class Width : Difference between UC==B== and LC==B==**.  

$$
\text{Class width} = \text{UCB} - \text{LCB}
$$

- If all intervals have the same width, the common width is \( C \).

### 3.3.4 Class Mark / Midpoint ($m_i$)

- The **midpoint** of a class interval, used as the **average of all observations** in the class (assuming even distribution).  

$$
m_i = \frac{\text{LCB + UCB}}{2} = \frac{\text{LCL + UCL}}{2}
$$

- Example: For class 40–49:

$$
m_i = \frac{40 + 49}{2} = 44.5
$$
 
Summary Table for Example Data

| Class | LCL | UCL | LCB  | UCB  | Width \( C \) | Midpoint \( $m_i$ \) | Frequency \( $f_i$ \) |
| ----- | --- | --- | ---- | ---- | ------------- | -------------------- | --------------------- |
| 30–39 | 30  | 39  | 29.5 | 39.5 | 10            | 34.5                 | 7                     |
| 40–49 | 40  | 49  | 39.5 | 49.5 | 10            | 44.5                 | 126                   |
| 50–59 | 50  | 59  | 49.5 | 59.5 | 10            | 54.5                 | 278                   |
| 60–69 | 60  | 69  | 59.5 | 69.5 | 10            | 64.5                 | 123                   |
| 70–79 | 70  | 79  | 69.5 | 79.5 | 10            | 74.5                 | 62                    |
| 80–89 | 80  | 89  | 79.5 | 89.5 | 10            | 84.5                 | 4                     |

---
## 3.4 Measures of Central Tendency for Grouped Data
For grouped data, we calculate **Mean, Mode, Median, Quartiles, Deciles, and Percentiles** using class midpoints, class frequencies, and cumulative frequencies.

### 3.4.1 Mean ( $\bar{X}$ )

Let \( $m_1, m_2, \dots, m_k$ \) be the **midpoints** of \( $k$ \) class intervals,  
and \( $f_1, f_2, \dots, f_k$ \) be their **frequencies**.  

The **mean** is:

$$
\bar{X} = \frac{\sum_{i=1}^{k} f_i m_i}{\sum_{i=1}^{k} f_i} = \frac{f_1 m_1 + f_2 m_2 + \dots + f_k m_k}{n}
$$

**Example Table:**

| Class | Frequency \( $f_i$\) | Midpoint \( $m_i$ \) | $f_i m_i$ |
| ----- | -------------------- | -------------------- | --------- |
| 30–39 | 7                    | 34.5                 | 241.5     |
| 40–49 | 126                  | 44.5                 | 5607      |
| 50–59 | 278                  | 54.5                 | 15151     |
| 60–69 | 123                  | 64.5                 | 7923.5    |
| 70–79 | 62                   | 74.5                 | 4619      |
| 80–89 | 4                    | 84.5                 | 338       |

$$
\bar{X} = \frac{\text{Sum of } f_i m_i}{\text{Sum of } f_i} = \frac{33779}{600} \approx 56.3
$$

### 3.4.2 Mode ($Mo$) – Modal Class Method

The **mode** is the value that occurs **most frequently**. For grouped data, the **modal class** has the highest frequency.  

$$
Mo = L_{Mo} + \frac{\Delta_1}{\Delta_1 + \Delta_2} \cdot C_{Mo}
$$
$$
Mo = L_{Mo} + \frac{f_1 - f_0}{(f_1 - f_0) + (f_1 - f_2)} \cdot C_{Mo}
$$

Where:

- \( $L_{Mo}$ \) = **Lower class boundary of modal class**  
- \( $f_1$ \) = Frequency of modal class  
- \( $f_0$ \) = Frequency of class **preceding** modal class  
- \( $f_2$ \) = Frequency of class **succeeding** modal class  
- \( $\Delta_1 = f_1 - f_0$ \), \( $\Delta_2 = f_1 - f_2$ \)  
- \( $C_{Mo}$ \) = Class width of modal class

**Example Table:**

| Class | Frequency \( $f_i$ \) |
| ----- | --------------------- |
| 30–39 | 7                     |
| 40–49 | 126                   |
| 50–59 | 278 **(modal)**       |
| 60–69 | 123                   |
| 70–79 | 62                    |
| 80–89 | 4                     |

- The **modal class** = 50–59 (highest frequency = 278)  
-  Identify Required Values

| Symbol         | Value                                       |
| -------------- | ------------------------------------------- |
| \( $L_{Mo}$ \) | 49.5 (lower boundary of modal class)        |
| \( $f_1$ \)    | 278 (frequency of modal class)              |
| \( $f_0$ \)    | 126 (frequency of class before modal class) |
| \( $f_2$ \)    | 123 (frequency of class after modal class)  |
| \( $C_{Mo}$ \) | 10 (class width)                            |
-  Use the Modal Class Formula

$$
Mo = L_{Mo} + \frac{f_1 - f_0}{(f_1 - f_0) + (f_1 - f_2)} \cdot C
$$
Substitute the values:

$$
Mo = 49.5 + \frac{278 - 126}{(278 - 126) + (278 - 123)} \cdot 10
$$
-  Simplify

$$
Mo = 49.5 + \frac{152}{152 + 155} \cdot 10
$$

$$
Mo = 49.5 + \frac{152}{307} \cdot 10
$$

$$
Mo \approx 49.5 + 4.95
$$

$$
\boxed{Mo \approx 54.45 \text{ kg}}
$$

### 3.4.3 Quartiles ( $Q_i, i = 1, 2, 3$ )

1. Find **cumulative frequencies**.  
2. Use the formula for the **$i_{th}$ quartile**:

$$
Q_i = L_{Q_i} + \frac{i \times\frac{ N}{4} - F_{Q_i}}{f_{Q_i}} \cdot C_{Q_i}
$$

Where:

- \( $L_{Q_i}$ \) = Lower class boundary of $i_{th}$ quartile class  
- \( $F_{Q_i}$ \) = Cumulative frequency **before** the quartile class  
- \( $f_{Q_i}$ \) = Frequency of quartile class  
- \( $C_{Q_i}$ \) = Class width of quartile class  
- \( $N$ \) = Total frequency  

**Example Table:**

| Class | Frequency \( $f_i$ \) |
| ----- | --------------------- |
| 30–39 | 7                     |
| 40–49 | 126                   |
| 50–59 | 278                   |
| 60–69 | 123                   |
| 70–79 | 62                    |
| 80–89 | 4                     |
- Calculate Cumulative Frequency ($CF$)

| Class | \( $f_i$ \) | Cumulative Frequency ($CF$) |
| ----- | ----------- | --------------------------- |
| 30–39 | 7           | 7                           |
| 40–49 | 126         | 133                         |
| 50–59 | 278         | 411                         |
| 60–69 | 123         | 534                         |
| 70–79 | 62          | 596                         |
| 80–89 | 4           | 600                         |
- Calculate \( $Q_1$\) (First Quartile)

	- \( $i = 1, N = 600, \frac{N}{4} = 150$ \)  
	- Locate quartile class: **50–59** (CF before = 133, f = 278, LCB = 49.5, C = 10)

$$
Q_1 = 49.5 + \frac{150 - 133}{278} \cdot 10
$$

$$
Q_1 = 49.5 + \frac{17}{278} \cdot 10
$$

$$
Q_1 \approx 49.5 + 0.61
$$

$$
\boxed{Q_1 \approx 50.11 \text{ kg}}
$$
- Calculate \( $Q_2$\) (Median)

	- \( $i = 2, \frac{2N}{4} = 300$ \)  
	- Quartile class = **50–59** (CF before = 133, f = 278, LCB = 49.5, C = 10)

$$
Q_2 = 49.5 + \frac{300 - 133}{278} \cdot 10
$$

$$
Q_2 = 49.5 + \frac{167}{278} \cdot 10
$$

$$
Q_2 \approx 49.5 + 6.01
$$

$$
\boxed{Q_2 \approx 55.51 \text{ kg}}
$$
- Calculate \( $Q_3$ \) (Third Quartile)

	- \( $i = 3, \frac{3N}{4} = 450$ \)  
	- Quartile class = **60–69** (CF before = 411, f = 123, LCB = 59.5, C = 10)

$$
Q_3 = 59.5 + \frac{450 - 411}{123} \cdot 10
$$

$$
Q_3 = 59.5 + \frac{39}{123} \cdot 10
$$

$$
Q_3 \approx 59.5 + 3.17
$$

$$
\boxed{Q_3 \approx 62.67 \text{ kg}}
$$

| Quartile | Value (kg) |
| -------- | ---------- |
| $Q_1$    | 50.11      |
| $Q_2$    | 55.51      |
| $Q_3$    | 62.67      |

- 25% of students weigh **less than 50.11 kg**  
- 50% of students weigh **less than 55.51 kg**  
- 75% of students weigh **less than 62.67 kg** 

### 3.4.4 Deciles ( $D_i, i = 1, 2, \dots, 9$ )
**Deciles** are measures of position that divide a data set into **10 equal parts**.

- Each part contains **10% of the total observations**
- There are **9 deciles**: \( $D_1, D_2, \dots, D_9$ \)

<img src="https://matematix.org/wp-content/uploads/que-son-los-deciles-y-cual-es-su-importancia-en-estadistica.png" alt="A description of the image" width="500" >

Meaning of Each Decile

| Decile      | Interpretation                                |
| ----------- | --------------------------------------------- |
| \( $D_1$ \) | 10% of data lie **below** this value          |
| \( $D_2$ \) | 20% of data lie below this value              |
| \( $D_3$ \) | 30% of data lie below this value              |
| \( $D_4$\)  | 40% of data lie below this value              |
| \( $D_5$ \) | 50% of data lie below this value (**Median**) |
| \( $D_6$ \) | 60% of data lie below this value              |
| \( $D_7$ \) | 70% of data lie below this value              |
| \( $D_8$ \) | 80% of data lie below this value              |
| \( $D_9$ \) | 90% of data lie below this value              |


1. Find **cumulative frequencies**.  
2. Use the formula for the **$i_{th}$ decile**:

$$
D_i = L_{D_i} + \frac{i \times\frac{ N}{10} - F_{D_i}}{f_{D_i}} \cdot C_{D_i}
$$

Where:

- \( $L_{D_i}$ \) = Lower class boundary of $i_{th}$ decile class  
- \( $F_{D_i}$ \) = Cumulative frequency **before** the decile class  
- \( $f_{D_i}$ \) = Frequency of decile class  
- \( $C_{D_i}$ \) = Class width of decile class  

**Example Table:**

| Class | Frequency \( $f_i$ \) | Cumulative Frequency ($CF$) |
| ----- | --------------------- | --------------------------- |
| 30–39 | 7                     | 7                           |
| 40–49 | 126                   | 133                         |
| 50–59 | 278                   | 411                         |
| 60–69 | 123                   | 534                         |
| 70–79 | 62                    | 596                         |
| 80–89 | 4                     | 600                         |

Total number of observations:

$$
N = 600
$$ 
**Example – Find the 4th Decile ($D_4$ )**

- Locate the Decile Position

$$
\frac{4N}{10} = \frac{4 \times 600}{10} = 240
$$

The value **240** lies in the class **50–59**, since:

- CF before = 133  
- CF of class = 411  

So, the **decile class** is **50–59**.

- Identify Required Values

| Symbol          | Value |
| --------------- | ----- |
| \( $L_{D_4}$ \) | 49.5  |
| \( $F_{D_4}$ \) | 133   |
| \( f$_{D_4}$ \) | 278   |
| \( $C_{D_4}$ \) | 10    |

- Substitute into the Formula

$$
D_4 = 49.5 + \frac{240 - 133}{278} \cdot 10
$$
- Simplify

$$
D_4 = 49.5 + \frac{107}{278} \cdot 10
$$

$$
D_4 \approx 49.5 + 3.85
$$

$$
\boxed{D_4 \approx 53.35 \text{ kg}}
$$

### 3.4.5 Percentiles ($P_i, i = 1, 2, \dots, 99$)

**Percentiles** are measures of position that divide a data set into **100 equal parts**.

- Each part contains **1% of the total observations**
- There are **99 percentiles**: \( $P_1, P_2, \dots, P_{99}$ \)

Meaning of Percentiles

| Percentile     | Interpretation                                |
| -------------- | --------------------------------------------- |
| \( $P_{10}$ \) | 10% of data lie **below** this value          |
| \( $P_{25}$ \) | 25% of data lie below this value (**$Q_1$ **) |
| \( $P_{50}$ \) | 50% of data lie below this value (**Median**) |
| \( $P_{75}$ \) | 75% of data lie below this value (**$Q_3$ **) |
| \( $P_{90}$ \) | 90% of data lie below this value              |

- Relation to Other Measures

$$
P_{25} = Q_1
$$

$$
P_{50} = Q_2 = D_5 = \text{Median}
$$

$$
P_{75} = Q_3
$$
When Percentiles Are Used

- To compare **individual positions** in large datasets  
- Widely used in **exam results, income distributions, and rankings**  
- Useful when **data size is large and grouped**

1. Find **cumulative frequencies**.  
2. Use the formula for the **$i_{th}$ percentile**:

$$
P_i = L_{P_i} + \frac{i \times\frac{ N}{100} - F_{P_i}}{f_{P_i}} \cdot C_{P_i}
$$

Where:

- \( $L_{P_i}$ \) = Lower class boundary of $i_{th}$ percentile class  
- \( $F_{P_i}$ \) = Cumulative frequency **before** the percentile class  
- \( $f_{P_i}$ \) = Frequency of percentile class  
- \( $C_{P_i}$ \) = Class width of percentile class  

**Example Table:**

| Class (kg) | Frequency \( $f_i$ \) | Cumulative Frequency ($CF$) |
| ---------- | --------------------- | --------------------------- |
| 30–39      | 7                     | 7                           |
| 40–49      | 126                   | 133                         |
| 50–59      | 278                   | 411                         |
| 60–69      | 123                   | 534                         |
| 70–79      | 62                    | 596                         |
| 80–89      | 4                     | 600                         |

Total number of observations:

$$
N = 600
$$

**Example: Find the 75th Percentile ($P_{75}$ )**

- Locate the Percentile Position

$$
\frac{75N}{100} = \frac{75 \times 600}{100} = 450
$$

The value **450** lies in the class **60–69**, since:

- CF before = 411  
- CF of class = 534  

So, the **percentile class** is **60–69**.

- Identify Required Values

| Symbol             | Value |
| ------------------ | ----- |
| \( $L_{P_{75}}$ \) | 59.5  |
| \( $F_{P_{75}}$ \) | 411   |
| \( $f_{P_{75}}$ \) | 123   |
| \( $C_{P_{75}}$ \) | 10    |

- Substitute into the Formula

$$
P_{75} = 59.5 + \frac{450 - 411}{123} \cdot 10
$$
- Simplify

$$
P_{75} = 59.5 + \frac{39}{123} \cdot 10
$$

$$
P_{75} \approx 59.5 + 3.17
$$

$$
\boxed{P_{75} \approx 62.67 \text{ kg}}
$$
---
## 3.5 Measures of Dispersion

Measures of dispersion describe **how spread out** the data values are around a central value.
They help us understand **variability, consistency, and stability** of data.

**Common Measures of Dispersion**
- [[#3.5.1 Range]] 
- [[#3.5.2 Interquartile Range (IQR)]]  
- [[#3.5.3 Semi-Interquartile Range (SIQR)]]  
- [[#3.5.4 Mean Deviation (MD)]]  
- [[#3.5.5 Mean Absolute Deviation (MAD)]]  
- [[#3.5.6 Median Absolute Deviation]]  
- [[#3.5.7 Variance]]
- [[#3.5.8 Standard Deviation]] 
- [[#3.5.10 Variance for Grouped Data]] 

### 3.5.1 Range
The **range** is the simplest measure of dispersion.  
It shows the difference between the **largest** and **smallest** values.

$$
R = \text{Maximum} - \text{Minimum}
$$

**Example:**

Data:
$$
4,\;6,\;9,\;12,\;15
$$

$$
R = 15 - 4 = 11
$$

### 3.5.2 Interquartile Range (IQR)
The **interquartile range** measures the spread of the **middle 50%** of data.

$$
IQR = Q_3 - Q_1
$$

**Example:**

Given:
$$
Q_1 = 20,\quad Q_3 = 50
$$

$$
IQR = 50 - 20 = 30
$$

### 3.5.3 Semi-Interquartile Range (SIQR)
The **semi-interquartile range** is half of the interquartile range.

$$
SIQR = \frac{1}{2}(Q_3 - Q_1)
$$

**Example:**

$$
SIQR = \frac{1}{2}(50 - 20) = 15
$$


### 3.5.4 Mean Deviation (MD)
Mean deviation measures the **average deviation of values from the mean**.

$$
MD = \frac{1}{n} \sum_{i=1}^{n} (X_i - \bar{X})
$$

⚠️ Positive and negative deviations may cancel out.

**Example:**

Given Data

$$
2,\;4,\;6
$$
- Find the Mean

$$
\bar{X} = \frac{2 + 4 + 6}{3} = 4
$$
- Find Deviations from the Mean

| \($X_i$\) | \($X_i - \bar{X}$\) |
| --------- | ------------------- |
| 2         | \(2 - 4 = -2\)      |
| 4         | \(4 - 4 = 0\)       |
| 6         | \(6 - 4 = +2\)      |
- Apply the Mean Deviation Formula

$$
MD = \frac{1}{n} \sum (X_i - \bar{X})
$$

$$
MD = \frac{-2 + 0 + 2}{3}
$$

$$
MD = \frac{0}{3} = 0
$$

⚠️ Important Observation

Although the data values are **spread out**, the mean deviation is **zero** because:

- Positive deviations cancel negative deviations  
- This is why **mean deviation is rarely used in practice**

**To avoid this cancellation problem, we use:**

- **Mean Absolute Deviation (MAD)**
- **Variance**
- **Standard Deviation**


### 3.5.5 Mean Absolute Deviation (MAD)
Mean absolute deviation removes the sign by using **absolute values**.

$$
MAD = \frac{1}{n} \sum_{i=1}^{n} |X_i - \bar{X}|
$$

**Example:**

Data:
$$
2,\;4,\;6
$$

Mean:
$$
\bar{X} = 4
$$

$$
MAD = \frac{|2-4| + |4-4| + |6-4|}{3}
$$

$$
MAD = \frac{2 + 0 + 2}{3} = 1.33
$$


### 3.5.6 Median Absolute Deviation
This measure calculates deviation from the **median**.

$$
MAD_{median} = \frac{1}{n} \sum_{i=1}^{n} |X_i - MO|
$$

Used when data contains **outliers**.

**Example:**

data:

$$
2,\;4,\;5,\;6,\;100
$$
- Arrange the Data

$$
2,\;4,\;5,\;6,\;100
$$
-  Find the Median

The middle value is:

$$
MO = 5
$$
-  Find Absolute Deviations from the Median

| $X_i$ |    Deviation from Median     |
| :---: | :--------------------------: |
|   2   |  $\lvert 2 - 5 \rvert = 3$   |
|   4   |  $\lvert 4 - 5 \rvert = 1$   |
|   5   |  $\lvert 5 - 5 \rvert = 0$   |
|   6   |  $\lvert 6 - 5 \rvert = 1$   |
|  100  | $\lvert 100 - 5 \rvert = 95$ |

- Apply the Formula

$$
MAD_{median} = \frac{3 + 1 + 0 + 1 + 95}{5}
$$

$$
MAD_{median} = \frac{100}{5} = 20
$$



### 3.5.7 Variance
Variance measures **how far data values spread around the mean**.

#### Population Variance
Let \( $X_1, X_2, \dots, X_N$ \) be a population.

$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (X_i - \mu)^2
$$

Alternative form:
$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (X_i - \mu)^2
$$
$(X_i - \mu)^2 = X_i^2 - 2X_i\mu + \mu^2$
$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} \left( X_i^2 - 2X_i\mu + \mu^2 \right)
$$
$$
\sigma^2 = \frac{1}{N}
\left(
\sum_{i=1}^{N} X_i^2
- 2\mu \sum_{i=1}^{N} X_i
+ \sum_{i=1}^{N} \mu^2
\right)
$$
$\sum_{i=1}^{N} X_i = N\mu$

$\sum_{i=1}^{N} \mu^2 = N\mu^2$

$$
\sigma^2 = \frac{1}{N}
\left(
\sum_{i=1}^{N} X_i^2
- 2\mu(N\mu)
+ N\mu^2
\right)
$$
$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} X_i^2
- 2\mu^2
+ \mu^2
$$
$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{N} X_i^2 - \mu^2
$$

#### Sample Variance

For sample data:

##### When values are unknown

$$
S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (X_i - \bar{X})^2
$$

##### When values are known

$$
s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$
Alternative form:
$$
S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (X_i - \bar{X})^2
$$

$(X_i - \bar{X})^2 = X_i^2 - 2X_i\bar{X} + \bar{X}^2$

$$
\sum_{i=1}^{n} (X_i - \bar{X})^2
= \sum_{i=1}^{n} X_i^2
- 2\bar{X}\sum_{i=1}^{n} X_i
+ \sum_{i=1}^{n} \bar{X}^2
$$

$\sum_{i=1}^{n} X_i = n\bar{X}$

$\sum_{i=1}^{n} \bar{X}^2 = n\bar{X}^2$
$$
\sum_{i=1}^{n} (X_i - \bar{X})^2
= \sum_{i=1}^{n} X_i^2
- 2\bar{X}(n\bar{X})
+ n\bar{X}^2
$$
$$
= \sum_{i=1}^{n} X_i^2 - 2n\bar{X}^2 + n\bar{X}^2
$$
$$
\sum_{i=1}^{n} (X_i - \bar{X})^2
= \sum_{i=1}^{n} X_i^2 - n\bar{X}^2
$$
$$
S^2 = \frac{1}{n-1}\left(\sum_{i=1}^{n} X_i^2 - n\bar{X}^2\right)
$$

### 3.5.8 Standard Deviation
The **standard deviation** is the square root of variance.
It has the **same unit as the original data**.
It describes how far data values typically spread from the **mean**.
Sensitive to **extreme values (outliers)**

$$
\text{Standard Deviation} = \sqrt{\text{Variance}}
$$
#### Population Standard Deviation
$$
\sigma = \sqrt{\sigma^2}
$$
#### Sample Standard Deviation
##### When values are unknown
$$
S = \sqrt{S^2}
$$
##### When values are known
$$
s = \sqrt{s^2}
$$

**Example:**

If:
$$
s^2 = 16
$$

Then:
$$
s = \sqrt{16} = 4
$$
#### Interpretation
- **Small standard deviation** → data values are **close to the mean**
- **Large standard deviation** → data values are **widely spread**

### 3.5.9 Coefficient of Variation (CV)
The coefficient of variation compares **relative variability** between datasets.

$$
CV = \frac{\sigma}{\mu} \times 100\%
$$

$$
CV = \frac{S}{\bar{X}} \times 100\%
$$

#### Interpretation
- **Higher CV** → More variability, less consistency , less stability 
- **Lower CV** → Less variability, more consistency , more stability 

**Example:**

$$
\bar{X} = 50,\quad S = 5
$$

$$
CV = \frac{5}{50} \times 100 = 10\%
$$


### 3.5.10 Variance for Grouped Data
For grouped data with class midpoints \( $m_i$ \) and frequencies \( $f_i$ \):

$$
S^2 = \frac{1}{n-1} \sum_{i=1}^{k} f_i (m_i - \bar{X})^2
$$

Where:

$$
n = \sum_{i=1}^{k} f_i
$$

**Example :**

| Class Interval | $f_i$ | $m_i$ |
| -------------- | ----- | ----- |
| 10–19          | 5     | 14.5  |
| 20–29          | 8     | 24.5  |
| 30–39          | 7     | 34.5  |

- Total Frequency

$$
n = 5 + 8 + 7 = 20
$$
- Mean of Grouped Data

$$
\bar{X} = \frac{\sum f_i m_i}{\sum f_i}
$$

| $f_i$ | $m_i$ | $f_i m_i$ |
| ----- | ----- | --------- |
| 5     | 14.5  | 72.5      |
| 8     | 24.5  | 196       |
| 7     | 34.5  | 241.5     |

$$
\sum f_i m_i = 510
$$

$$
\bar{X} = \frac{510}{20} = 25.5
$$
- Compute $(m_i - \bar{X})^2$

| $m_i$ | $m_i - \bar{X}$ | $(m_i - \bar{X})^2$ |
| ----- | --------------- | ------------------- |
| 14.5  | \( -11 \)       | 121                 |
| 24.5  | \( -1 \)        | 1                   |
| 34.5  | \( 9 \)         | 81                  |

- Multiply by Frequencies

| $f_i$ | $(m_i - \bar{X})^2$ | $f_i (m_i - \bar{X})^2$ |
| ----- | ------------------- | ----------------------- |
| 5     | 121                 | 605                     |
| 8     | 1                   | 8                       |
| 7     | 81                  | 567                     |

$$
\sum f_i (m_i - \bar{X})^2 = 1180
$$

- Variance

$$
S^2 = \frac{1}{20 - 1} \times 1180
$$

$$
S^2 = \frac{1180}{19}
$$

$$
\boxed{S^2 \approx 62.11}
$$






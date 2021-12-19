## PROJECT 3: Electric Motor Temperature

> ### TASK: Study Polynomial Linear Regression
> 

### Project goals and objectives

#### Project goal

- Studying **Polynomial Linear Regression**

#### Project objectives

1. Explore and prepare data 
2. Build polynomial linear regression model


### Dataset

[Electric Motor Temperature](https://www.kaggle.com/wkirgsn/electric-motor-temperature)

**DATASET INFORMATION:**

**Context**
The data set comprises several sensor data collected from a permanent magnet synchronous motor (PMSM) deployed on a test bench. The PMSM represents a german OEM's prototype model. Test bench measurements were collected by the LEA department at Paderborn University.

**Content**
All recordings are sampled at 2 Hz. The data set consists of multiple measurement sessions, which can be distinguished from each other by column "profile_id". A measurement session can be between one and six hours long.

The motor is excited by hand-designed driving cycles denoting a reference motor speed and a reference torque.
Currents in d/q-coordinates (columns "id" and iq") and voltages in d/q-coordinates (columns "ud" and "uq") are a result of a standard control strategy trying to follow the reference speed and torque.
Columns "motor_speed" and "torque" are the resulting quantities achieved by that strategy, derived from set currents and voltages.

Most driving cycles denote random walks in the speed-torque-plane in order to imitate real world driving cycles to a more accurate degree than constant excitations and ramp-ups and -downs would.



### Results

1. [x] [**Polynomial Linear Regression**](https://github.com/rttrif/TrifonovRS.Machine_Learning_Portfolio.github.io/blob/main/REGRESSION/Project%203:%20Electric%20Motor%20Temperature/Polynomial_Regression.ipynb)



### References

1. [Polynomial regression](https://en.wikipedia.org/wiki/Polynomial_regression)
2. [Machine Learning: Polynomial Regression with Python](https://towardsdatascience.com/machine-learning-polynomial-regression-with-python-5328e4e8a386)
3. [All you need to know about Polynomial Regression](https://www.analyticsvidhya.com/blog/2021/07/all-you-need-to-know-about-polynomial-regression/)
4. [Understanding Polynomial Regression](https://medium.com/analytics-vidhya/understanding-polynomial-regression-5ac25b970e18)
5. [Introduction to Polynomial Regression Analysis](https://serokell.io/blog/polynomial-regression-analysis)


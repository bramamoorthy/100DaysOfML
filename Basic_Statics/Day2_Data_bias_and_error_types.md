# Basic Statistics for machine learning 2: Bias and Error in Data

Every dataset is distinct, data cames from distinct sources and services, but all data sources have errors and we need to know what this ones suppose to our analysis and statistical models.

## Random and Systematica error 

### Random Error

Random error can be explained as the error that is generated in the process of adquiring the data, as an example, if you weight yourself 10 times in a row you will observe some variation in the results.

There're some requirements to classify this error, let's explain them:

1. The sum of all the error scores tends to cancel over number ob mesurements.

2. It's unrelated to the true score.

3. The error component of one measurement is unrelated to the error component of any other measurement.


For instance, in a series of measurements, a pattern of the size of the error component should not be increasing over time, so later measurements have larger errors, or errors in a consistent direction, relative to earlier measurements.

### Systematic Error

In contrast, systematicall error has an observed pattern that can be measured, and the cause of this pattern can be analized and solved.

An example of systematic error can be measures coming from a not balanced temperature sensor always have 5 degrees more than the real value.

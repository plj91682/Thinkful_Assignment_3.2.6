# Thinkful_Assignment_3.2.6
(Prep Course) Unit 3, Lesson 2, Assignment 6

### Drill - Exercises in Bayes' Rule

Calculate the probability that the test will:

* Be positive
* Correctly diagnose a sufferer of Thripshaw's
* Correctly identify a non-sufferer of Thripshaw's
* Misclassify the person

__Given Facts__

-  98% -> (for sufferers) The test Accuracy Rate: The test confirms you *__Do Have__* the condition
-  02% -> (for sufferers) The test Error Rate: The test *__incorrectly__* confirms you don't have the condition
-  10% -> (for non-sufferers) The test Error Rate: the test *__incorrectly__* confirms you Do Have the condition 
-  90% -> (for non-sufferers) The test Accuracy Rate: the test confirms you *__Don't Have__* the condition
- 0.5% -> The rate the general population has the condition
- 99.5% -> The rate the general population won't have the condition

__Bayes Rule__

P(A|B) = (Pr(B|A)Pr(A)) / (Pr(B|A)Pr(A)+Pr(B|~A)Pr(~A))

1. Be positive (The probabilty the test identifies someone has the condition given a disease rate of 0.5%)
     ```
     A = (Actually Positive) People who have it that test-positive: (0.005)(0.98) = 0.0049
     A'= (False Positive) People who don't have it but test-positive: (0.995)(0.1) = 0.0995
     
     actual_positive + false_positive: 0.0049 + 0.0995 = 0.1044
     ```
     __The rate the test identifies someone with the disease is 10.44%__
     
2. Correctly diagnose a sufferer of Thripshaw's
     ```
     This was given in the scenario prompt
     ```
     __98% -> (for sufferers) The test Accuracy Rate: The test confirms you *__Do Have__* the condition__
3. Correctly identify a non-sufferer of Thripshaw's
4. Misclassify the person


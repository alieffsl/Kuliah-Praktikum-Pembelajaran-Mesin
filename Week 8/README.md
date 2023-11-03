## Practical Assignment

### Task 1: Fuzzy Logic Model using Mamdani Method

Implement the Fuzzy Logic model using the Mamdani method based on the example provided in the module. Create a flowchart based on your understanding and analyze the results.

### Task 2: Modification of Example 1

Budi, a diligent student majoring in Robotics and Artificial Intelligence, is taking a Machine Learning course this semester. He scored 85 in assignments, 80 in the midterm exam (UTS), and 40 in the final exam (UAS). Budi performed poorly in the final exam due to oversleeping and forgetting to study. He is concerned about his overall grade, whether it is low, medium, or high.

#### a. Calculating Budi's Final Grade

Help Budi calculate his final grade using the example 1 approach in the module. In this modified scenario, the rules are adjusted as follows:
- Convert Membership Values: Low = 1, Middle = 2, High = 3
- Calculate using: Total converted values / 3
- If the result falls within:
  - Less than 1.5: Low
  - Between 1.5 and 2.5: Middle
  - Greater than or equal to 2.5: High

#### b. Handling Multiple Assignments

In reality, Budi has three assignments with scores 80, 85, and 75. Adjust the values by calculating the average before applying the fuzzy rules from example 1.

#### c. Converting Fuzzy Results to Academic Grades

Convert the fuzzy output to academic grades: 
- "Low" corresponds to "C"
- "Middle" corresponds to "B"
- "High" corresponds to "A"

#### d. Predicting Results for Budi's Friends

Predict the final grades for Budi's friends based on their scores:

| Name   | Assignments | UTS | UAS | Final Grade |
| ------ | ----------- | --- | --- | ----------- |
| Jasmine| 70          | 80  | 75  | -           |
| Rafik  | 90          | 80  | 77  | -           |
| Mutia  | 50          | 55  | 60  | -           |
| Patrik | 10          | 0   | 90  | -           |
| Fajar  | 65          | 35  | 100 | -           |

### Task 2 Analysis:

The implemented fuzzy logic model provides a systematic approach to evaluating students' performance based on their assignment scores, midterm exam results, and final exam results. By converting numerical scores into fuzzy values and applying predefined rules, the system effectively categorizes students into low, medium, and high achievement levels.

For Budi, his average assignment score and exam results were analyzed to determine his overall performance. The fuzzy logic system successfully converted the scores into linguistic variables and mapped them to appropriate academic grades (C, B, or A) for easy interpretation.

For Budi's friends, their scores were input into the system, and the fuzzy logic rules were applied to predict their final grades. This predictive analysis enables proactive intervention and support for students who may need additional assistance based on their performance. The fuzzy logic model serves as a valuable tool for educators and students alike, providing a clear understanding of academic achievements and areas that require improvement.

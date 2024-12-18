# README

About the Project:
We will be using a dataset of biological metrics of three different species of Penguins found in the Palmer Archipelago of Antartica.

The main question this work tries to explore is whether AI models can be useful for ecological studies and research on animals and wildlife, especially those found in remote regions of the planet. We want to explore whether AI can be used as a tool for further enhancing oru understanding of these species and using existing data to answer biological questions that are not easy to answer purely based on manual studies.

We plan to explore four different ML tasks in this project.

Species classification:

Objective 1: Build a model to classify penguin species (Adelie, Gentoo, Chinstrap) based on features like bill length, bill depth, flipper length, and body mass.
Applications: Wildlife monitoring, ecological studies, conservation efforts.
Sex classification

Objective 2: Predict the sex of a penguin using the dataset's features.
Applications: Understanding population demographics, breeding patterns.
Bill Length Prediction

Objective 3: Predict the bill length using other features.
Applications: To study the feeding habits of penguins and identify ways to preserve penguin communities by improving access to food.
Flipper length prediction

Objective 4: Predict the flipper length based on other features.
Applications: Understanding the swimming capabilities of Penguins and their adaptations to changing ocean environments.
The first two are classification tasks and the last two are regression tasks. We plan to test several classication and regression models covered in the course and carry out a comprehensive comparative analysis of the different models. Through this small-scale study, we want to identify specific domains where machine learning has the potential to advance ecological research, and also identify potential pitfalls and drawbacks (if any) of using AI in this context.

About the Dataset:
Source: https://www.kaggle.com/datasets/samybaladram/palmers-penguin-dataset-extended

This dataset provides detailed measurements for three species of penguins (Adélie, Chinstrap, and Gentoo) observed in the Palmer Archipelago, Antarctica. This dataset provides a deeper insight into penguin biology and ecology, making it perfect for more sophisticated analysis. It is suitable for educational purposes, ecological studies, and advanced machine learning algorithms. It includes the following features:

Species: Species of the penguin (Adelie, Chinstrap, Gentoo)
Island: Island where the penguin was found (Biscoe, Dream, Torgensen)
Sex: Gender of the penguin (Male, Female)
Diet: Primary diet of the penguin (Fish, Krill, Squid)
Year: Year the data was collected (2021-2025)
Life Stage: The life stage of the penguin (Chick, Juvenile, Adult)
Body Mass (g): Body mass in grams
Bill Length (mm): Bill length in millimeters
Bill Depth (mm): Bill depth in millimeters
Flipper Length (mm): Flipper length in millimeters
Health Metrics: Health status of the penguin (Healthy, Overweight, Underweight)

Methods being used:
Logistic Regression, Random Forest Selection, SVM, and basic Neural Networks. 

I will be checking for the highest accuracy across all the data algorithms.

INITIAL FINDINGS:
Based on the four models built, neural networks indicated the highets accuracy and decision tree had the least accuracy. Both logistical regression and random forest selection had similar accuracy values to that of neural networks ranging around 80% and 90% respectively for species and sex. 

We have also created confusion matrix to further review the correlations and have a better understanding of both the target variables.

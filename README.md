# Anonymize data in Python

A possible solution to dealing with Personal identifying information(PII) in the datasets is to anonymize the dataset by replacing information that would identify a real individual with information about a fake (but similarly behaving or sounding) individual.

## Objective: 
Given a target dataset (for example, a CSV file with multiple columns), produce a new dataset such that for each row in the target, the anonymized dataset does not contain any personally identifying information. The anonymized dataset should have the same amount of data and maintain its analytical value.

<p align="center">
<img src="https://miro.medium.com/max/1400/0*Mf_EX7p1caMoabhv.png">
  
<!--(Image)![image](https://user-images.githubusercontent.com/28645647/175289257-05924a9c-6d61-4ed2-9933-3ad3939eae24.png)-->


## Tools:
There are two third-party libraries for generating fake data with Python
- Faker
- Fake Factory, also called “Faker”

Faker provides anonymization for user profile data, which is completely generated on a per-instance basis. 
Fake Factory uses a providers approach to load many different fake data generators in multiple languages (deprecated now - still useable)

## References:
- A Practical Guide to Anonymizing Datasets with Python & Faker - https://medium.com/district-data-labs/a-practical-guide-to-anonymizing-datasets-with-python-faker-ecf15114c9be
- Faker documentation - https://faker.readthedocs.io/en/master/

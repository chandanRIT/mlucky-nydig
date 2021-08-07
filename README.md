Project Overview:

This 3-part project is designed to evaluate your written and coding abilities. <br />
In part 1, we'd like you to provide the data model of a basic medical system based on a series of specifications. <br />
In part 2, we'd like you to sketch out a high level design and discuss trade-offs. <br />
In part 3, we'd like you to provide an implementation of a single specification. <br />

Time required on this project should not take you more than 5 hours in total. <br />
Questions can be asked via GitHub issues. We'd prefer your implementation to use a JVM based or an OOP language. <br />
Associated documentation, design artifacts, and implementations should be submitted back and viewable as a GitHub Pull Request.

Part 1: Data Model
Sketch out reasonable data models for a medical system that covers the following specifications.

Specifications: <br />
A patient should be able to view & edit their personal information. <br />
A patient should not be able to view or edit another patient’s personal information. <br />
A patient should be able to view their medical information. <br />
A patient should be able to view a generated health summary report that shows an overview of their health. <br />
A patient should not be able to view another patient’s medical information. <br />
The patient’s doctor should be able to view the patient’s personal information. <br />
The patient’s doctor should be able to view & edit the patient’s medical information. <br />
Doctors should be able to view & edit visit notes and medical information (separated into diagnostic and treatment) for their patients. <br />

Part 2: System Design <br />
Write a brief sketch of a high level system design for the above specifications and discuss what technologies you'd use, the alternatives, and the trade-offs. You do NOT need to go too much in depth.

Part 3: Implementation <br />
Using the specifications and data model above, implement a class that generates a health summary given a patient ID and date. Feel free to have mocked database access that returns hardcoded data, but do not hardcode in the actual service class. Write tests for your service. This can be a mix of unit and functional tests that cover corner cases where applicable. You do NOT have to spin up a full web service or database. We're looking for a well tested class (with potentially small utility classes) that is complete with some tests.

Things to include in the summary: <br />
Basic patient information such as name, birthday, gender, height, and weight. <br />
Current BMI calculated from the medical history.<br />
Min, mean, median, and max for blood pressure and heart rate within the last 12 months. <br />
List of visits within the last 12 months. <br />

How you will be evaluated
Your system design and data model writeup should be clear, reasonable, discuss trade offs, and not overengineered. <br />
Your submission should include a README that outlines how to run your project and execute tests. <br />
Your code should be clean, readable, and idiomatic. <br />
Your code should have the right level of abstraction. <br />
Your code should run and be correct. <br />
Your code should be reasonably well tested with mocks where appropriate. <br />

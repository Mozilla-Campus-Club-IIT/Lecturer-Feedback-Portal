![header](https://github.com/Mozilla-Campus-Club-IIT/Lecturer-Feedback-Portal/blob/master/file/hacktoberfesth1.jpg)
![title](https://github.com/Mozilla-Campus-Club-IIT/Lecturer-Feedback-Portal/blob/master/file/Collection4.jpg)

# Feedback Portal for Lecturers
Lecturers want to get feedback from students after each lecture they do. 

There are two main aspects to consider
1. **Students understanding**
2. **Lecturer teaching feedback**- So in order to get overall feedback the following is used to measure.
A series of MCQ questions (yes or no) and text inputs to type the students feedback about the lecturers output for that particular lecturer.

From the lecturer dashboard a lecturer can see the response and percentages of students understanding. This will be a good insight for the lecturers since the responses will be anonymous. Data collected can be used to future pattern matching and analysis.

# Functionality

## Lecturers 
* Login
* Create new feedback form for a lecture (with some lecture details and date). This form should be dynamic to add mcq and text fields (form builder)!
* Generate a unique URL for the feedback form
* View past forms and responses 
* More analytics about the feedback and timeline
* Cookie based user tracking in order to secure the anonymity 

## Students
* View form via a URL
* Submit responses 
* Show a positive inspirational quote (nf)

# Proposed System Architecture 
### Front end
- Angular 2
- Bootstrap

### Backend 
- NodeJS 
- MongoDB Database
- [ ] AWS Lamda (Serverless Architecure)- in phase two

#My test Jayasanka

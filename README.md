# Do Tutors Learn from Equity Training and Can Generative AI Assess It?

## Citation  

Thomas, D. R., Borchers, C., Kakarla, S., Lin, J., Bhushan, S., Guo, B., Gatz, E., & Koedinger, K. R. (2025). *Do Tutors Learn from Equity Training and Can Generative AI Assess It?*. In *Proceedings of the 15th International Learning Analytics and Knowledge Conference (LAK 2025)*. Association for Computing Machinery. [https://doi.org/10.1145/3706468.3706531](https://doi.org/10.1145/3706468.3706531)  

```bibtex
@inproceedings{thomas2025equityai,
    author    = {Thomas, Danielle R. and Borchers, Conrad and Kakarla, Sanjit and Lin, Jionghao and Bhushan, Shambhavi and Guo, Boyuan and Gatz, Erin and Koedinger, Kenneth R.},
    title     = {{Do Tutors Learn from Equity Training and Can Generative AI Assess It?}},
    booktitle = {Proceedings of the 15th International Learning Analytics and Knowledge Conference},
    series    = {LAK 2025},
    location  = {Dublin, Ireland},
    publisher = {Association for Computing Machinery},
    address   = {New York, NY, USA},
    doi       = {10.1145/3706468.3706531},
    month     = {03},
    year      = {2025}
}
```
---

**Research Questions:**

- **RQ1**: Is the scenario-based lesson effective in teaching tutors new skills for responding to students possibly experiencing inequities?  
- **RQ2**: How does tutors’ self-reported confidence in their knowledge attending to students experiencing potential inequities change from pretest to posttest, and do tutors feel they can apply what they have learned?  
- **RQ3**: How effective are large language models GPT-4o and GPT-4-turbo in assessing tutors’ actions in responding to students managing possible inequity?  
- **RQ4**: How do the large language models GPT-4o and GPT-4-turbo compare in performance, efficiency, and cost?  

To access the lesson log data files, visit **[DataShop](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=6251)**.  

Below is a brief explanation of the provided data fields.

Sample_Name - Name of dataset sample - all lessons in this dataset are Advocacy lessons<br/>
Transaction_Id - Unique identifiers for each interaction on the tutor platform <br/>
Anon_Student_Id - Anonymized identifier for each student/tutor <br/> 
Session_Id - Unique identifiers for each student/tutor log-in session<br/> 
Time - Timestamp for when lesson response was recorded<br/> 
Time_Zone - The Timezone in which the time or lesson response was recorded<br/> 
Duration_(sec) - Duration of student/tutor interaction on platform<br/> 
Student_Response_Type - The type of response provided by the student/tutor<br/> 
Student Response Subtype - Additional classification for the student/tutor response type<br/>
Tutor Response Type - Type of response provided by the student/tutor (answer evaluator)<br/>
Tutor Response Subtype - Additional classification for the student/tutor response type<br/>
Level (Lesson) - Name of the lesson<br/> Level_(Level2) - Response classification<br/>
Level_Level2_corrected - Corrected version of response classification to have uniformity<br/>
Problem Name - Specific question that the student/tutor is answering<br/> 
Problem View - View of the problem number<br/> 
Problem Start Time - Timestamp for when the problem was attempted<br/> \Step Name - Action taken by the student/tutor by question<br/> 
Attempt At Step - Number of attempts for the specific step<br/> 
Is Last Attempt - Indicates whether this is the last attempt at the step (1 for yes, 0 for no)<br/> 
Outcome - Result of attempt for MCQ<br/> 
MCQ_score - Multiple-choice question score (1 for correct, 0 for incorrect)<br/> 
Selection - Selection made by the student/tutor<br/> Action - Action taken by the student/tutor<br/> 
Input - Input provided by student/tutor<br/> 
Rater1_codes - Codes assigned by rater1 for open response questions to student/tutor response (1 for correct, 0 for incorrect)<br/>
Rater2_codes - Codes assigned by rater2 for open response questions to student/tutor response (1 for correct, 0 for incorrect)<br/> 
Open_response_score_human_truth - Source of truth determined between two raters for open-response questions<br/> 
Feedback_Text - Textual feedback provided to response<br/> 
Feedback_Classification - Classification of the feedback<br/> 
Help_Level - Level of help provided<br/> 
Total_Num_Hints - Number of hints used<br/> 
KC (Single-KC) - Knowledge component (KC) linked to the step, representing a single skill or concept<br/> 
KC Category (Single-KC) - Category of KC for the step<br/> 
KC (Unique-step) - Unique identifiers for KC<br/> 
KC Category (Unique-step) - Category of unique KC identifier<br/> 
School - School or organization through which student/tutor takes the course<br/> 
Class - Class of the lesson<br/> CF (AI_Evaluation) - Evaluation of response by AI (1 for correct, -1 for incorrect)<br/> 
CF (AI_Rephrased_Response) - AI rephrased version of the incorrect response<br/> 
CF (AI_Request_Counter) - Counter for AI requests<br/> 
CF (Condition) - Condition of the question between Mixed, Open response, and MCQ<br/> 
CF (Counterbalanced) - Order of scenarios counterbalanced<br/> 
CF_Counterbalanced_corrected - Corrected version of the order of scenarios counterbalanced to have uniformity<br/> 
CF (Sequence) - Sequence in which events occur<br/> 
CF (tool_event_time) - Timestamp for the tool event<br/> 
CF (tutor_event_time) - Timestamp for the tutor event<br/> 
Event_Type - Type of event recorded<br/>

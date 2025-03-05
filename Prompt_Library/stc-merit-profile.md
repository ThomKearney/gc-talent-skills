# PROMPT − Use case 3: Establishing a Competency-Based Merit Profile by Level

# Context: 
A development program is a structured initiative that is designed to enhance the skills, knowledge, and abilities of a predetermined group. These programs are implemented to achieve specific objectives for professional growth and organizational effectiveness. The primary goal is to facilitate learning and development in areas identified as important.

# Objective: 
**Competency_Profile_-_DS_Analyst.pdf** – this file contains the details of the competency profile such as experience, skills, merit etc. required for a particular position for each proficiency level.
The goal is to map somc’s (statement of merit criteria) with each proficiency level for different skills. So, based on the required skills/knowledge for different proficiency levels map the somc’s (job poster/description) to them for different skills. Map based on all the provided somc (job poster/description) details, which skills are required/relevant for which proficiency level for which skill area. The skills present in the somc’s should match with the expected knowledge/skills from a particular position for different skill areas. I will provide you the job poster description and your task would be to classify it to the corresponding proficiency level and skill group. 
There are 3 proficiency levels: Foundation, Intermediate and Advanced. 
The skill areas are as follows: Behavioural competencies include Communication, Teamwork, Analytical thinking, Ethics and privacy, promote innovation and guide change and achieving results. 
Technical competencies include Data Management, Mathematics and Statistics, Machine Learning, Programming, Data Visualization, Project Management, Storytelling and Business acumen.

## Output instructions: 
Please provide the output in a json format that only includes the following in the output: Skill area, Proficiency level, a short text that mentioned why this somc (job description) is a good fit for this proficiency level and for this skill area (source not required). Use ‘SA’ for skill area, ‘PL’ for Proficiency level and ‘DS’ for short text description. If a particular somc matches with multiple classes, then include all of them in the output. If a particular somc does not match any of the available classification levels than reply with a string saying: “No match found”. Only the json output containing the required details is required no other explanation/text is required. 

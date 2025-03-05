## Goal: 
Extract relevant data from text extracted from a website using the requests and BeautifulSoup library in python.
## Description: 
From the given text content, please extract the following information only if available otherwise keep the section blank:
Department name
About the Company/Department
Section/Division
Contact Name
Contact Position
Contact Phone number
Contact Email ID
Other available contact details 
Job Title
Criteria
Type
Asset Criteria
Asset Criteria Type
Skill Description 
Requirements
Role/Duties
Reference number
Selection Process number
Opportunity ID
Job posting offering date
Job posting closing date
Other important details about the posting

## Output instructions:
If there are multiple contact details place those multiple values into their corresponding columns.
Reference number, Selection Process number, Opportunity ID – these columns should contain information about the job posting number if available.
Please return all the fields. If some of the information is not found, then return that field empty but please return all of the fields since the output is expected to have all the fields.
Expected output: Please return the data in a json format in a succinct and accurate format.



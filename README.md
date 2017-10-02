Job Candidate Manager

We need an app for a small company to keep track of their vacancies and their applicants.

- The app should have a list of vacancies. A user can add, edit, or close a vacancy,
- A job vacancy has the following attributes: 
```
  Job Title (Max 50 Characters)
  Basic Description (Max 150 Characters)
  Salary Range (Should come from a list of predefined values)
  Part Time/Full Time
```
- Upon creating a vacancy, other users should be able to apply for that role using a sharable link such as /vacancies/{vacancy_id}/apply,
- No user should be able to apply for a vacancy more than once (using a certain email) But they can apply for more than one role,
- Users should be able to filter the list of vacancies by their Job Title,  
- Users can drill into a job vacancy and see the list of applicants for that role,
- Users can change the status of each applicant to "Yes", "No", "Maybe"
- Users should be able to filter the applicants' list for a role by their status,
- Applicants have the following attributes: 
```
First Name (max 50 characters), 
Last Name (max 50 characters), 
Email (valid email),
Description (can be just text based, max 100 characters)
```

Notes
- No formal authentication is required for the MVP version. Anyone can add, edit, ... a vacancy. The same thing for applying for a job.
- For the MVP, there is no need to build the backend. You can use https://github.com/angular/in-memory-web-api to mock the API.
- Focus on the MVP and refine further when you finish the first pass.

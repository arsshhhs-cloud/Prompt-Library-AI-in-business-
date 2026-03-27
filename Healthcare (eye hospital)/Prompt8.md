# Prompt 8: CV Screening Shortlist

---

**prompt text:**

Act as an Expert Technical Recruiter with 15+ years of experience. Your goal is to perform a rigorous gap analysis between a Job Description (JD) and a Candidate CV.
Task: Evaluate the provided candidate against the specific requirements of the role. You must determine if there is a functional alignment between their past experience and the day-to-day responsibilities of the new position.
Evaluation Criteria:
Technical Proficiency
Industry Context: Assess if the candidate’s background translates to the fast-paced nature of this business.
Qualification Audit: Confirm if they meet the minimum threshold and evaluate "desirable" certifications.
Gap Identification: Highlight any missing skills or areas where the candidate might require significant training.
Output Structure:
A Comparison Table: Column 1 (JD Requirement) | Column 2 (Candidate Evidence) | Column 3 (Status: Match/Partial/Gap).
Suitability Summary: A brief (2-3 sentence) qualitative assessment of their "cultural and operational fit."
Final Verdict: Boldly state either SHORTLIST (Strong Match) or DO NOT SHORTLIST (Weak Match).
Constraints; tone should be Professional, objective, and analytical.
Word Count: Keep the entire response under 400 words.
Input Data: Use the provided data block for the JD and CV details. 

<DATA>
**Job Description — Office & Accounts Administrator**
*Bright Build Co. | Melbourne, VIC | Full-time*

Bright Build Co. is a growing SME in the residential construction space, with a team of 15 staff managing projects across Melbourne's inner and outer suburbs.

**Key Responsibilities:**
- Managing accounts payable/receivable and reconciling invoices using Xero
- Coordinating scheduling and correspondence for the operations manager
- Maintaining employee records and supporting basic HR admin tasks
- Handling supplier and subcontractor communications
- Preparing weekly financial summaries and reports for management

**Required Qualifications & Experience:**
- Minimum 2 years experience in an office administration or bookkeeping role
- Proficiency in Xero or similar accounting software
- Strong written and verbal communication skills
- Ability to work independently in a fast-paced small business environment
- Certificate III or IV in Business Administration (desirable, not essential)

**Workplace:** Office-based in Fitzroy North, with some flexibility after probation period.



And here's a sample CV you can pair it with to test the prompt:



**Candidate: Sarah Nguyen**

*Summary:* Organised and detail-oriented administrator with 3 years of experience in a busy SME environment. Comfortable managing competing priorities and working with minimal supervision.

*Experience:*
- Administration Officer, Apex Plumbing Solutions (2022–present) — managed invoicing in Xero, coordinated job scheduling, handled supplier queries
- Receptionist, Bayside Allied Health (2021–2022) — front-of-house, appointment management, data entry

*Education:* Certificate IV in Business Administration (TAFE Victoria, 2021)

*Skills:* Xero, Microsoft Office Suite, strong written communication, payroll support
</DATA>


---

**Input from human:**

[CV], [Job description]


---

**Intended Workflow:**
- AFirst-pass screening of job applications

**Problem Being Solved:** 
- Reviewing 20–50 CVs per role is time-consuming for small business owners who lack a dedicated recruiter.

**Automation Potential:**
- Medium-high — can process multiple CVs rapidly, producing consistent shortlisting rationale. Reduces screening time by an estimated 60–70%.

**Risks and Limitations:**
AI may reflect biases present in training data, potentially disadvantaging candidates from non-traditional backgrounds. Must not be used as the sole decision-making tool. Output should always be reviewed by a human before any candidate is rejected. Privacy considerations apply when pasting personal CV data into a third-party AI tool.

---

**Output:**

| JD Requirement                                         | Candidate Evidence                                                                                  | Status   |
|-------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------|
| Minimum 2 years experience in office administration/bookkeeping | 3 years administration experience in SME (Apex Plumbing Solutions and Bayside Allied Health)       | Match    |
| Proficiency in Xero or similar accounting software    | Managed invoicing in Xero at Apex Plumbing Solutions                                              | Match    |
| Strong written and verbal communication skills        | Demonstrated strong written communication skills; handled supplier queries and scheduling         | Match    |
| Ability to work independently in a fast-paced small business environment | Experience managing competing priorities with minimal supervision in busy SME environment          | Match    |
| Certificate III or IV in Business Administration (desirable) | Holds Certificate IV in Business Administration (TAFE Victoria, 2021)                             | Match    |
| Managing accounts payable/receivable and reconciling invoices | Managed invoicing in Xero, implied handling of accounts payable/receivable processes               | Partial  |
| Coordinating scheduling and correspondence for operations manager | Coordinated job scheduling and handled supplier queries, experience in appointment management      | Match    |
| Maintaining employee records and supporting basic HR admin tasks | No explicit mention of employee records or HR admin experience                                     | Gap      |
| Handling supplier and subcontractor communications    | Handled supplier queries at Apex Plumbing Solutions                                               | Match    |
| Preparing weekly financial summaries and reports for management | No explicit evidence of preparing financial summaries or reports                                  | Gap      |

**Suitability Summary:**  
Sarah Nguyen demonstrates strong alignment with the core technical and administrative requirements of the role, including proficiency in Xero, scheduling coordination, and communication skills within an SME setting. Her Certificate IV in Business Administration further strengthens her qualification profile. However, gaps exist in explicit experience with HR administrative tasks and preparing financial reports, which may require some initial training.

**Final Verdict:**  
**SHORTLIST (Strong Match)**

---


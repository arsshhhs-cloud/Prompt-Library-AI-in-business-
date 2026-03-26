**title:** - SMS appointment reminder with health tips.

**prompt text:**
Role: Senior Healthcare Communications Specialist (UX Writing).
Task: Generate a library of 5 intent-specific SMS appointment reminders for an eye-specialty hospital.
Constraint: Maximum 150 characters per SMS (to prevent multi-segment billing).

The Five Specific Intents:

Routine/General: Tip on resting eyes from screens.

Post-Surgery (e.g., LASIK/Cataract): Tip on bringing sunglasses for light sensitivity.

Contact Lens Review: Tip on not wearing lenses 24h prior.

Diagnostic/Dilation: Tip on arranging a driver for home.

New Patient: Tip on arriving 10 mins early for paperwork.

Requirements per Variation:

Personalization: Use tags [Name], [Date], [Time].

Call to Action: Include a placeholder link [Link].

Structure: Friendly greeting + Confirmation + 1 Medical Tip + CTA.

Formatting: Present as a numbered list with a "Character Count" check for each.

**Intended Workflow:**
Automated pre-appointment SMS reminders sent via the hospital's CRM system.

**Problem Being Solved:**
High no-show rates cost the hospital significant revenue and waste clinical resources. Manually crafting and sending appointment reminders is repetitive and not scalable as patient volumes grow.

**Automation Potential:**
Very High. SMS templates generated here can be loaded directly into platforms and triggered automatically based on appointment schedules — requiring zero ongoing manual effort.

**Risks and Limitations:**
- Character limits-constrain how much information can be included; prompt outputs must be carefully checked.
- Patients must have provided consent to receive SMS communications — AI cannot verify this; compliance must be managed at the CRM level.
- AI cannot tailor messages to individual medical history or preferences.

**Output:**
1. Hi [Name], your eye check is on [Date] at [Time]. Rest screens for 20 mins/hr to ease eye strain. Confirm: [Link]  
Character Count: 139

2. Hello [Name], your post-surgery visit is [Date] at [Time]. Bring sunglasses for light sensitivity. Confirm: [Link]  
Character Count: 126

3. Hi [Name], your contact lens review is on [Date] at [Time]. Avoid lenses 24h before your visit. Confirm: [Link]  
Character Count: 131

4. Hello [Name], your diagnostic test with dilation is on [Date] at [Time]. Arrange a driver for home. Confirm: [Link]  
Character Count: 134

5. Hi [Name], your new patient appointment is [Date] at [Time]. Arrive 10 mins early for paperwork. Confirm: [Link]  
Character Count: 134

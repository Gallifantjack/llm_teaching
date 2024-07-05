# Prompt Cards

> These Prompt Cards come from the paper "The First Generative AI Prompt-A-Thon in Health Care: A Novel Approach to Workforce Engagement with a Private Instance of ChatGPT" by Small et al., under review at PLOS Digital Health.

## Example Project Card 1: Patient Education

**Theme:** Patient education (Medication)  
**Source Material:** Hospital Discharge Summaries

### Core Tasks

| Task | Example | Sample Prompt |
|------|---------|---------------|
| Search | Search whether the plan for follow-up is described. | Please find me all the details in this clinical note that describe what doctors/clinic this patient should follow-up with. |
| Summarization | High risk medications | Give me a list of all the high-risk medications listed in this clinical note, explain your reasoning, and highlight any new high-risk medications. |
| Extraction | Medications and Doses | Based on this note, I need to know every medicine this patient will be leaving the hospital on, their doses and frequencies, and how long they are prescribed for. |
| Verification | Verify there are no drug-drug interactions. | Ensure that any of the new medications do not interact with the home medications that they will remain on after leaving the hospital. If you notice an interaction, let me know and show me alternatives. |
| Classification | Classify the reading level of the document. | Determine the reading level of this document and make a classification on whether this clinical document is understandable for the average patient and why. |
| Transformation | Transform the data to display medications and administration times (am/pm) in an easy-to-read table. | Create a readable table of medications, administration times and doses from this document. It should be easy to understand for a patient leaving the hospital with poor health literacy and low family support. |
| Generation | Recommend medication administration times based on current best timing practice. | Utilize the table of medications you just created with administration times and optimize those times based on current best practices for medication compliance. Highlight what you changed and explain why. |

## Example Project Card 2: Health Equity

**Theme:** Equity (Evaluate clinical data for bias)  
**Source Material:** History and Physical Notes

### Core Tasks

| Task | Example | Sample Prompt |
|------|---------|---------------|
| Search | Look for indicators of socioeconomic status: Identify indicators of the patient's race, ethnicity, wealth, income, occupation, and/or education level. | Isolate into a list all indicators of the patient's socioeconomic status from this clinical note. Comment on what you think their status is based on the evidence. |
| Summarization | Describe why the patient was admitted to the hospital. | Summarize the following clinical document and not just describe the patient's primary problem, but whether you think any social determinants of health could have played a major role. |
| Extraction | Review the H&P and please extract any positive descriptors of the patient or their behavior, for example, compliments or shows of approval. Extract any indicators of bias. | Extract any negative descriptors of the patient or their behavior, for example, resistant, refusing, agitated, difficult or noncompliant. |
| Verification | Ensure there is shared decision making with the patient in formulating the assessment and plan. | Please verify whether there is evidence the clinician participated with the patient in shared decision making when constructing their plan. Explain why you think so. |
| Classification | Rate how patient-centered the document is. | Considering the use of negative and positive descriptors and inclusion or exclusion of evidence for shared decision making, I need you to classify the H&P as high, moderate, or low in terms of patient-centered-ness. |
| Transformation | Increase patient trust in the medical team. | Without medical jargon, please use the H&P to create a one paragraph explanation to the patient about why they are being admitted to the hospital that communicates the team listened to their complaints and their concern for the patient's well-being. |
| Generation | Create an alternative assessment and plan. | Review the ED Data and History section of the H&P to create an assessment and plan. Describe the differences between your assessment and plan and the one in the H&P. |

## Example Project Card 3: Research Grant Proposal

**Theme:** Research – transform a project summary into a specific aims page  
**Source Material:** R01 Grant Project Summary

### Core Tasks

| Task | Example | Sample Prompt |
|------|---------|---------------|
| Draft | Draft a full specific aims page based on the project summary provided. | Here is a research project summary. Give me at least 3 specific aims with descriptions underneath. |
| Evaluate | Identify potential weaknesses of this proposed study. | What might be the weaknesses to this proposed study? How do you suggest the authors improve the design? |
| Identify alternatives | Generate alternative designs that address potential weaknesses. | Use this project summary to propose a number of projects with a variety of study designs and your reasoning why it could be important for generalizable knowledge. |
| Enhance | Propose rigorous measures for the study. | What would be additional study measures that can be used to evaluate the study hypotheses? |
| Contextualize | Identify relevant literature that would strengthen the proposal. | Improve the background and significance section of the specific aims page. Add supporting references. |
| Optimize | Test various language, format, styles, "voices," to enhance the proposal. | Make the tone more scientific. Make the tone more colloquial. Add a stronger narrative voice to the proposal. Reorganize the structure of the proposal in 3 different ways for me to compare. |
| Equity | Propose versions that would study this problem from an equity perspective. | Revise the proposal to directly address the equity issues related to these research questions. |
| Compare | Compare the proposal to the original and evaluate pros/cons. | Compare the proposal to this specific aims page """xxx""". Which is more likely to get funded by the NIH. |
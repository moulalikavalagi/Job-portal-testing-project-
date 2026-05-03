# Test Cases: Job Application Module

| TC ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC031 | Apply for job with complete profile | Click Apply, submit application | Application submitted successfully | | |
| TC032 | Apply without uploading resume | Click Apply without resume in profile | Show error "Please upload resume to apply" | | |
| TC033 | Apply for same job twice | Submit application, apply again for same job | Show error "Already applied for this job" | | |
| TC034 | Apply for expired job posting | Open expired job, click Apply | Show error "This job posting has expired" | | |
| TC035 | Upload valid resume format | Upload PDF resume file | Resume uploaded successfully | | |
| TC036 | Upload invalid resume format | Upload .exe file as resume | Show error "Invalid file format" | | |
| TC037 | Upload resume exceeding size limit | Upload file larger than 5MB | Show error "File size exceeds limit" | | |
| TC038 | Write cover letter | Enter cover letter text, submit application | Cover letter saved with application | | |
| TC039 | Apply without cover letter | Submit application without cover letter | Application submitted successfully without cover letter | | |
| TC040 | View application status | Go to My Applications section | Show current status of all applications | | |
| TC041 | Withdraw application | Click withdraw on submitted application | Application withdrawn successfully | | |
| TC042 | Apply with incomplete profile | Click Apply with missing profile details | Show error "Complete your profile to apply" | | |
| TC043 | Receive confirmation email | Submit application successfully | Confirmation email received in inbox | | |
| TC044 | Application with notice period | Enter 30 days notice period | Notice period saved correctly | | |
| TC045 | Apply for job with salary mismatch | Apply for job below expected salary | Application submitted with warning message | | |

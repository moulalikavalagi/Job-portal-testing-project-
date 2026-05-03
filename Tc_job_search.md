# Test Cases: Job Search Module

| TC ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC016 | Search with valid job title | Enter "Software Tester" in search bar, click search | Display relevant job listings | | |
| TC017 | Search with invalid job title | Enter "xyzabc123" in search bar | Display "No jobs found" message | | |
| TC018 | Search with empty field | Click search without entering anything | Display "Please enter a search term" | | |
| TC019 | Filter by location | Select "Bangalore" from location filter | Display only Bangalore based jobs | | |
| TC020 | Filter by experience | Select "Fresher" from experience filter | Display only fresher jobs | | |
| TC021 | Filter by salary range | Select "2-4 LPA" salary range | Display jobs within that salary range | | |
| TC022 | Filter by job type | Select "Remote" from job type filter | Display only remote jobs | | |
| TC023 | Multiple filters together | Select Fresher + Bangalore + Remote | Display jobs matching all three filters | | |
| TC024 | Clear all filters | Click "Clear Filters" button | All filters reset, show all jobs | | |
| TC025 | Sort by date posted | Select "Newest First" from sort option | Latest jobs appear at top | | |
| TC026 | Sort by relevance | Select "Most Relevant" from sort option | Most matching jobs appear first | | |
| TC027 | Job listing pagination | Click page 2 of results | Next set of jobs loads correctly | | |
| TC028 | View job details | Click on any job listing | Full job description page opens | | |
| TC029 | Save job for later | Click bookmark icon on job listing | Job saved to favourites list | | |
| TC030 | Search with special characters | Enter "@#$%" in search bar | Display "Invalid search term" error | | |

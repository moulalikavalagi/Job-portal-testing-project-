# Bug Reports: Job Portal Web Application

## BUG001
**Title:** Duplicate email registration allowed without error
**Severity:** Critical
**Priority:** High
**Module:** Registration
**Steps to Reproduce:**
1. Register with email test@gmail.com
2. Logout
3. Register again with same email test@gmail.com
**Expected Result:** Show error "Email already exists"
**Actual Result:** Second account created successfully with same email
**Status:** Open

---

## BUG002
**Title:** No error shown when search field is empty
**Severity:** Medium
**Priority:** Medium
**Module:** Job Search
**Steps to Reproduce:**
1. Login as job seeker
2. Go to search bar
3. Click search without entering anything
**Expected Result:** Show error "Please enter a search term"
**Actual Result:** Page refreshes with no results and no error message
**Status:** Open

---

## BUG003
**Title:** Invalid file format accepted during resume upload
**Severity:** Critical
**Priority:** High
**Module:** Job Application
**Steps to Reproduce:**
1. Login as job seeker
2. Go to profile section
3. Upload .exe file as resume
**Expected Result:** Show error "Invalid file format. Only PDF and DOC allowed"
**Actual Result:** File uploaded successfully without any error
**Status:** Open

---

## BUG004
**Title:** Expired job posting still shows Apply button
**Severity:** High
**Priority:** High
**Module:** Job Application
**Steps to Reproduce:**
1. Login as job seeker
2. Open any expired job listing
3. Check Apply button visibility
**Expected Result:** Apply button should be disabled or hidden
**Actual Result:** Apply button visible and clickable on expired listings
**Status:** Open

---

## BUG005
**Title:** Special characters accepted in job search field
**Severity:** Low
**Priority:** Low
**Module:** Job Search
**Steps to Reproduce:**
1. Login as job seeker
2. Enter "@#$%" in search bar
3. Click search
**Expected Result:** Show error "Invalid search term"
**Actual Result:** Search executes with no results and no error message
**Status:** Open

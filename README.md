# Test Case Writer

You have been tasked to write a test suite for a series of small web apps. Each application has a set of business rules that you must verify work correctly. For each web app you will create 3 documents.
- Test Suite
- Defect Report
- Requirements Traceability Matrix

You may choose to write these documents in excel, word or markdown however they should be uploaded to Github. An example template/guide for the documents is provided.

## Example Documents
This is for a fictional app not included as one the apps provided.

Test Suite
|Test Case| Desc | Steps |
|---------|------|-------|
|TC-1| Login with correct credentials | type username as "Billy99" and password  as "pass123". Press login. Verify on homepage for Billy99 | 
|TC-2| Login with incorrect credentials | type username as "Billy99" and password  as "coolbeans". Press login. Verify message says incorrect password |


Defect Report
|Defect | Desc | Severity | Priority | Steps to reproduce |
|-------|------|----------|----------|--------------------|
|DEF1   |Popup message says user not found instead of incorrect password | low | low | Login with a correct username and incorrect password |

Requirements Traceability Matrix
|Requirement| Test Cases | Status | Defects |
|-----------|------------|--------|---------|
|Users should see a generic message saying login has failed if they provide the wrong credentials | TC-1, TC-2 | TC-1 PASS, TC-2 FAIL| DEF1 |

Test Cases: Ubaydulla N
Team number: Oreo

Test ID: TC-01
Written by: Ubaydulla N
Title: Costume name one character over the maximum length is accepted and empty characters are accepted
Traces to: REQ-04 (Costume names must be between 1 and 50 characters)
Test type: Boundary Value 
Preconditions: Demo data reset. Logged in as ubay (password ubay).
Test data: (empty)
Description: (empty)
Category: creative

Steps: Leave Costume name field and Description field empty. Click Submit Costume and Open the Gallery page.

Expected result: An error message appears saying the name must be 50 characters or less. The costume does not appear in the Gallery. 
Actual result: A success message appeared ("Costume submitted! Good luck.").
Status: Fail 
Severity: Major
V or V: Verification


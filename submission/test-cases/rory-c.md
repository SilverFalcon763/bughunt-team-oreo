# Test Cases: Rory C

**Team number:** Oreo

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID:** TC-01
**Written by:** Rory C
**Title:** Vote Count Decrement
**Traces to:** REQ-9: Each user may cast at most 3 votes in total.
**Test type:** Boundary Value
**Test data:** Logged in as rory (password admin)

**Steps:**
1. Log in to account
2. Go to vote page
3. Click vote button 4 times

**Expected result:** User is unable to vote after submitting 3 votes and vote count is 0
**Actual result:** User can submit 4 votes or until vote count hits -1
**Status:** Fail
**Severity:** Minor
**V or V:** Verification

---

**Test ID:** TC-02
**Written by:** Rory C
**Title:** Password Length
**Traces to:** REQ-01	A user can register with a unique username and a password of at least 8 characters.
**Test type:** Acceptance
**Preconditions:** None
**Test data:** Created account with username "rory" and password "admin"

**Steps:**
1. Go to Login/Register tab
2. Enter any username
3. Enter a password less than 8 character

**Expected result:** Password is rejected for being less than 8 characters
**Actual result:** Account is created without issue
**Status:** Fail
**Severity:** Major
**V or V:** Verification

---

**Test ID:** TC-03
**Written by:** Rory C
**Title:** Can only add costumes with account
**Traces to:** REQ-02	A user can log in with their username and password. Only logged-in users can submit costumes or vote.
**Test type:** System
**Preconditions:** Create account
**Test data:** Username "rory" and password admin

**Steps:**
1. Create account with username and password
2. Go to submit costume tab and fill out fields
3. Click submit costume

**Expected result:** Users must be logged in to add a costume and are unable to if not
**Actual result:** User is prompted to login before submitting a costume
**Status:** Pass

---

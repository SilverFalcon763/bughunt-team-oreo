# Test Cases: Deandre C

**Team number:** 12

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

**Test ID:** DC-01
**Written by:** Deandre Chandler
**Title:** Creative Not in Vote page
**Traces to:** REQ-07 (Every submitted costume appears in the Gallery and is eligible for voting)
**Test type:** Integration
**Preconditions:** none
**Test data:** N/A

**Steps:**
1. Confirm the creative costume in the gallery
2. Check the vote page to see if eligible to vote

**Expected result:** Creative costume in vote page
**Actual result:** Not existant
**Status:** Fail
**Severity:** Critical
**V or V:** Validation

---

**Test ID:** DC-02
**Written by:** Deandre Chandler
**Title:** User cna submit multiple costumes
**Traces to:** REQ-03 (Each user may submit at most one costume.)
**Test type:** Negative
**Preconditions:** Logged in as g (password gggg). On the Submit Costume Page
**Test data:** 

Name: gg
Description: gg
Category: Spooky

Name: gg
Description: gg
Category: Spooky

**Steps:**
1. Type the test data name into the Costume name field
2. Type the test data description into the Description field
3. Select Spooky from the Category dropdown
4. Click Submit Costume
5. Repeat steps 1-4 

**Expected result:** Reject more than 1 costume entry
**Actual result:** Accepts more than 1 costume entry
**Status:** FAIL
**Severity:** Critcal
**V or V:** Validation

---

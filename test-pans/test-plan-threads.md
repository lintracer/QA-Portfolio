# Test Plan: Threads (Beta Testing via TestFlight)

## Overview
**Project:** Threads (pre-release iOS builds via TestFlight)  
**Platform:** iOS / TestFlight  
**Period:** Jan–Jun 2025  
**Role:** Beta tester — functional testing, exploratory testing, feedback submission  

**Summary:**  
Tested 5 pre-release builds on iOS devices. Conducted exploratory testing across core flows: onboarding, account setup, creating/editing posts, uploading images/videos, feed interactions, and profile settings. Submitted 3 functional bugs and 5 UI/UX suggestions, including detailed reproduction steps, screenshots, videos, and device logs. Verified fixes after new builds were released.  

**Testing types:** Functional, Exploratory, UI/UX Feedback

---

## Scope

**In Scope:**
- Onboarding flow
- Account setup and management
- Creating/editing posts
- Uploading images and videos
- Feed interactions (like, comment, share)
- Profile settings
- Reporting bugs and providing UI/UX feedback

**Out of Scope:**
- Backend API performance
- Third-party integrations
- Push notifications testing
- Automated testing (all testing was manual)

---

## Test Approach
- Manual exploratory testing for core features
- Bug reports submitted via TestFlight with screenshots, videos, and device logs
- UI/UX suggestions collected for onboarding, navigation, and post interactions
- Verification of bug fixes on subsequent builds

**Tools / Skills:** TestFlight, iOS, Exploratory testing, Functional testing, Bug reporting, Device logs

---

## Resources
- Environment: iOS devices via TestFlight (iPhone XS)
- Testers: Alex (QA / Beta Tester)
- Network: Wi-Fi and Mobile Data
- App versions: Threads 327.0 (TestFlight)

---

## Schedule
- Test execution: Jan–Jun 2025
- Feedback submission: Ongoing with each new build
- Bug verification: After each build update

---

## Exit Criteria
- All critical and high-priority bugs fixed and verified
- All planned exploratory testing flows completed
- UI/UX suggestions submitted and acknowledged
- All bug reports include reproduction steps and attachments

---

## Risks
- Intermittent issues may be missed due to random reproducibility
- Delays in new TestFlight builds could slow verification
- Limited device types may not cover all iOS variations

---

## Bugs Reported

### Bug Report BR-002
**Title:** Images fail to load in the feed (placeholder displayed)  
**Module:** Feed  
**Severity:** Medium | **Priority:** High  
**Environment:** iPhone XS, iOS 18.6.2, Threads 327.0 (TestFlight), Wi-Fi / Mobile Data  

**Preconditions:** User logged in, feed loaded  
**Steps to Reproduce:**  
1. Open the Threads app  
2. Scroll the feed slowly  
3. Observe posts containing images  

**Expected Result:** All images load normally  
**Actual Result:** Some images do not load; grey placeholder is shown  
**Reproducibility:** Random (~10–15% of posts affected)  
**Additional Information:** Occurs on both Wi-Fi and mobile data; restarting app does not solve the issue  
**Attachments:** Screenshots included  

---

### Bug Report BR-003
**Title:** Like counter does not update after tapping Like button  
**Module:** Feed / Post Interactions  
**Severity:** Low | **Priority:** Medium  
**Environment:** iPhone XS, iOS 18.6.2, Threads 327.0 (TestFlight), Wi-Fi / Mobile Data  

**Preconditions:** User logged in, feed loaded  
**Steps to Reproduce:**  
1. Open any post in Threads  
2. Tap the Like button  

**Expected Result:** Heart icon turns solid, counter +1  
**Actual Result:** Heart icon changes, counter does not update until feed refresh  
**Reproducibility:** ~60% of attempts  
**Additional Information:** No error messages displayed  
**Attachments:** Optional  

---

### Bug Report BR-004
**Title:** Keyboard input delayed in “Create Post” text field  
**Module:** Posting / Composer  
**Severity:** Medium | **Priority:** Medium  
**Environment:** iPhone XS, iOS 18.6.2, Threads 327.0 (TestFlight), Wi-Fi / Mobile Data  

**Preconditions:** User logged in, Home Feed open  
**Steps to Reproduce:**  
1. Tap “Create Post”  
2. Type a long sentence (10+ words)  

**Expected Result:** Keyboard input responds instantly  
**Actual Result:** Typing delayed 0.3–0.5s after 3–5 seconds  
**Reproducibility:** Random/intermittent, more noticeable with long sentences  
**Additional Information:** More noticeable when switching keyboard languages; disappears after app restart  
**Attachments:** Optional  

---

## References
- TestFlight builds of Threads (pre-release iOS versions)
- iOS device logs and crash reports
- Personal exploratory testing notes

### Test-Cases
[View case](./test-cases/QASE Threads.pdf) 

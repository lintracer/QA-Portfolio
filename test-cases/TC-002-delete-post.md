# ✅ Test Case

**Test Case ID:** TC-002  
**Title:** Deleting an existing post  
**Requirement ID (if exists):**  
**Module / Area:** Post Management  
**Type:** Functional  
**Priority:** Medium  
**Severity:** Major  

**Preconditions:**  
- User is logged into Threads  
- User has at least one existing post in their profile  
- Internet connection is active  
- App is open on the Profile screen  

**Environment:**  
- Device: iPhone (TestFlight build)  
- OS version: iOS  
- App version / Browser: Threads (TestFlight)  
- Network: Wi-Fi or Mobile Data

---

## ✅ Test Steps

| Step | Action | Expected Result |
|------|---------|------------------|
| 1 | Navigate to the Profile screen | Profile loads successfully |
| 2 | Locate an existing post | Post is visible |
| 3 | Tap the three-dot menu (…) on the post | Options menu opens |
| 4 | Tap Delete | Confirmation dialog appears |
| 5 | Tap Delete again in confirmation dialog | Post is removed from the account |
| 6 | Return to the profile feed | Post list updates and deleted post is gone |

---

## ✅ Expected Result

- Confirmation dialog appears after tapping Delete  
- After confirming, the post is permanently removed  
- Post no longer appears in:  
  - user’s profile  
  - main feed  
  - search results (if applicable)  
- No errors occur during deletion  
- Profile refreshes correctly  

---

## ✅ Postconditions

- The selected post is permanently removed from the account

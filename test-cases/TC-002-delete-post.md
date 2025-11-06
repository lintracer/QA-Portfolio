# Test Case: Delete an existing post

**ID:** TC-002  
**Title:** Deleting an existing post  
**Priority:** Medium  
**Module:** Post Management  
**Platform:** iOS (Threads via TestFlight)  
**Prepared by:** Alina  
**Status:** Ready

---

## ✅ Preconditions
- User is logged into Threads.
- User has at least one existing post in their profile.
- Internet connection is active.
- App is open on the **Profile** screen.

---

## ✅ Steps to reproduce

1. Navigate to the **Profile** screen.  
2. Locate any previously created post.  
3. Tap the **three-dot menu** (…) on the selected post.  
4. Tap **Delete**.  
5. Confirm the action by tapping **Delete** again in the confirmation dialog.  
6. Return to the profile feed and verify the post list.

---

## ✅ Expected result

- A confirmation dialog appears after tapping **Delete**.  
- After confirming, the post is permanently removed.  
- The deleted post no longer appears in:  
  - user’s profile,  
  - the main feed,  
  - search results (if applicable).  
- No errors occur during the deletion process.  
- The profile refreshes correctly.

---

## ✅ Postconditions
- The selected post is permanently removed from the account.

---

## ✅ Notes
- If the post contained media (photo/video), ensure no residual thumbnails or placeholders remain.
- Test should be repeated with:  
  - long posts,  
  - posts with media,  
  - posts made less than 1 minute ago (fresh publish).  
- Check deleting posts both on Wi-Fi and mobile data.

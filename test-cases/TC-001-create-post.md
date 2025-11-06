# Test Case: Create a new post in Threads

**ID:** TC-001  
**Title:** Creating a new text post  
**Priority:** High  
**Module:** Posting / Composer  
**Platform:** iOS (Threads via TestFlight)  
**Prepared by:** Alina  
**Status:** Ready

---

## ✅ Preconditions
- User is logged into Threads.  
- Internet connection is active.  
- App is launched and on the Home Feed screen.

---

## ✅ Steps to reproduce

1. Tap the **+** button (“New thread”).  
2. In the text field, enter any valid text (1–500 characters).  
3. (Optional) Add emoji.  
4. Tap the **Post** button.  
5. Wait for the post to publish and observe the behaviour.

---

## ✅ Expected result

- The post is successfully published.  
- The user is redirected to the feed or sees the post in their profile immediately.  
- The post text is displayed exactly as typed (formatting intact).  
- No errors or delays occur.

---

## ✅ Postconditions
- A new post is created and visible in the user's profile and feed.

---

## ✅ Notes
- If media is added (image/video), it should be covered with a separate test case.  
- This test should be repeated on mobile data and Wi-Fi for reliability.

# Test Plan: Adorable Adventures (Demo)

## Overview
**Project:** Adorable Adventures (Demo)  
**Platform:** PC / Windows  
**Period:** Feb 2026 - Mar 2026     
**Role:** QA Tester — exploratory and functional testing  

**Summary:**  
Tested demo build on PC. Conducted exploratory testing across core gameplay flows: character movement, inventory management, quest mechanics, environmental interaction, and UI navigation. Verified stability, game mechanics, and UI/UX consistency. Documented 6 confirmed bugs and provided UX suggestions.  

**Testing types:** Functional, Exploratory, UI/UX Observation

---

## Scope

**In Scope:**
- Character movement and sprint mechanics  
- Inventory and quest board interactions  
- Quest flow verification  
- Environmental interactions  
- UI/UX observation and feedback  
- Game stability and mechanics validation

**Out of Scope:**
- Multiplayer or online features (if any)  
- Full release content not in demo  
- Automated testing  

---

## Test Approach
- Manual exploratory testing for core gameplay features  
- Observation and documentation of UI/UX inconsistencies  
- Functional testing for main game mechanics  
- Bug reports submitted with reproduction steps, screenshots, and videos  

**Tools / Skills:** PC / Windows, Exploratory testing, Functional testing, UX observation, Bug reporting, Game mechanics verification

---

## Resources
- Environment: Windows PC  
- Testers: Alina (QA Tester)  
- Game version: Demo 0.9  
- Network: Offline  

---

## Schedule
- Test execution: Feb 2026 - Mar 2026   
- Observations, bug reports, and feedback: Ongoing during testing period  

---

## Exit Criteria
- Core gameplay flows verified and functional  
- Bugs documented and submitted  
- UX observations provided to improve player onboarding and gameplay experience  
- Game stability verified without critical issues  

---

## Risks
- Demo limitations may prevent testing of all game mechanics  
- Minor inconsistencies may not be reproducible on all configurations  

---

## Bugs Reported

### Bug Report BR-007
**Title:** Inventory and quest board not intuitive to close  
**Module:** Inventory / Quest Board / Smell List  
**Severity:** Medium | **Priority:** Medium  
**Environment:** PC, Windows 10/11, Demo 0.9, Offline  

**Preconditions:** Game started, main character on map, inventory/quest board/smell list opened  
**Steps to Reproduce:**  
1. Open inventory, quest board, or smell list  
2. Try to close using visible UI controls (without TAB key)  

**Expected Result:** UI elements can be closed via visible button or hint  
**Actual Result:** Only way to close is TAB key, not obvious  
**Reproducibility:** 100%  
**Additional Information:** Suggested tutorial or visual hints for inventory management  
**Attachments:** Screenshots  

---

### Bug Report BR-008
**Title:** Main character accelerates too fast during sprint  
**Module:** Character movement / Sprint  
**Severity:** Medium | **Priority:** Medium  
**Environment:** PC, Windows 10/11, Demo 0.9, Offline  

**Preconditions:** Game started, character able to move freely  
**Steps to Reproduce:**  
1. Begin moving character  
2. Activate sprint  
3. Observe speed and control  

**Expected Result:** Sprint speed allows precise control  
**Actual Result:** Accelerates too fast, hard to control direction  
**Reproducibility:** 100%  
**Additional Information:** Adjust sprint speed to maintain control  
**Attachments:** Screenshots  

---

### Bug Report BR-009
**Title:** Character collides and launches to unrealistic height  
**Module:** Physics / Collision / Jump mechanics  
**Severity:** Medium | **Priority:** Medium  
**Environment:** PC, Windows 10/11, Demo 0.9, Offline  

**Preconditions:** Game started, character in motion near obstacles  
**Steps to Reproduce:**  
1. Move character near object or wall  
2. Collide while sprinting/jumping  
3. Observe launch height  

**Expected Result:** Collisions follow normal physics  
**Actual Result:** Character sometimes launched to unrealistic heights  
**Reproducibility:** 80% (depends on angle and speed)  
**Additional Information:** Adjust collision physics to prevent unrealistic launches  
**Attachments:** Screenshots  

---

## References
- Adorable Adventures Demo build  
- Personal testing notes, logs, and UX observations

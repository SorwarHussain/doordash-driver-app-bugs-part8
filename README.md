# doordash-driver-app-bugs-part8
Text overlaps with UI elements, and component positions change unexpectedly, causing layout issues.

# Bug Report
**Title:** UI layout breaks and text overlaps after navigating back in Help flow

---

## Steps to Reproduce
1. Open the **DoorDash Driver (Dasher)** app.
2. Accept **two combined (stacked) orders**.
3. Start confirming the **first order**.
4. Tap the **Help** button.
5. Select the affected **order**.
6. Choose **Issue with store**.
7. Under order-related options, select **“Order not found in system.”**
8. Tap **Continue**.
9. Select **“Ask the store to place the order.”**
10. Tap **“Can’t place the order.”**
11. Select the radio button **“Other reason.”**
12. Attempt to add a description in the text box.
13. Tap the **Back** button.
14. Observe the UI layout.

---

## Expected Behavior
- UI elements should maintain proper alignment.
- Text should not overlap with other components.
- Layout should remain consistent when navigating back.

---

## Actual Behavior
- Text overlaps with UI elements.
- UI components shift positions unexpectedly.
- Layout appears broken after returning from the text input screen.

---

## Frequency
- Occurs always.

---

## Environment
- **Application:** DoorDash Driver (Dasher) app  
- **Platform:** Android 
- **App Version:** 8.62.1
- **Date Observed:** Jan 9, 2026 
- **Network:** Mobile data

---

## Impact
- Degrades user experience.
- Makes the Help screen difficult or impossible to use.
- Reduces clarity when reporting issues during active deliveries.

---


## Attachments
- Screen recording showing overlapping text and layout shift.

---


https://github.com/user-attachments/assets/7846e03a-c718-410e-b9dd-4363dbd97937



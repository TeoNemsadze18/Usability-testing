# NAV-BTN-018 - 18th Button Triggers Animation Only Without Navigation Link

* **Severity:** Medium
* **Environment:** Web / Mobile Web (anonymized)
* **Reproducibility:** 100%

## Summary
Out of 18 buttons in a group/list, the first 17 navigate to their respective links when clicked or tapped, while the 18th (last) button only plays the animation without any navigation link or handler attached.

## Steps
1. Open the view containing the group of 18 buttons.
2. Click or tap the first 17 buttons to verify that each navigates to its target link.
3. Click or tap the 18th (last) button and observe the behavior.

## Actual
The 18th button triggers only the visual animation and does not navigate anywhere.

## Expected
The 18th button should navigate to its intended link/destination, matching the behavior of the first 17 buttons.

## Notes
Missing link attribute or click/navigation handler on the final item in the 18-button set.

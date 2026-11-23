# UI-BTN-002 - Non-Clickable / Unresponsive Action Button

* **Severity:** High
* **Environment:** Mobile / Web (anonymized)
* **Reproducibility:** 100%

## Summary
An interactive action button does not respond when tapped or clicked, blocking the expected UI transition or action.

## Steps
1. Open the screen or view containing the interactive action button.
2. Tap or click directly on the button.
3. Observe whether any UI transition, action, or visual state change occurs.

## Actual
The button does not react to user interaction, and no action or visual feedback occurs.

## Expected
Tapping or clicking the button should trigger its intended action and provide clear visual feedback.

## Notes
Possible UI interaction block, overlapping element, or layout hit-area/event-handler issue.

# Enduroco App Changelog

This document tracks all significant changes, bug fixes, and feature additions to the Enduroco mobile application across different versions.

## Version 2.3.0 (In Development)

### Planned Fixes / Known Issues from v2.2.8
- iOS Chat keyboard gets stuck on screen (Persists according to Apr 15 testing)
- Training intensity thresholds show/update for both cycling/running even when only one is selected (Reported Apr 15)
- Error when updating daily duration with "time-capped" volume selection (Reported Apr 15)
- Cannot change training method (error message) (Reported Apr 15)
- Unable to log in to Strava using Gmail authentication (Not fixable - users should use OTP login)
- Typo in "strength" (showing as "strent") under plan (Could not reproduce in v2.2.8 - might be display width issue)
- Nothing happens after clicking "Ok" on intervals connecting page
- Subscription flow issues - stays on same page after processing
- Remove references to old api.enduroco.en everywhere.

## Version 2.2.8 (Released: April 16, 2024)
### Bug Fixes
- Fixed: Timezone is now editable
- Fixed: Black screen on Garmin Connect
- Fixed: Threshold not updating and showing error message
- Fixed: Black page when selecting any volume selection method

### Notes
- Released to address issues identified in v2.2.7 testing.
- Remaining known issues moved to v2.3.0 backlog.

## Version 2.2.7 (Testing: April 15, 2024)

### Known Issues (Identified April 15, 2024)
- Timezone is not editable (Fixed in v2.2.8)
- Unable to log in to Strava using Gmail authentication (Not fixable - users should use OTP login)
- Black screen on Garmin Connect (Fixed in v2.2.8)
- Typo in "strength" (showing as "strent") under plan (Could not reproduce in v2.2.8 - might be display width issue)
- Threshold not updating and showing error message (Fixed in v2.2.8)
- Black page when selecting any volume selection method (Fixed in v2.2.8)
- iOS Chat keyboard gets stuck on screen (Moved to v2.3.0)
- Nothing happens after clicking "Ok" on intervals connecting page (Moved to v2.3.0)
- Subscription flow issues - stays on same page after processing (Moved to v2.3.0)

### Notes
- Testing phase with multiple issues identified, addressed in v2.2.8 or moved to v2.3.0.

## Version 2.2.6 (Released: April 12, 2024)

### Bug Fixes
- Fixed various subscription-related issues identified in v2.2.3 and v2.2.5 testing, including the validity date display in settings.

### Notes
- This release focuses on stabilizing the subscription functionality.

---

## Version 2.2.5 (Building: April 12, 2024)

### Bug Fixes
- Fixed: "Unlock premium features" option removed from homepage for subscribed users.
- Fixed: Redundant "Sign In" link removed from the main page.
- Fixed: Subscription page now redirects properly after successful subscription.
- Fixed: Active accounts no longer show the "Unlock premium features" option.

### Notes
- Testing required for the new plan page added in v2.2.2/v2.2.3.
- "Welcome to Enduroco" message after every login is intentional for this build for testing purposes; planned improvements in next update.
- Issue: Subscribe option in settings not showing validity date needs verification (expected behavior: disappears after ~10s).

## Version 2.2.3 (Released for Testing: April 12, 2024)

### Bug Fixes
- Fixed critical in-app subscription bug introduced in v2.2.2.

### Known Issues (Identified April 12, 2024)
- "Unlock premium features" option still appears on homepage after subscription
- Subscribe option in settings doesn't display subscription validity date
- "Already have an account? Sign In" link on main page isn't working
- "Welcome to Enduroco" message appears after every login (should only show for new users)
- App stays on same page with "Subscribe now" button enabled after successful subscription
- Active accounts still showing "Unlock premium features" option

### Notes
- Released internally for testing before public release. Focus on verifying subscription functionality.

## Version 2.2.2 (Released: April 11, 2024)

### Bug Fixes
- Fixed crash on boot issue that was present in v2.2.1
- Addressed login frequency issues (users were being asked to log in too often)
- Fixed fitness-related bugs

### New Features
- Added new home screen design
- Improved calendar functionality
- Enhanced onboarding experience

### Known Issues
- Subscription functionality underwent major refactoring and may have issues (needs testing)

### Notes
- Released as an emergency fix for the crash in v2.2.1

## Version 2.2.1 (Released: [Date])

### Bug Fixes
- Fixed issue where app was asking for login very frequently and redirecting to website
- [Other fixes]

### Known Issues
- App crashes on boot for some users (fixed in v2.2.2)

---

*Note: This changelog should be updated with each new release. Include version number, release date, bug fixes, new features, and any known issues.*
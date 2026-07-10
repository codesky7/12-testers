# Google Play Production Access Checklist -- Closed Testing Preparation

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Home-README-blue" alt="Home"></a>
  <a href="./REQUIREMENTS.md"><img src="https://img.shields.io/badge/Previous-Requirements-blue" alt="Previous: Requirements"></a>
  <a href="./FAQ.md"><img src="https://img.shields.io/badge/Next-FAQ-orange" alt="Next: FAQ"></a>
</p>

---

## Table of Contents

- [How to Use This Checklist](#how-to-use-this-checklist)
- [Phase 1: Pre-Testing Preparation](#phase-1-pre-testing-preparation)
- [Phase 2: Tester Recruitment](#phase-2-tester-recruitment)
- [Phase 3: Closed Testing Track Setup](#phase-3-closed-testing-track-setup)
- [Phase 4: During Testing (Days 1-14)](#phase-4-during-testing-days-1-14)
- [Phase 5: Pre-Application Review](#phase-5-pre-application-review)
- [Phase 6: Production Access Application](#phase-6-production-access-application)
- [Phase 7: Post-Submission](#phase-7-post-submission)
- [Comprehensive Master Checklist](#comprehensive-master-checklist)

---

## How to Use This Checklist

This checklist is designed to be followed sequentially. Each phase builds on the previous one, and skipping steps increases your risk of rejection. Mark items as you complete them. If you encounter a problem, refer to the linked troubleshooting resources.

**Important**: The Google Play Console interface changes periodically. If a menu path or button name does not match what you see, check the official Google Play Console Help documentation for the most current navigation.

> **Read next:** [TROUBLESHOOTING.md](./TROUBLESHOOTING.md) -- Solutions for common issues at each phase.

---

## Phase 1: Pre-Testing Preparation

Complete these items before you begin recruiting testers or setting up your testing track.

### Account Setup

- [ ] Google Play Console account created ($25 one-time fee paid)
- [ ] Account email verified
- [ ] Two-factor authentication enabled (recommended for security)
- [ ] Account type confirmed (personal or organization)
- [ ] If personal account: confirmed you have no prior production app
- [ ] If organization account: D-U-N-S number verified

### App Preparation

- [ ] App builds and runs without crashing on at least 3 different devices
- [ ] Core features are functional (the app does something useful)
- [ ] App targets required API level (check current requirement: API 34+)
- [ ] App signed with upload key
- [ ] Android App Bundle (.aab) generated for release
- [ ] App version code and version name set appropriately
- [ ] ProGuard/R8 mapping file saved (if using obfuscation)
- [ ] Debug logging disabled or minimized
- [ ] No hardcoded test credentials or debug endpoints exposed
- [ ] App handles network errors gracefully
- [ ] App handles permission denials gracefully

### Content and Policy Preparation

- [ ] Privacy policy written and hosted at a publicly accessible URL
- [ ] Privacy policy covers all data collection, usage, and sharing
- [ ] Terms of service created (if applicable)
- [ ] All app content reviewed for policy compliance
- [ ] No copyrighted material used without permission
- [ ] No prohibited content (check Google Play Developer Policies)
- [ ] All third-party SDKs and libraries declared

### Store Listing Materials

- [ ] App icon created (512x512 PNG, adaptive icon format)
- [ ] Feature graphic created (1024x500 PNG)
- [ ] At least 2-4 screenshots captured showing actual app usage
- [ ] Screenshots meet minimum resolution requirements (320px min dimension)
- [ ] App name finalized (30 characters or fewer)
- [ ] Short description written (80 characters or fewer)
- [ ] Full description written (describes features and value proposition)
- [ ] App category selected
- [ ] Content rating questionnaire answers prepared

---

## Phase 2: Tester Recruitment

Recruiting 12 testers is often the hardest part. Start this phase early. If you are unable to find enough testers through your personal network, [TesterBee](https://testerbee.com/12-testers-for-google-play) offers a service that connects Android developers with real testers for Google Play closed testing, saving weeks of recruitment effort.

### Tester List Preparation

- [ ] At least 15-20 potential testers identified (buffer above the 12 minimum)
- [ ] Tester email addresses collected (must be Google accounts)
- [ ] Testers briefed on what is expected:
  - [ ] Must accept invitation via Google Play link
  - [ ] Must install the app from Google Play
  - [ ] Must open and use the app
  - [ ] Must keep the app installed for 14 consecutive days
  - [ ] Should use core features regularly
  - [ ] Should provide feedback (bugs, suggestions, issues)
- [ ] Communication channel established (email, chat group, Discord, etc.)
- [ ] Backup testers identified in case of dropouts

### Tester Diversity Check

- [ ] Testers are not all from the same geographic location (if possible)
- [ ] Testers use different device models and Android versions
- [ ] Testers are real individuals (not accounts you created)
- [ ] At least some testers have older Google accounts

### Google Group Setup (Recommended Method)

- [ ] Google Group created at groups.google.com
- [ ] Group name is descriptive (e.g., `your-app-name-testers`)
- [ ] Group set to "Restricted" (only managers can add members)
- [ ] All tester emails added to the group
- [ ] Group email address noted (needed for Play Console)

> **Read next:** [BEST_PRACTICES.md](./BEST_PRACTICES.md) -- Detailed strategies for tester recruitment and engagement.

---

## Phase 3: Closed Testing Track Setup

Set up your closed testing track in Google Play Console.

### Track Configuration

- [ ] Google Play Console opened, app selected
- [ ] Navigated to **Testing > Closed testing**
- [ ] Closed testing track created (or existing track selected)
- [ ] Track name set (e.g., "alpha" or "closed-testing")
- [ ] Country availability configured (include countries where testers are located)
- [ ] Tester management method selected:
  - [ ] Google Group method: group email entered
  - [ ] Individual email method: all 12+ emails entered

### Release Setup

- [ ] App Bundle (.aab) or APK uploaded to the closed testing track
- [ ] Release name set (e.g., "Closed Testing - Initial Release")
- [ ] Release notes written (describe what testers should focus on)
- [ ] Release reviewed for completeness (all required fields filled)

### Store Listing Setup (for Testing Track)

- [ ] App name entered
- [ ] Short description entered
- [ ] Full description entered
- [ ] App icon uploaded
- [ ] Feature graphic uploaded
- [ ] Screenshots uploaded (at least 2)
- [ ] Category and tags set
- [ ] Privacy policy URL entered
- [ ] Content rating questionnaire completed
- [ ] Data Safety section completed

### Final Checks Before Rollout

- [ ] All tester emails are correct and active
- [ ] Google Group membership is correct (all testers added)
- [ ] App version is the intended testing build
- [ ] No debug or test-only features are exposed
- [ ] Privacy policy URL is accessible and correct
- [ ] Data Safety declarations match actual data practices

### Start Rollout

- [ ] **Start rollout** button clicked
- [ ] Rollout confirmation received
- [ ] "In review" status noted (testing track updates still go through review)
- [ ] Review completion confirmed (typically 1-3 hours)
- [ ] Track status shows as "Available" or "Published"

---

## Phase 4: During Testing (Days 1-14)

Monitor your testing progress and maintain tester engagement.

### Day 1: Kickoff

- [ ] Confirmed all testers received invitation emails
- [ ] Confirmed testers are accepting invitations
- [ ] Confirmed app is downloadable from Google Play for testers
- [ ] Sent welcome message to testers with expectations
- [ ] Noted the official start date of testing

### Days 1-7: Active Monitoring

- [ ] Daily check of installation count in Play Console
- [ ] Daily check of crash reports (Quality > Android vitals > Crashes)
- [ ] Daily check of ANR reports (Quality > Android vitals > ANRs)
- [ ] Feedback from testers collected and organized
- [ ] Any critical bugs identified and prioritized
- [ ] Tester engagement tracked (who is using the app, who is not)

### Mid-Point (Day 7)

- [ ] Mid-point check-in message sent to all testers
- [ ] Tester list verified: 12+ testers still installed and engaged
- [ ] Dropouts identified and replacement testers added if below 12
- [ ] Any mid-testing updates planned based on first-week feedback
- [ ] Crash rate reviewed and compared to targets

### Days 8-14: Continued Monitoring

- [ ] Continued daily monitoring of installations and crashes
- [ ] Bug fix updates published if needed
- [ ] Tester feedback addressed (at minimum, acknowledge receipt)
- [ ] Engagement maintained through reminders and updates

### Day 14: Testing Period Completion

- [ ] Confirmed 14 consecutive days reached
- [ ] Confirmed 12+ testers throughout the period
- [ ] Final feedback collected from testers
- [ ] Crash and ANR data reviewed for the full period
- [ ] Decision made: extend testing or proceed to application

---

## Phase 5: Pre-Application Review

Before submitting your production access application, verify everything.

### Tester Metrics Review

- [ ] 12+ testers participated (confirmed in Play Console dashboard)
- [ ] 14+ consecutive days of testing completed
- [ ] Testers showed genuine engagement (not just install-and-forget)
- [ ] No suspicious patterns (mass installs/uninstalls, zero engagement)
- [ ] Tester feedback documented and summarized

### App Quality Review

- [ ] Crash rate is below 1% over the testing period
- [ ] ANR rate is below 0.47% over the testing period
- [ ] No critical bugs remain unfixed
- [ ] All core features work correctly
- [ ] App performs well on a variety of devices

### Store Listing Review

- [ ] All required elements present and correct
- [ ] Privacy policy still accessible and accurate
- [ ] Data Safety section is accurate
- [ ] Screenshots represent the current app version
- [ ] Description accurately describes the app

### Policy Compliance Review

- [ ] No policy violations detected during testing
- [ ] All permissions are necessary and justified
- [ ] Content rating is accurate
- [ ] No impersonation or misleading claims

### Application Preparation

- [ ] Testing process summary written (how testers were recruited, process followed)
- [ ] Feedback summary prepared (key themes, issues identified)
- [ ] Changes-made summary prepared (bugs fixed, improvements made)
- [ ] Any supporting screenshots or documentation gathered
- [ ] Answers to likely review questions prepared

---

## Phase 6: Production Access Application

Submit your application through Google Play Console.

### Navigation

- [ ] Opened Google Play Console
- [ ] Navigated to **Grow > Production access**
- [ ] Reviewed the dashboard showing testing status

### Application Submission

- [ ] All required fields filled honestly and completely
- [ ] Testing process described in detail
- [ ] Feedback and changes described with specifics (not generic statements)
- [ ] Application reviewed for accuracy before submission
- [ ] Application submitted
- [ ] Confirmation message received
- [ ] Expected review timeline noted (typically 3-7 days)

---

## Phase 7: Post-Submission

### During Review

- [ ] Email monitored for Google follow-up questions
- [ ] Play Console notifications checked daily
- [ ] Response prepared for possible questions (have your data ready)
- [ ] No changes made to the app during review (unless requested by Google)
- [ ] No attempts to contact Google support about review status (unless beyond 7 days)

### If Approved

- [ ] Production release created in Play Console
- [ ] Rollout strategy selected (full rollout or staged)
- [ ] Production release submitted for review
- [ ] Release monitoring plan in place
- [ ] Celebrate -- you have published your first app

### If Rejected

- [ ] Rejection reasons carefully read and understood
- [ ] Each reason addressed with specific actions
- [ ] Additional testing completed if required
- [ ] New evidence gathered to support reapplication
- [ ] Application resubmitted with substantive changes
- [ ] Do not resubmit without making changes

> **Read next:** [COMMON_REJECTIONS.md](./COMMON_REJECTIONS.md) -- Understand and address rejection reasons.

---

## Comprehensive Master Checklist

Copy this section for quick reference. Every box must be checked before submitting.

### Account & Setup
- [ ] Play Console account created and verified
- [ ] Account type confirmed
- [ ] $25 fee paid

### Testers
- [ ] 15+ potential testers identified
- [ ] Testers briefed on expectations
- [ ] Google Group created with all testers
- [ ] Communication channel established

### App
- [ ] App functional on multiple devices
- [ ] Target API level met
- [ ] Signed with upload key
- [ ] .aab generated
- [ ] Debug logging cleaned

### Store Listing
- [ ] App icon uploaded (512x512)
- [ ] Feature graphic uploaded (1024x500)
- [ ] 2+ screenshots uploaded
- [ ] Description written
- [ ] Category selected
- [ ] Privacy policy URL entered
- [ ] Content rating completed
- [ ] Data Safety completed

### Testing Track
- [ ] Closed testing track created
- [ ] Testers added (Group or individual)
- [ ] Release uploaded and reviewed
- [ ] Rollout started
- [ ] Invitations sent

### 14-Day Testing
- [ ] 14 consecutive days reached
- [ ] 12+ testers throughout
- [ ] Crash rate < 1%
- [ ] ANR rate < 0.47%
- [ ] Feedback collected and documented

### Application
- [ ] Testing process described
- [ ] Feedback summary prepared
- [ ] Changes summary prepared
- [ ] Application submitted

---

<p align="center">
  <a href="./README.md">Home</a> |
  <a href="./REQUIREMENTS.md">Requirements</a> |
  <a href="./FAQ.md">FAQ</a> |
  <a href="./COMMON_REJECTIONS.md">Common Rejections</a> |
  <a href="./TROUBLESHOOTING.md">Troubleshooting</a>
</p>

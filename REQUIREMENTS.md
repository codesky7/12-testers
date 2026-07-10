# Google Play 12 Testers Requirement -- The Complete Guide

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Home-README-blue" alt="Home"></a>
  <a href="./CHECKLIST.md"><img src="https://img.shields.io/badge/Next-Checklist-green" alt="Next: Checklist"></a>
  <a href="./FAQ.md"><img src="https://img.shields.io/badge/Also-FAQ-orange" alt="Also: FAQ"></a>
</p>

---

## Table of Contents

- [Overview](#overview)
- [Who Must Comply](#who-must-comply)
- [The Core Requirements](#the-core-requirements)
- [Personal vs Organization Accounts](#personal-vs-organization-accounts)
- [Tester Eligibility](#tester-eligibility)
- [The 14-Day Rule](#the-14-day-rule)
- [App Readiness Requirements](#app-readiness-requirements)
- [Store Listing Requirements](#store-listing-requirements)
- [Privacy and Policy Requirements](#privacy-and-policy-requirements)
- [Technical Requirements](#technical-requirements)
- [Production Access Application Requirements](#production-access-application-requirements)
- [What Google Checks During Review](#what-google-checks-during-review)
- [Regional Differences](#regional-differences)
- [Frequently Asked Questions About Requirements](#frequently-asked-questions-about-requirements)

---

## Overview

Google Play's closed testing requirement is the single biggest policy change for new Android developers in years. If you are publishing an app through a new personal developer account, you **must** complete a closed testing phase with at least **12 testers** over a minimum of **14 consecutive days** before your app can go live in production.

This document covers every requirement in detail: who must comply, what testers must do, how the 14-day period works, what your app needs before testing begins, and what Google checks during the production access review. Use this as your authoritative reference before, during, and after your closed testing phase.

> **Read next:** [CHECKLIST.md](./CHECKLIST.md) -- A step-by-step checklist to ensure you meet every requirement before applying.

---

## Who Must Comply

The closed testing requirement applies to the following account types and scenarios:

### Must Comply

| Account Type | Requirement |
|-------------|-------------|
| New personal developer accounts (created after Nov 13, 2023) | Must complete closed testing before first production release |
| Dormant personal accounts reactivated after Nov 13, 2023 | Must complete if no prior production app exists |
| Personal accounts with prior production access revoked | Must re-complete closed testing |
| Personal accounts with only internal testing history | Must complete closed testing before production |

### Exempt From Requirement

| Account Type | Exemption Reason |
|-------------|-----------------|
| Organization accounts with verified D-U-N-S number | Organization identity already verified |
| Personal accounts with an existing published production app | Grandfathered -- requirement targets new developers |
| Apps that only use internal or open testing tracks | Requirement applies only to production access |
| Accounts created before November 13, 2023 with production history | Pre-policy accounts are exempt |

### Special Cases

**Account type conversion**: If you convert a personal account to an organization account after the policy date but before publishing your first production app, you may still need to complete closed testing. Google evaluates based on your account's publishing history, not its current type.

**Multiple apps**: Once you have successfully completed closed testing and published one app to production, subsequent apps on the same account do **not** require a new closed testing phase. The requirement is per-account, not per-app.

**Account reinstatement**: If your production access was removed due to policy violations, you will likely need to complete closed testing again when reapplying.

---

## The Core Requirements

The Google Play closed testing requirement has four non-negotiable components:

### 1. Minimum 12 Testers

You must recruit at least **12 unique testers** who opt in to your closed testing track. Each tester must:

- Use a valid Google account (Gmail or Google Workspace)
- Accept the closed testing invitation
- Install the app from Google Play
- Open and use the app

Google does not specify an upper limit for testers. Having more than 12 may strengthen your application, particularly if testers are diverse in terms of geography and device types.

### 2. Minimum 14 Consecutive Days

The testing period must span at least **14 consecutive calendar days**. This period starts when testers have installed and used the app, not when the testing track is created. Key details:

- The 14 days cannot be split -- it must be one continuous block
- Weekends and holidays count toward the 14 days
- Google may require longer if the review team determines testing was insufficient
- There is no maximum testing duration -- longer testing is generally viewed positively

### 3. Genuine Tester Engagement

Google expects testers to meaningfully engage with your app. While the exact criteria are not public, insufficient engagement is one of the most common rejection reasons. Testers should:

- Open the app multiple times during the 14-day period
- Use core features of the app
- Keep the app installed throughout the testing period
- Ideally provide feedback or report issues

### 4. Successful Production Access Application

Meeting the tester count and duration alone is not sufficient. You must also submit a production access application that Google approves. The application requires you to:

- Describe your testing process
- Share what feedback you received
- Explain what changes you made based on feedback
- Confirm policy compliance

---

## Personal vs Organization Accounts

### Personal Accounts

Personal developer accounts are for individual developers. Key characteristics:

- Created with an individual Google account (typically a Gmail address)
- One-time $25 registration fee
- Your legal name appears on the Play Store listing
- Required to complete closed testing before production

### Organization Accounts

Organization accounts are for registered businesses and organizations. Key characteristics:

- Require a valid D-U-N-S number for verification
- One-time $25 registration fee
- Organization name appears on the Play Store listing
- Exempt from the closed testing requirement (organization identity verification serves a similar trust function)

### Should You Create an Organization Account?

If you have a legally registered business with a D-U-N-S number, creating an organization account can bypass the closed testing requirement entirely. However, the tradeoff is:

| Personal Account | Organization Account |
|-----------------|---------------------|
| 12 testers, 14 days required | No closed testing required |
| Faster account setup | D-U-N-S verification takes 1-5 days |
| Your name on Play Store | Business name on Play Store |
| No business registration needed | Requires D-U-N-S number |

> **Read next:** [FAQ.md](./FAQ.md) -- Answers to common questions about account types and requirements.

---

## Tester Eligibility

### Who Can Be a Tester?

Testers must be real people with valid Google accounts. There are no explicit geographic restrictions, but testers should meet these criteria:

- Have a Google account (Gmail or Google Workspace)
- Be able to access Google Play on an Android device
- Accept your closed testing invitation
- Install and use your app

### Who Cannot Be a Tester?

- **You (the developer)**: Your own Google account does not count toward the 12
- **Automated accounts/bots**: Google's review can detect non-human usage patterns
- **Duplicate accounts**: Multiple accounts controlled by the same person may be flagged
- **Accounts created solely for testing**: Brand new Google accounts created just to serve as testers may raise flags

### Tester Management Best Practices

- Use a Google Group to manage your tester list
- Add 15-20 testers to account for potential dropouts
- Communicate expectations clearly -- testers need to know they must stay engaged for 14 days
- Send reminders at day 1, day 7, and day 13 to maintain engagement
- If recruiting testers yourself proves difficult, services like [TesterBee](https://testerbee.com) specialize in connecting developers with genuine testers for Google Play closed testing, handling the recruitment and engagement management for you

> **Read next:** [BEST_PRACTICES.md](./BEST_PRACTICES.md) -- Strategies for recruiting and retaining 12 testers.

---

## The 14-Day Rule

### When Does the Clock Start?

The 14-day countdown begins when all conditions are met:

1. Your closed testing track is published and active
2. Testers have accepted invitations
3. Testers have installed the app
4. Testers have opened and used the app

Google's system tracks these metrics. The "Grow > Production access" dashboard in Play Console shows your progress.

### What Breaks the 14-Day Streak?

While Google does not publish exact failure criteria, the following scenarios are risky:

- **Mass uninstalls**: Multiple testers uninstalling around the same time
- **Zero engagement days**: Days where no testers use the app
- **Tester count dropping below 12**: Even temporarily
- **Crash spikes**: High crash rates during the testing period

### Can I Make Updates During the 14 Days?

Yes. You can and should update your app during the testing period to fix bugs and respond to feedback. However, each update:

- Must pass Google Play's standard review (typically 1-3 hours for testing track updates)
- Does not reset the 14-day counter
- May cause a brief dip in tester engagement while the update propagates

### What Happens After 14 Days?

The 14-day minimum is just that -- a minimum. You are not required to submit your production access application on day 15. Many developers choose to extend testing to:

- Gather more feedback
- Fix additional bugs
- Build confidence in app stability
- Strengthen their production access application

> **Read next:** [TIMELINE.md](./TIMELINE.md) -- A detailed day-by-day plan for the 14-day testing period.

---

## App Readiness Requirements

Before starting closed testing, your app must meet basic quality standards. An app that crashes on launch or has no functional features will likely be rejected.

### Functional Requirements

- The app must be functional -- it should do something useful
- Core features must work as described in the store listing
- The app should not crash on launch on common devices
- The app should handle network errors gracefully (if it uses network access)

### Content Requirements

- All content must comply with Google Play Developer Policies
- No prohibited content (hate speech, violence, illegal activities, etc.)
- No impersonation of other apps, brands, or services
- No deceptive behavior or functionality

### Performance Requirements

While Google does not publish specific performance thresholds for closed testing, poor performance will hurt your application:

- Crash rate: Aim for less than 1% crash rate
- ANR (Application Not Responding) rate: Aim for less than 0.47%
- App size: Keep it reasonable (under 150MB for most apps)
- Startup time: The app should launch within a few seconds

---

## Store Listing Requirements

Your app's store listing must be complete and policy-compliant, even during closed testing. Google reviews the listing as part of the production access evaluation.

### Required Elements

| Element | Requirement |
|---------|------------|
| App name | 30 characters or fewer, unique and descriptive |
| Short description | 80 characters or fewer, summarizes the app |
| Full description | Describes what the app does, its key features |
| App icon | 512x512 PNG, meets design guidelines |
| Feature graphic | 1024x500 PNG, used on the store listing |
| Screenshots | At least 2, showing actual app usage |
| Category | Appropriate category and tags |
| Privacy policy URL | Valid, accessible URL |
| Content rating | Completed content rating questionnaire |

### Common Store Listing Issues

- **Misleading descriptions**: Descriptions must accurately reflect what the app does
- **Keyword stuffing**: Don't pack irrelevant keywords into the description
- **Missing privacy policy**: Required for all apps that collect any data
- **Low-quality screenshots**: Screenshots should be clear and representative
- **Unanswered content rating questionnaire**: Must be completed before review

---

## Privacy and Policy Requirements

### Privacy Policy

A privacy policy is mandatory for all apps, even during closed testing, if your app:

- Collects any personal or sensitive user data
- Accesses device permissions (camera, location, contacts, etc.)
- Uses analytics, advertising, or third-party SDKs
- Communicates with any server or API

Your privacy policy must:

- Be hosted at a valid, publicly accessible URL
- Disclose what data you collect and why
- Explain how data is used, stored, and shared
- Include a contact method for privacy questions
- Be linked from both the Play Console and within your app

### Data Safety Section

The Data Safety section in Play Console must be completed honestly. It asks about:

- Data types collected (location, personal info, financial info, etc.)
- Data usage purposes (app functionality, analytics, advertising, etc.)
- Data sharing practices (with third parties, service providers, etc.)
- Data security practices (encryption, deletion requests, etc.)

Inaccurate Data Safety declarations can result in rejection or even account suspension.

### Permissions

Your app should only request permissions it genuinely needs:

- Declare all permissions in the manifest
- Provide runtime permission requests with clear explanations
- Avoid requesting unnecessary permissions
- Be prepared to justify each permission in the production access application

---

## Technical Requirements

### App Signing

- Apps must be signed with an upload key (managed in Play Console)
- Google manages the app signing key by default (Play App Signing)
- The signing key cannot be changed after the first release

### Target API Level

- New apps must target API level 33 (Android 13) or higher as of August 2023
- New apps must target API level 34 (Android 14) or higher as of August 2024
- Check the latest target API requirements before submitting

### App Bundle vs APK

- Android App Bundle (.aab) is the recommended format
- APKs are accepted but may have size limitations
- App Bundles enable Google Play's dynamic delivery optimizations

---

## Production Access Application Requirements

When you apply for production access, you will be asked to provide information about your testing process. Prepare the following:

### Testing Process Description

Describe:

- How you recruited testers (personal network, communities, etc.)
- How many testers participated
- How you communicated with testers
- The duration of the testing period

### Feedback Summary

Summarize:

- Key feedback themes from testers
- Specific issues that were identified
- How you prioritized and addressed feedback
- Any tester suggestions you plan to implement in future updates

### Changes Made

List:

- Bugs fixed during the testing period
- UI/UX improvements based on tester feedback
- Performance optimizations
- Any feature changes driven by testing

### Policy Compliance Confirmation

You will need to confirm that your app:

- Complies with all Google Play Developer Policies
- Has accurate Data Safety declarations
- Has a valid privacy policy
- Meets target API level requirements

---

## What Google Checks During Review

Google's review process for production access is not fully transparent, but based on community experience, reviewers evaluate:

### Automated Checks

- Tester count and engagement metrics
- Installation and uninstallation patterns
- Crash and ANR rates
- Policy compliance scans
- Store listing completeness

### Manual Review

- App functionality and quality
- Store listing accuracy
- Privacy policy adequacy
- Data Safety section accuracy
- Overall app value proposition

### Red Flags That Trigger Additional Scrutiny

- Sudden spikes in testers near the application date
- All testers from the same geographic region
- All testers using the same device model
- No tester engagement after initial installation
- App functionality too minimal to justify testing
- Identical or near-identical store listing to other apps

---

## Regional Differences

Google Play's closed testing requirement applies globally, but there are regional nuances:

### Regional Tester Availability

- Testers can be located anywhere in the world
- If your app targets a specific country, having testers in that country is beneficial
- Language barriers may affect feedback quality

### App Availability by Country

- Your closed testing track can be limited to specific countries
- Testers need a Google Play account associated with an available country
- Consider making the testing track available in multiple countries to broaden your tester pool

---

## Frequently Asked Questions About Requirements

### Can I use the same testers for multiple apps?

Yes, but Google may view identical tester lists across multiple apps with suspicion. It is better to have some variety, especially if you are publishing many apps in a short period.

### What if a tester uninstalls mid-way through?

Do not panic. If you have 15+ testers and one uninstalls, you still meet the 12-tester minimum. If the count drops below 12, recruit replacements and extend the testing period to ensure 14 continuous days.

### Can I test for more than 14 days?

Yes. Longer testing periods with sustained engagement strengthen your application. There is no downside to testing longer, as long as your testers remain engaged.

### Does the 14-day counter reset if I publish an update?

No. Publishing updates does not reset the counter, though a major update may briefly affect tester engagement.

### Can I switch from personal to organization account mid-testing?

This is not straightforward. If you have not yet completed closed testing, switching account types may require you to start over. If you already have a D-U-N-S number, consider creating an organization account from the start.

---

## Summary Checklist

Before submitting your production access application, verify:

- [ ] 12+ testers opted in and installed your app
- [ ] 14+ consecutive days of testing completed
- [ ] Testers have used core app features
- [ ] Crash rate is below 1%
- [ ] Store listing is complete with all required elements
- [ ] Privacy policy is published and accessible
- [ ] Data Safety section is accurate and complete
- [ ] App targets required API level
- [ ] All Google Play policies are followed
- [ ] Feedback has been collected and addressed
- [ ] Production access application answers are prepared

> **Read next:** [CHECKLIST.md](./CHECKLIST.md) -- Verify every requirement before you submit.

---

<p align="center">
  <a href="./README.md">Home</a> |
  <a href="./CHECKLIST.md">Checklist</a> |
  <a href="./FAQ.md">FAQ</a> |
  <a href="./COMMON_REJECTIONS.md">Common Rejections</a> |
  <a href="./BEST_PRACTICES.md">Best Practices</a>
</p>

# Google Play Closed Testing FAQ -- Frequently Asked Questions

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Home-README-blue" alt="Home"></a>
  <a href="./CHECKLIST.md"><img src="https://img.shields.io/badge/Previous-Checklist-blue" alt="Previous: Checklist"></a>
  <a href="./COMMON_REJECTIONS.md"><img src="https://img.shields.io/badge/Next-Common%20Rejections-orange" alt="Next: Common Rejections"></a>
</p>

---

## Table of Contents

- [General Questions](#general-questions)
- [Tester Requirements](#tester-requirements)
- [The 14-Day Period](#the-14-day-period)
- [Account Questions](#account-questions)
- [App and Store Listing Questions](#app-and-store-listing-questions)
- [Production Access Application](#production-access-application)
- [Rejection and Reapplication](#rejection-and-reapplication)
- [Troubleshooting Common Problems](#troubleshooting-common-problems)
- [Pricing and Payment](#pricing-and-payment)
- [Timeline and Strategy](#timeline-and-strategy)

---

## General Questions

### What is Google Play closed testing?

Closed testing is a Google Play testing track that allows you to distribute your app to a limited, invite-only group of testers. Unlike open testing (where anyone can join) or internal testing (limited to your organization), closed testing lets you control exactly who tests your app. Since November 2023, new personal developer accounts must complete closed testing with at least 12 testers over 14 days before publishing to production.

### When did this requirement start?

The policy was announced in November 2023 and applies to new personal developer accounts created on or after November 13, 2023. If your account was created before this date and already has a published production app, you are grandfathered in and do not need to complete closed testing.

### Why does Google require 12 testers?

Google introduced this requirement to improve app quality on the Play Store. By requiring developers to test with real users before publishing, Google aims to reduce spam, malware, low-quality apps, and abandoned software. The 12-tester minimum creates a meaningful quality gate without being unreasonably difficult for solo developers.

### Is closed testing the same as beta testing?

Closed testing is one form of beta testing. Google Play offers three testing tracks: internal testing (for your team), closed testing (invite-only, for selected testers), and open testing (public beta, anyone can join). When people say "Google Play beta testing," they are often referring to either closed or open testing. The production access requirement specifically mandates closed testing.

---

## Tester Requirements

### Who can be a tester?

Anyone with a Google account (Gmail or Google Workspace) who can access Google Play on an Android device can be a tester. Testers do not need to be developers or have any technical expertise. They simply need to accept your invitation, install the app, and use it.

### Can I be one of my 12 testers?

No. Your own Google account (the developer account or any account you control) does not count toward the 12-tester minimum. Google expects testers to be independent users who can provide unbiased feedback.

### Can my family members be testers?

Yes, family members can be testers as long as they have their own Google accounts and are willing to install and use your app for the full 14 days. Personal connections are one of the most common and reliable sources of testers.

### Do testers need to be in the same country as me?

No. Testers can be located anywhere in the world. However, you should configure your closed testing track to be available in the countries where your testers are located. If your app targets a specific market, having testers in that market can be beneficial.

### How many testers should I recruit?

Recruit at least 15-20 testers to have a buffer above the 12-tester minimum. Testers may drop out, uninstall, or lose interest. Having extras ensures you stay above 12 throughout the 14-day period.

### Can I use the same testers for multiple apps?

Technically yes, but Google may view identical tester lists across multiple apps with suspicion. If you publish multiple apps, try to have some tester variety. Using the exact same 12 testers for every app may raise red flags during review.

### How do I find 12 testers?

The most effective methods are:
1. Personal network (friends, family, colleagues, classmates)
2. Developer communities (Reddit r/androiddev, Discord servers, Telegram groups)
3. Social media (X/Twitter, LinkedIn, Facebook groups)
4. Testing exchange communities where developers swap testing
5. Paid testing services

If finding 12 engaged testers on your own feels overwhelming, [TesterBee](https://testerbee.com) provides a managed service specifically for Google Play's 12 tester requirement -- they handle tester recruitment and engagement so you can focus on your app.

For detailed strategies, see [BEST_PRACTICES.md](./BEST_PRACTICES.md).

---

## The 14-Day Period

### When does the 14-day countdown start?

The countdown starts when your closed testing track is live and testers have installed and begun using your app. It does not start when you create the testing track or upload the build. Check the "Grow > Production access" dashboard in Play Console for your progress.

### What happens if a tester uninstalls during the 14 days?

If a tester uninstalls, you lose their contribution to the engagement metrics. If your total engaged tester count drops below 12, you need to recruit replacement testers. The 14-day clock does not reset, but you need continuous engagement from at least 12 testers.

### Can I extend testing beyond 14 days?

Yes, and many developers do. Longer testing periods with sustained engagement can strengthen your production access application. There is no maximum testing duration, and Google generally views extended testing positively.

### What if my app has no new testers after day 14?

You can still apply for production access. The requirement is that 12 testers engaged for at least 14 days -- not that they continue beyond that point. However, make sure your tester metrics still look legitimate at the time of application.

### Do weekends and holidays count toward the 14 days?

Yes. The 14 days are calendar days, not business days. Weekends and holidays count normally. Google's automated systems track the time continuously.

### Can I pause testing and resume later?

No. The 14 days must be consecutive. Pausing the testing track or removing it and recreating it will reset the clock. Plan for an uninterrupted 14-day period from the start.

---

## Account Questions

### Do organization accounts need closed testing?

No. Organization accounts (verified with a D-U-N-S number) are exempt from the closed testing requirement. The organization verification serves as a trust signal that substitutes for the closed testing requirement.

### Can I convert my personal account to an organization account?

Yes, you can convert account types in Play Console. However, if you have not yet completed closed testing and published a production app, converting mid-process may not exempt you from the requirement. Google evaluates based on publishing history, not just account type. If you already have a D-U-N-S number, creating an organization account from the start is the better approach.

### How do I get a D-U-N-S number?

D-U-N-S numbers are issued by Dun & Bradstreet. You can request one through their website (dnb.com). The process typically takes 1-5 business days and is free for businesses that need it for Google Play verification. You will need to provide your legal business name, address, and contact information.

### Do I need a new closed testing phase for each app?

No. Once you have successfully completed closed testing and published one app to production, you do not need to repeat the process for subsequent apps on the same account. The requirement is per-account, not per-app.

### What if my production access was revoked?

If Google removed your production access (typically due to policy violations), you will likely need to complete closed testing again when reapplying. Review the specific reasons for revocation and address them before starting a new testing phase.

---

## App and Store Listing Questions

### What if my app is very simple?

Even simple apps must go through closed testing. If your app is extremely minimal (e.g., a single-screen calculator), be aware that Google may scrutinize it more closely during the production access review and question whether it provides sufficient value to users.

### Do I need a privacy policy for my closed testing app?

If your app collects any data or accesses any device permissions, yes. A privacy policy is mandatory for any app that handles user data, even during closed testing. Host it at a publicly accessible URL and link it from both your Play Console listing and within the app.

### Can I update my app during the 14-day testing period?

Yes. You can and should publish updates to fix bugs and address tester feedback during the testing period. Each update goes through Google's standard review (typically 1-3 hours for testing tracks) and does not reset the 14-day counter.

### What if my app crashes during testing?

Fix the crashes as quickly as possible. A crash rate above 1% is a common reason for production access rejection. Publish a fix, monitor crash reports in Play Console under Quality > Android vitals > Crashes, and be prepared to explain what you fixed in your production access application.

### Do I need to complete the content rating questionnaire for testing?

Yes. The content rating questionnaire must be completed before your testing track can go live. Answer honestly based on your app's actual content and functionality. Inaccurate ratings can result in rejection or app removal.

---

## Production Access Application

### Where do I apply for production access?

In Google Play Console, navigate to **Grow > Production access**. This section shows your testing progress dashboard and provides the application form when you are ready to apply.

### What kind of questions are on the application?

The application asks about:
- Your testing process (how you recruited testers, how you communicated)
- Feedback received from testers
- Changes made based on feedback
- Policy compliance confirmation
- App functionality and value proposition

Answer honestly and provide specific details. Generic or vague answers are more likely to result in rejection.

### How long does the review take?

Most reviews are completed within 3-7 business days. Some may take longer during high-volume periods. If your review exceeds 7 days, you can check the status in Play Console. Avoid contacting support about review status before day 7, as this will not speed up the process.

### Can I make changes to my app while the application is under review?

It is best to avoid making changes during the review period unless Google specifically requests them. Changes during review can complicate the process and may delay a decision.

### What happens after I am approved?

Once approved, you can create a production release. Navigate to **Production** in Play Console, create a release, upload your App Bundle, and submit it for review. The production release itself also goes through standard app review, but you no longer need closed testing for this account.

---

## Rejection and Reapplication

### What are the most common rejection reasons?

1. **Insufficient tester engagement**: Testers installed but did not meaningfully use the app
2. **Too few testers**: Less than 12 testers consistently throughout the period
3. **Testing period too short**: Less than 14 consecutive days of testing
4. **App crashes or instability**: High crash rates or ANR rates
5. **Incomplete store listing**: Missing elements or inaccurate descriptions
6. **Policy violations**: Content or behavior that violates Google Play policies

For detailed solutions, see [COMMON_REJECTIONS.md](./COMMON_REJECTIONS.md).

### My application was rejected. What should I do?

1. Read the rejection message carefully -- it usually contains specific reasons
2. Address each reason with concrete actions
3. Gather evidence of the changes you made
4. Run additional testing if needed
5. Resubmit with a thorough explanation of what changed

Do not resubmit without making substantive changes. Repeated identical applications may be flagged.

### How many times can I reapply?

There is no published limit on reapplications. However, each application should reflect genuine improvements and address the previous rejection reasons. Multiple rejections without substantive changes may harm your credibility with the review team.

### Can I appeal a rejection?

Google Play does not have a formal appeals process specifically for production access rejections. The practical approach is to address the rejection reasons and reapply. If you believe the rejection was in error, you can contact Google Play Developer Support, but this is rarely successful unless there is clear evidence of a mistake.

---

## Troubleshooting Common Problems

### Testers cannot find or install my app

Common causes:
- The testing track is still under review (wait 1-3 hours)
- The tester's Google account is not added to the tester list
- The tester's country is not included in your track's availability
- The tester is using the wrong Google account on their device
- The opt-in link has expired or was not used correctly

See [TROUBLESHOOTING.md](./TROUBLESHOOTING.md) for detailed solutions.

### Google Play Console shows 0 installs

Possible reasons:
- The release is still under review
- The tracker has not updated yet (can take up to 24 hours)
- The testing track is not properly configured
- Your App Bundle/APK has issues preventing installation

### The production access dashboard shows incomplete status

This usually means the system has not yet detected sufficient tester engagement or duration. Wait 24-48 hours after meeting all requirements, as the dashboard may have a reporting delay. If it remains incomplete after 48 hours, check your tester metrics carefully.

### I suspect my testers are not being counted

Ensure that:
- Testers accepted the invitation through the Play Store link (not just via email)
- Testers installed from Google Play (not a sideloaded APK)
- Testers are using the correct Google account
- Testers opened the app at least once after installation

---

## Pricing and Payment

### How much does a Google Play Console account cost?

A one-time registration fee of $25 USD. There are no recurring fees for maintaining a developer account.

### Do testers have to pay for the app?

No. Apps in closed testing are free for testers, regardless of whether you plan to charge for the production version. You cannot charge testers during closed testing.

### Can I offer incentives to testers?

You can offer incentives, but be transparent about it. If you pay testers or offer rewards, consider how this might look during Google's review. The focus should remain on genuine testing and feedback, not on compensating people to install and forget the app.

---

## Timeline and Strategy

### How long does the entire process take?

| Scenario | Duration |
|----------|----------|
| Best case (testers ready on day 1, no issues) | ~18 days |
| Typical (recruitment + testing + review) | 4-6 weeks |
| Worst case (recruitment issues, rejection, reapplication) | 8-12 weeks |

### What is the fastest way to get through closed testing?

1. Start recruiting testers before your app is ready
2. Have your store listing materials prepared in advance
3. Fix all known bugs before starting testing
4. Maintain active communication with testers
5. Apply for production access immediately after day 14

### Should I test for exactly 14 days or longer?

Longer is generally better. 14 days is the minimum, and Google's reviewers may view a longer testing period more favorably. Many developers test for 3-4 weeks to gather sufficient feedback and demonstrate sustained engagement.

### What if my app is time-sensitive?

If you have a hard launch deadline, plan backward:
- Launch date minus 7 days = Production access application
- Production access application minus 14-21 days = Closed testing start
- Closed testing start minus 1-4 weeks = Tester recruitment

Start the process at least 6-8 weeks before your target launch date.

### Is there any way to bypass the closed testing requirement?

Only by using an organization account with a verified D-U-N-S number. There is no other legitimate way to skip closed testing for a new personal account. Attempts to circumvent the requirement (fake testers, automated installations) risk account suspension.

---

## Additional Questions

### Does the closed testing requirement apply to instant apps?

Yes. Instant apps published through new personal accounts are subject to the same closed testing requirement before they can reach production.

### Does the requirement apply to app updates?

No. The closed testing requirement applies only to the first production release from a new personal account. Once you have a published production app, subsequent updates do not require closed testing.

### What if my app is a game?

Games follow the same closed testing requirements as any other app. There is no special exemption or separate process for games on Google Play.

### Can I reuse testing data from another platform?

If you previously tested your app on another platform (e.g., iOS TestFlight), that testing does not count toward Google Play's closed testing requirement. You must complete the full 14-day closed testing on Google Play with Android users.

---

<p align="center">
  <a href="./README.md">Home</a> |
  <a href="./REQUIREMENTS.md">Requirements</a> |
  <a href="./CHECKLIST.md">Checklist</a> |
  <a href="./COMMON_REJECTIONS.md">Common Rejections</a> |
  <a href="./TROUBLESHOOTING.md">Troubleshooting</a> |
  <a href="./RESOURCES.md">Resources</a>
</p>

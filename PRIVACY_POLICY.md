# Privacy Policy - Pawsitively Healthy

**Last Updated: March 20, 2026**

## Introduction

Pawsitively Healthy ("we," "our," or "the app") is a pet care tracking application for iOS, watchOS, and home screen widgets. This Privacy Policy explains how your information is collected, used, and shared when you use Pawsitively Healthy.

## Information We Collect

### Account Information

Pawsitively Healthy uses your Apple iCloud account for authentication and data synchronization. We do not create separate user accounts or collect your name, email address, or password directly. Your iCloud account identifier is used solely to associate your data with your devices.

### Pet Information

You may provide the following information about your pets:

- Name, species, and breed
- Date of birth and weight
- Photos (selected from your device photo library)
- Notes

### Health and Care Data

The app collects pet health and care data that you choose to enter, including:

- Care activity logs (feeding, water intake, walks, grooming, vet visits, playtime, daycare, litter box, and weight records)
- Breathing rate measurements
- Medication details (name, dosage, form, frequency, and quantity administered)
- Nutritional information, calorie tracking, and daily goals
- Food product records with serving sizes and unit conversions
- Water intake amounts

### Reminders

You may create reminders that include titles, categories, recurrence schedules, priority levels, and notification preferences. Reminder completion and skip actions are logged as care log entries for trend tracking.

### Household Data

If you use the household sharing feature, the app processes CloudKit sharing records that identify household participants by their iCloud account identifiers.

### Aggregated Trend Data

The app computes aggregated health trends from your care data, including daily calorie totals, water consumption, weight changes, medication dosage totals, and activity counts. This data is derived from your existing care logs and is not collected separately.

## How We Store Your Data

### On-Device Storage

All data is stored locally on your device using Apple's Core Data framework with a SQLite database.

### App Group Container

To enable widget and extension access to your data, the app stores its Core Data database in a shared app group container (`group.rhealitycheck.Pawsitively-Healthy`). This allows the iOS widgets to read your data directly from the local database in a read-only capacity. The data never leaves your device or Apple's ecosystem through this mechanism.

### iCloud (CloudKit)

When you are signed into iCloud, your data is automatically synchronized to your private iCloud CloudKit database (`iCloud.com.pawsitively-healthy.app`). Apple manages the encryption and security of data stored in CloudKit. Your data is stored in your personal iCloud private database and is not accessible to us or any third party.

For more information about how Apple handles iCloud data, see [Apple's iCloud Security Overview](https://support.apple.com/en-us/102651).

## How We Use Your Information

Your data is used exclusively to:

- Display and manage your pet profiles and care records within the app
- Synchronize your data across your Apple devices via iCloud
- Deliver local notifications for reminders you have configured
- Enable household sharing with people you explicitly invite
- Display health trends, charts, and aggregated metrics within the app and on home screen widgets
- Provide quick-access summaries on home screen widgets and watch face complications
- Enable care logging and reminder management from the Apple Watch companion app
- Export your data when you use the data export feature

## iOS Widgets

Pawsitively Healthy includes home screen widgets (Reminders, Activity Timeline, Calendar, and Combined Trends) that display summaries of your pet data. These widgets:

- Read data directly from the shared app group container on your device
- May display pet names, care activity summaries, reminder details, medication names, and health metrics (calories, water intake, weight)
- Are visible on your home screen and may be visible on your lock screen depending on your device settings
- Update periodically (every 30–60 minutes) and do not transmit data to any external service

## Apple Watch App

The Pawsitively Healthy watchOS companion app allows you to:

- View and complete or skip reminders
- Log walks with distance and duration
- Log care activities (feeding, medication, grooming, and others)
- Snooze reminders

The Watch app accesses the same data as the main iOS app via the shared CloudKit container. No additional data is collected beyond what is described in this policy.

## Watch Face Complications

Pawsitively Healthy provides watch face complications that offer quick-launch shortcuts for logging walks and opening the app. These complications display static icons and labels only and do not show personal data on the watch face.

## Data Sharing

### Household Sharing

You may choose to share your pet data with other iCloud users through CloudKit sharing. Sharing requires an explicit invitation from you and can be revoked at any time.

### Third Parties

Pawsitively Healthy does **not**:

- Sell your data to third parties
- Share your data with advertisers
- Use third-party analytics or tracking services
- Send your data to external servers or APIs
- Include any advertising SDKs
- Use crash reporting or telemetry services

All data remains within Apple's ecosystem (your device and your private iCloud account).

## Permissions

Pawsitively Healthy may request the following device permissions:

|
 Permission 
|
 Purpose 
|
|
---
|
---
|
|
**
iCloud
**
|
 Sync and back up your data across devices 
|
|
**
Photo Library
**
|
 Select photos for pet profiles 
|
|
**
Notifications
**
|
 Deliver reminder alerts via local and remote notifications 
|

Pawsitively Healthy does **not** access your location, camera, microphone, contacts, or health data (Apple HealthKit).

## Data Retention

Your data persists on your device and in your iCloud account for as long as you use the app. If you sign out of a household, your data remains stored in iCloud. You can delete individual records within the app at any time, including care logs from the edit view. To remove all data, you can delete the app from your device and remove its data from iCloud via your device's iCloud storage settings.

## Data Export and Portability

Pawsitively Healthy provides a data export feature that allows you to export your pet data (care logs, breathing rates, reminders, and medications) as JSON files. This supports your right to data portability.

## Children's Privacy

Pawsitively Healthy does not knowingly collect personal information from children under 13. The app tracks pet data, not personal data about children. iCloud account access is governed by Apple's own age and parental consent requirements.

## Security

Your data is protected by:

- Apple's on-device data protection and encryption
- Apple CloudKit's encryption for data in transit and at rest
- iCloud authentication managed by Apple
- Read-only access for widget extensions to the shared data store

We do not operate our own servers or databases. We rely on Apple's infrastructure and security practices for all data storage and transmission.

## Changes to This Policy

We may update this Privacy Policy from time to time. The "Last Updated" date at the top of this page indicates when the policy was last revised. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy or your data, please contact us at:

**Email:** rhea@rhealitychek.com

## Your Rights

Depending on your jurisdiction, you may have the right to:

- Access the personal data we hold about you
- Request correction of inaccurate data
- Request deletion of your data
- Export your data (available via the in-app export feature)
- Withdraw consent for data processing

Since all data is stored in your own iCloud account and on your device, you have direct control over your data at all times.

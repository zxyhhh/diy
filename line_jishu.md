# Thenline Support

Thenline is a local-first private timeline journal for iPhone. This page provides troubleshooting steps and answers to common questions.

## Contact Support

**Email:** zxyhdream@gmail.com

When contacting support, include:

- Your Thenline app version.
- Your iPhone model and iOS version.
- A short description of what happened.
- The steps that reproduce the problem.
- A screenshot, if it does not reveal private information.

Do not send journal entries, exported backups, location details, health information, or other sensitive content unless you intentionally choose to share it for troubleshooting.

## System Requirements

- Thenline requires iOS 15 or later.
- Apple Health State of Mind integration requires iOS 17 or later.
- Some features require camera, photo-library, microphone, location, notification, Health, biometric-authentication, or iCloud permission.
- Premium features require an active Thenline Pro subscription or lifetime purchase recognized by the App Store.

## Where Is My Data Stored?

Journal entries are stored on your device by default. Thenline does not use a developer-operated server to store journal content.

If you enable Premium iCloud backup, Thenline stores a backup ZIP in the private iCloud container associated with your Apple ID. Files you export are saved or shared only to the destination you choose.

## How Do I Back Up My Entries?

Open **Thenline › Settings › Privacy & Data**.

- Choose **Export Entries › Full Backup (.zip)** to create a complete portable backup.
- Premium users can enable **Automatic Backup to iCloud**.
- Premium users can also choose **Sync › Back Up to iCloud** to create a backup manually.

Create a backup before deleting Thenline, resetting your device, changing Apple IDs, or moving to another device.

## How Do I Restore a Backup?

For an exported ZIP backup:

1. Open **Thenline › Settings › Privacy & Data**.
2. Choose **Import Entries**.
3. Select a valid Thenline ZIP backup.

For iCloud:

1. Sign in to the Apple ID that contains the backup.
2. Make sure iCloud is enabled for Thenline.
3. Open **Thenline › Settings › Privacy & Data › Sync**.
4. Choose **Restore from iCloud**.

Restoring merges the backup with local content. Entries with the same internal ID are replaced by the backup version.

## iCloud Backup Is Unavailable

Check the following:

- You are signed in to iCloud on the device.
- iCloud Drive is enabled.
- Thenline is allowed to use iCloud in system settings.
- Your internet connection is working.
- Your iCloud account has available storage.
- Thenline Pro is active.

After checking these items, reopen Thenline and try the backup again.

## Can Deleted Entries Be Recovered?

Deleted entries and their replies cannot be recovered directly in Thenline. They may be recoverable only if they exist in a previously created ZIP or iCloud backup. Restoring an older backup can also replace newer versions of entries with matching internal IDs.

## How Do I Export My Journal?

Open **Thenline › Settings › Privacy & Data › Export Entries** and choose:

- **Full Backup (.zip):** A restorable backup containing entries, structured data, profile information, and available media.
- **Markdown (.md):** A readable text document.
- **Word (.docx):** A document that can be opened in compatible word processors.

Markdown and Word exports contain readable entry content and attachment placeholders. Use the ZIP format when you need a complete restorable backup with media.

## Purchase or Premium Access Is Missing

1. Confirm that the device is signed in to the Apple ID used for the purchase.
2. Check your internet connection.
3. Open the Thenline Premium page and choose **Restore Purchases**.
4. Reopen Thenline after the restore completes.

If no purchase is found, check your Apple purchase history and active subscriptions. Apple handles billing, refunds, subscription changes, and payment disputes.

## How Do I Manage or Cancel a Subscription?

On iPhone, open:

**Settings › [your name] › Subscriptions › Thenline**

Canceling a subscription stops future renewal. Premium remains available until the end of the current paid period unless Apple states otherwise. A lifetime purchase does not renew.

## Camera, Photos, Microphone, or Location Does Not Work

Open **iPhone Settings › Privacy & Security**, select the relevant permission, and allow access for Thenline.

Location is requested only when you add a place to an entry. Microphone access is required for voice notes and video recording. Camera and photo-library access are required only for media features you choose to use.

## Apple Health Does Not Work

State of Mind requires iOS 17 or later.

Open **Settings › Privacy & Security › Health › Thenline** and allow the requested State of Mind access. You can also manage Thenline's access from the Apple Health app. Health permission must be granted separately on each device.

## Daily Reminders Do Not Appear

Open **iPhone Settings › Notifications › Thenline** and enable notifications. Then return to **Thenline › Settings › Daily Reminder**, enable the reminder, and confirm the selected time.

Daily reminders are scheduled locally. Focus modes, Scheduled Summary, Low Power Mode, and system notification settings may affect when they appear.

## App Lock Cannot Be Enabled

Set up a device passcode first. Face ID or Touch ID availability depends on your device and system settings.

Then open **Thenline › Settings › App Lock** and enable **Require unlock to open Thenline**. Thenline does not receive or store your biometric templates or device passcode.

## The Home Screen Widget Is Not Updating

1. Open Thenline so it can refresh widget data.
2. Confirm that Thenline Pro is active.
3. Remove and add the widget again.
4. Restart the iPhone if the widget remains unchanged.

Widget refresh timing is controlled by iOS and may not be immediate.

## Search Cannot Find an Entry

Search matches published entry text, replies, quotes, localized dates, and topics. Drafts are not included. Try a shorter term, a topic name, the calendar, or a content filter.

## Media Is Missing or Will Not Play

Make sure the media file still exists in Thenline's app storage and that the device has enough free space. If the media came from an imported backup, try importing the complete ZIP again. Markdown and Word exports do not contain the original media files.

## Before Reinstalling Thenline

Deleting the app removes local Thenline data from the device. Before reinstalling:

1. Create a Full Backup ZIP or confirm that a recent iCloud backup completed successfully.
2. Save the ZIP somewhere outside the Thenline app container.
3. Verify that you can access the file or iCloud account.

Do not assume that an iPhone device backup or iCloud synchronization contains a current Thenline backup unless Thenline shows a successful backup.

## Privacy

Thenline stores journal content locally by default and does not contain third-party advertising or cross-app advertising tracking. For details about permissions, Apple Health, iCloud, RevenueCat, retention, and deletion, read the [Thenline Privacy Policy](yinsi.md).

## Feedback and Feature Requests

Send feedback and feature requests to **zxyhdream@gmail.com**. Please describe the problem you want to solve and your current workflow. Do not include private journal content unless it is necessary and you intentionally choose to share it.

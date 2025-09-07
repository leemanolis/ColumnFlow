ColumnFlow – Privacy Policy

Effective date: September 7, 2025
Contact: lee.manolis@gmail.com

ColumnFlow is a personal finance app that helps you project monthly cash flow across iPhone, iPad, and Mac. We designed it to keep your data private: your budget lives on your devices and (optionally) in your iCloud account—not on our servers.

⸻

Summary (the short version)
    •    No ads. No tracking. No third-party analytics SDKs.
    •    We don’t run our own servers. Data sync uses Apple’s CloudKit in your iCloud private database.
    •    Optional Calendar access is only used to add/update events you request.
    •    Optional file access is only used when you import/export CSV files via the system file picker.
    •    You can delete all iCloud data from inside the app at any time.

⸻

What data the app handles

Budget data (you enter)
    •    What: months, starting/ending balances, line items (label, amount, date, projected flag), currency code.
    •    Where: stored locally on device and, if iCloud is enabled, in your iCloud private database (CloudKit).
    •    Why: to provide the app’s core functionality (budget projection).

Calendar data (optional)
    •    What: when you use “Add Items to Calendar,” the app creates/updates all-day events in a dedicated “ColumnFlow” calendar with the item’s title and an amount summary in the notes.
    •    Where: saved in your device’s Calendar via EventKit. A small local mapping file (UUID ↔︎ event ID) is stored in the app’s documents folder to keep events in sync.
    •    Why: so projected items can appear on your calendar.
    •    Control: turn off at any time; removing the “Projected” flag or running the update will remove linked events.

Files (optional)
    •    What: CSV import/export of months and items.
    •    Where: handled locally using the system file picker; exported files are saved to a location you choose.
    •    Why: to let you back up, move, or edit data outside the app.

CloudKit notifications
    •    What: the app registers for silent (content-available) remote notifications so CloudKit can nudge the app to pull changes.
    •    Where: delivered by Apple. No marketing notifications.
    •    Why: faster, near-real-time sync.
    •    Control: you can disable notifications in system settings; sync still works, just less instantly.

Diagnostics
    •    In-app log: a lightweight, on-device event list (e.g., “Pushed to CloudKit”).
    •    System crash reports (optional): If you’ve opted in to share diagnostics with developers via Apple, we may receive aggregated crash reports tied to Apple’s identifiers, not to your identity.

⸻

What we do not collect or do
    •    We do not track you across apps or websites.
    •    We do not sell, rent, or share your data with third parties.
    •    We do not use advertising SDKs or third-party analytics SDKs.
    •    We do not request location, contacts, microphone, photos, or Bluetooth.

⸻

Legal bases (GDPR/EEA)
    •    Performance of a contract / App functionality: processing your budget data to run the app.
    •    Consent: Calendar and Files access only after you grant permissions.
    •    Legitimate interests: receiving anonymized crash reports (if you opted in with Apple) to improve stability.

You may have rights to access, correct, export, or delete your data. Contact us at lee.manolis@gmail.com for help.

⸻

Security
    •    Apple’s CloudKit encrypts data in transit and at rest within your iCloud account.
    •    Local storage is protected by your device’s security (passcode, Face/Touch ID, and data protection).
    •    No internet transmission is perfectly secure; we rely on Apple’s infrastructure and best practices.

⸻

Data retention & your controls
    •    On device: kept until you delete the app or use the in-app controls.
    •    In iCloud: kept until you remove it.
    •    Your controls:
    •    In the app: Help → Maintenance → Delete all iCloud data to remove the CloudKit record.
    •    Delete the app to remove local data.
    •    Disable iCloud for the app in system settings if you prefer local-only.

⸻

Children’s privacy

ColumnFlow is not directed to children under 13, and we do not knowingly collect personal information from children.

⸻

International transfers

iCloud is operated by Apple and may store/process data in data centers outside your country. Apple’s safeguards and policies apply to CloudKit storage.

⸻

Changes to this policy

We may update this policy as the app evolves. We’ll change the “Effective date” above and, where appropriate, notify you in-app or on our site.

⸻

Contact

Questions or privacy requests?
lee.manolis@gmail.com

⸻

App Store Privacy Summary (helper)
    •    Data Collected: None (no analytics/tracking).
    •    Data Linked to You: None by the developer (budget data stays on device/iCloud).
    •    Optional Access: Calendars (user-initiated), Files (user-initiated).
    •    Tracking: No.

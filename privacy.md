---
layout: default
title: Privacy Policy - PocketLog
---

<div style="text-align: center; margin-bottom: 2rem;">
  <h1>Privacy Policy</h1>
  <p style="color: #586069;">Last Updated: December 7, 2025</p>
</div>

PocketLog ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our mobile application.

---

## Our Privacy Commitment

<div style="background: linear-gradient(135deg, #28a745 0%, #20c997 100%); color: white; border-radius: 12px; padding: 1.5rem; margin: 1.5rem 0;">
<p style="font-size: 1.1rem; margin: 0; text-align: center;">
<strong>PocketLog is designed with privacy at its core.</strong><br>
We do not collect, store, or share your personal data on our servers.<br>
Your information stays on your device and under your control.
</p>
</div>

---

## Information Storage

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin: 1.5rem 0;">

<div style="background: #f6f8fa; border-radius: 12px; padding: 1.5rem;">
<h3 style="margin-top: 0;">📱 Local Storage</h3>
<p>All data you enter into PocketLog—including contacts, logs, todos, and attachments—is stored locally on your device using SwiftData (Apple's modern persistence framework).</p>
<p style="margin-bottom: 0;">This data never leaves your device unless you explicitly choose to:</p>
<ul style="margin-bottom: 0;">
<li>Enable iCloud sync</li>
<li>Create and export a backup file</li>
<li>Share content using iOS sharing features</li>
</ul>
</div>

<div style="background: #f6f8fa; border-radius: 12px; padding: 1.5rem;">
<h3 style="margin-top: 0;">☁️ iCloud Sync (Optional)</h3>
<p>If you choose to enable iCloud sync:</p>
<ul style="margin-bottom: 0;">
<li>Your data is stored in your personal iCloud <strong>private database</strong> using Apple's CloudKit framework</li>
<li>Data is encrypted in transit and at rest by Apple</li>
<li>Sync occurs directly between your devices through Apple's CloudKit infrastructure</li>
<li>Apple's CloudKit architecture ensures that private database contents are accessible only to the account holder—we as developers cannot view, access, or retrieve your synced data</li>
</ul>
</div>

</div>

---

## Contact Import & Data Handling

<div style="background: #e3f2fd; border: 1px solid #2196f3; border-radius: 12px; padding: 1.5rem; margin: 1.5rem 0;">

<h3 style="margin-top: 0; color: #1565c0;">📇 When You Import Contacts</h3>

<p>PocketLog allows you to import contacts from your device's Contacts app. Here's exactly what happens:</p>

<ol>
<li><strong>Permission Request:</strong> The app requests access to your device contacts. You can choose to import all contacts or select specific ones.</li>
<li><strong>Local Storage:</strong> Imported contact information (name, phone, email, address, birthday) is copied into PocketLog's local database on your device.</li>
<li><strong>iCloud Sync (if enabled):</strong> If you have enabled iCloud Sync in PocketLog settings, imported contacts will be synced to your private iCloud account along with all other PocketLog data.</li>
<li><strong>No Third-Party Servers:</strong> Contact data is <strong>never</strong> sent to our servers or any third-party service. The only cloud destination is your own private iCloud, and only if you explicitly enable it.</li>
</ol>

<p style="margin-bottom: 0;"><strong>Important:</strong> The app clearly displays your current sync status (local-only or iCloud) when importing contacts, so you always know where your data will be stored.</p>

</div>

<div style="background: #fff3cd; border: 1px solid #ffc107; border-radius: 8px; padding: 1rem; margin: 1rem 0;">
<h4 style="margin-top: 0; color: #856404;">⚠️ Backup Files</h4>
<p style="margin-bottom: 0; color: #856404;">
When you create a backup using Backup & Restore, backups are exported as <strong>JSON files</strong> that are <strong>not encrypted</strong> by default. You are responsible for storing backup files securely. We recommend storing backups in a secure location or encrypted storage.
</p>
</div>

---

## Data You Provide

When you use PocketLog, you may choose to enter the following types of information, which is stored **only on your device** (and optionally in your private iCloud database):

| Data Type | Examples | Purpose |
|-----------|----------|---------|
| 👤 Contact Info | Names, phone numbers, emails, addresses | Store information about your contacts |
| 📝 User Content | Log entries, notes, photos, attachments | Record interactions and memories |
| 🔗 Identifiers | Contact IDs (internal use only) | Link logs and todos to contacts |
| 📍 Location | Places you add to logs | Remember where interactions occurred |
| 📅 Dates | Birthdays, anniversaries, custom dates | Track important dates and reminders |

<div style="background: #d4edda; border: 1px solid #28a745; border-radius: 8px; padding: 1rem; margin: 1rem 0;">
<p style="margin: 0; color: #155724;">
<strong>✓ Important:</strong> All of this data is stored locally on your device or in your private iCloud database. We do not have access to any of this information.
</p>
</div>

---

## Information We Do NOT Collect

<div style="background: #f6f8fa; border-radius: 8px; padding: 1.5rem; margin: 1rem 0;">

<p><strong>PocketLog does not collect:</strong></p>

<ul style="list-style: none; padding-left: 0; margin: 0;">
<li>❌ Personal identification information</li>
<li>❌ Usage analytics or behavioral data</li>
<li>❌ Location tracking data</li>
<li>❌ Device identifiers</li>
<li>❌ Advertising identifiers</li>
<li>❌ Any data for marketing purposes</li>
</ul>

</div>

---

## Third-Party Services

PocketLog does not integrate with any third-party analytics, advertising, or tracking services.

The only third-party service involved is **Apple's iCloud**, which is:
- ✓ Optional and user-controlled
- ✓ Governed by [Apple's privacy policy](https://www.apple.com/privacy/)
- ✓ Used solely for syncing your data across your own devices

---

## Data Security

<div style="background: #f6f8fa; border-radius: 12px; padding: 1.5rem; margin: 1rem 0;">

<p><strong>Your data security is important to us:</strong></p>

<ul style="list-style: none; padding-left: 0; margin: 0;">
<li style="margin-bottom: 0.75rem;"><strong>🔐 App Sandbox</strong><br><span style="color: #586069;">All data is stored within iOS's secure app sandbox</span></li>
<li style="margin-bottom: 0.75rem;"><strong>🔒 CloudKit Encryption</strong><br><span style="color: #586069;">iCloud data is encrypted using Apple's CloudKit security standards</span></li>
<li><strong>📱 Device Security</strong><br><span style="color: #586069;">Your device's built-in security (passcode/Face ID/Touch ID) protects all locally stored data</span></li>
</ul>

</div>

---

## Your Rights and Control

You have complete control over your data:

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; margin: 1rem 0;">

<div style="background: #e3f2fd; border-radius: 8px; padding: 1rem; text-align: center;">
<strong>👁️ Access</strong><br>
<small>View all your data within the app at any time</small>
</div>

<div style="background: #e8f5e9; border-radius: 8px; padding: 1rem; text-align: center;">
<strong>📤 Export</strong><br>
<small>Create a full backup in Settings > Backup & Restore</small>
</div>

<div style="background: #ffebee; border-radius: 8px; padding: 1rem; text-align: center;">
<strong>🗑️ Delete</strong><br>
<small>Delete any data at any time. Deleting the app removes all local data</small>
</div>

<div style="background: #fff3e0; border-radius: 8px; padding: 1rem; text-align: center;">
<strong>☁️ iCloud</strong><br>
<small>Enable or disable iCloud sync at any time in Settings</small>
</div>

</div>

---

## Children's Privacy

PocketLog does not knowingly collect information from children under 13. The app is intended for general audiences and does not contain content directed at children.

---

## International Users & GDPR

<div style="background: #f6f8fa; border-radius: 12px; padding: 1.5rem; margin: 1rem 0;">

<p>PocketLog is designed with privacy principles that align with international privacy regulations including GDPR:</p>

<ul style="list-style: none; padding-left: 0; margin: 0;">
<li style="margin-bottom: 0.75rem;"><strong>Data Minimization</strong><br><span style="color: #586069;">We collect no data; you control what you store locally</span></li>
<li style="margin-bottom: 0.75rem;"><strong>Right to Access</strong><br><span style="color: #586069;">All your data is visible within the app at any time</span></li>
<li style="margin-bottom: 0.75rem;"><strong>Right to Portability</strong><br><span style="color: #586069;">Export your data using the Backup feature</span></li>
<li style="margin-bottom: 0.75rem;"><strong>Right to Erasure</strong><br><span style="color: #586069;">Delete any data within the app, or delete the app to remove all local data</span></li>
<li><strong>No Cross-Border Transfers</strong><br><span style="color: #586069;">Your data stays on your device or in your iCloud account</span></li>
</ul>

</div>

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.

---

## Contact Us

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; border-radius: 12px; padding: 2rem; text-align: center; margin: 2rem 0;">

<h3 style="color: white; margin-top: 0;">Questions about Privacy?</h3>
<p>If you have questions about this Privacy Policy, please contact us:</p>
<p style="font-size: 1.2rem; margin: 1rem 0;">
<a href="mailto:pocketlog.app@gmail.com" style="color: white; text-decoration: underline;">pocketlog.app@gmail.com</a>
</p>

</div>

---

<div style="text-align: center; margin: 2rem 0;">
<a href="/" style="display: inline-block; background: #f6f8fa; color: #24292e; padding: 10px 20px; border-radius: 6px; text-decoration: none;">← Back to Home</a>
</div>

<p style="text-align: center; color: #586069; font-size: 0.85rem;">© 2025 PocketLog. All rights reserved.</p>

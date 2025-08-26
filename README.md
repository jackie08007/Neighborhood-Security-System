# Neighborhood-Security-System
Neighborhood Watch Security Patrol Monitoring System

I developed this application to help a neighborhood watch group monitor the patrols performed by their contracted security company. The system is built with both a web-based application and a mobile application. The mobile app is capable of working offline and synchronizes with the back-end whenever internet access becomes available.

Users and Roles
👨‍💻 Administrators

As an administrator, I (or another admin) can:

Approve or reject self-registered accounts.

Delete, block, suspend, or reinstate users.

Add, remove, or suspend houses that require monitoring.

Access developer-level configurations for system maintenance.

Administrator accounts are created by other administrators. Password resets are supported through the “forgot password” feature, and every login requires two-factor authentication (2FA) via an OTP sent to the registered email.

🚔 Security Officers

Security officers use only the mobile app. Each officer:

Self-registers in the app and awaits admin approval.

Uses a work-issued device with the app preinstalled.

Scans unique QR codes assigned to gates during patrols.

Each scan logs the officer’s name, date, time, and optional contextual notes (e.g., “gate open,” “dogs outside”).

Can view a full history of their patrols but cannot modify or delete entries.

👥 Neighborhood Watch Members

Members of the neighborhood watch group also use the mobile app.

They self-register and require admin approval.

Membership requires a monthly subscription fee (X Pula), payable online (mobile cards or other payment methods available in Botswana).

If a member fails to pay for two consecutive months, their account is automatically suspended and security officers are notified. Once payment is made, access is restored.

Members can unsubscribe at any time.

Features for Members:

Patrol Statistics: View how often officers patrol their area.

Community Interaction: Post and respond to comments visible to all members.

Emergency Alerts: Raise high-priority alerts that notify both officers and members instantly.

App Features
🔍 Patrol Monitoring

If an officer fails to patrol adequately, the system sends SMS and email notifications to all members.

Each incident report is logged for reference.

📷 QR Code Compliance

If an officer scans fewer than X% of their assigned households, the system:

Provisions a suspension.

Sends SMS/email alerts to admins and members.

Allows admins to revoke suspension if the issue is due to faulty QR codes.

Finalizes suspension if misconduct is confirmed.

Suspended officers must be replaced by the security company.

After 3 months, an admin may reinstate the officer manually.

Officers who are deleted are permanently barred from the system.

📊 Reporting

The system generates:

Weekly reports

Monthly reports

Yearly reports

🔐 Security & Non-Functional Requirements

Security: Strong emphasis on protecting user data and payment details.

Scalability: The system can handle increased loads without slowing down or crashing.

Disaster Recovery: Includes backup and recovery procedures to minimize downtime.

Performance: Optimized for high responsiveness across both web and mobile platforms.

✨ With this system, neighborhood watch members, administrators, and officers all have clearly defined roles and tools that keep patrols transparent, accountable, and secure.

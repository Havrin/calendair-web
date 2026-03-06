# Permission Explanation / General Information

**CalendAIr needs access to your Google, Outlook or Apple calendar so that the app can check when you are free or busy and generate smart meeting time suggestions.**

* For technical reasons, we require permission to read your calendar events. **However, we exclusively process and use your availability data (free/busy)** from this access to suggest suitable meeting times.  
* We **never read, store, or share** event titles, descriptions, attendees, notes, or locations.  
* Calendar content is **never visible to us or to other users**.  
* You can revoke access at any time in your device settings or by disconnecting your calendar in the profile area.

Please see further information in the Data Privacy section.

# Data Privacy 

When you grant permission, the app accesses your calendar through the respective service APIs:

* Apple EventKit (iOS)  
* Outlook (Microsoft Graph API)  
* Google Calendar API (Android & Google Accounts)

For technical reasons, the app loads event object metadata, which may include the following fields: ID, ICalUID, Title, Description, StartTime, EndTime, Location, Status, Transparency, and Attendees.

Crucially, we exclusively process and use only the free/busy information from this data to calculate suitable meeting times. We explicitly do not use the content of event titles, descriptions, attendees, or locations for our core functionality.

**Data We Store on Our Servers**

We do not store any sensitive calendar content. Temporary free/busy data may be processed in-memory for suggestion generation but is not persisted. The data we *do* store includes:

* User Profiles and Meeting Records  
* Calendar Metadata: The name and status (e.g., 'Primary' calendar) of your selected calendars.  
* Secure Access Tokens: Encrypted refresh tokens (for Google and Outlook) or equivalent access credentials (for Apple) are stored to maintain the connection to your calendars. These tokens can be revoked by you at any time in your respective Google or Outlook account settings, or by disconnecting your calendar in the app.

**What We Do *Not* Store or Share**

We explicitly do not store, share, or make visible to any user or employee:

* Event titles  
* Descriptions or notes  
* Attendee lists  
* Locations  
* Reminders or attachments  
* Any other event content

**Purpose of Processing**

We use your free/busy data solely to:

* Detect when you are available.  
* Generate meeting time suggestions for you and the people you invite.

  This is strictly limited to functionality within the app.

**Legal Basis**

The legal basis for processing your calendar availability is your explicit consent (Art. 6(1)(a) GDPR). You may withdraw your consent at any time by revoking calendar access in your device settings or by deleting your account.

**Third-Party Services Used**

Our application is built using secure infrastructure and services. We use the following major service providers for our core functionality and infrastructure:

* AWS (Amazon Web Services) – for cloud infrastructure.  
* Google – for Google Calendar API access and Google OAuth 2.0 authentication.  
* Apple – for Apple EventKit access and Apple authentication.  
* Microsoft Outlook – for Microsoft Graph API access.  
* Firebase Core / Analytics / Crashlytics – for app analytics and crash diagnostics (no calendar content is transmitted).

We may also use advertising services (like Google AdMob). All data collected for advertising is subject to your explicit consent, which is managed via our in-app consent tool. For detailed terms of service and privacy policies of the other listed providers, please refer to their respective websites.

**International Transfers**

Some services (Google, AWS) may process data outside the EU. In such cases, we rely on:

* Standard Contractual Clauses (SCCs)  
* Adequacy decisions  
* Other legally recognized safeguards

**Your Rights**

You have the right to:

* Access your personal data  
* Request deletion of your data  
* Withdraw consent  
* Object to processing  
* File a complaint with your local data protection authority

To exercise these rights, contact us at: \[insert email\]
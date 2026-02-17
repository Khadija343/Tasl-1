SRS Review Activity
Requirement 1

❌ Original:

The system should be user-friendly.

Problems:

❌ Not Clear

❌ Not Testable

❌ Not Measurable

❌ Not Specific

✅ Improved Requirement:

The system shall allow a new user to complete registration within 3 minutes without external assistance.

Requirement 2

❌ Original:

The system shall store student records safely.

Problems:

❌ Ambiguous ("safely")

❌ Not measurable

❌ Not specific

✅ Improved Requirement:

The system shall store all student records in an encrypted database using AES-256 encryption.

Requirement 3

❌ Original:

The system should load quickly.

Problems:

❌ Not measurable

❌ Not testable

❌ Ambiguous

✅ Improved Requirement:

The system shall load the dashboard page within 2 seconds under normal network conditions (minimum 10 Mbps).

Requirement 4

❌ Original:

The system shall allow users to register, login, and manage their profile.

Problems:

❌ Not Atomic (multiple requirements combined)

✅ Improved Requirements (Split into atomic ones):

The system shall allow users to register using email and password.

The system shall allow registered users to log in using valid credentials.

The system shall allow users to update their profile information including name and password.

Requirement 5

❌ Original:

The system shall send notifications.

Problems:

❌ Not clear

❌ Not specific

❌ Not measurable

✅ Improved Requirement:

The system shall send email notifications to users within 5 seconds after successful registration.
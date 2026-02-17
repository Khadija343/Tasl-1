# Software Requirements Specification (SRS)
## Task 6: SRS Review Activity

------------------------------------------------------------

## Requirement 1

### ❌ Original Requirement:
The system should be user-friendly.

### Problems Identified:
- Not Clear
- Not Measurable
- Not Testable
- Ambiguous
- Not Specific

### ✅ Improved Requirement:
The system shall allow a new user to complete the registration process within 3 minutes without external assistance.

------------------------------------------------------------

## Requirement 2

### ❌ Original Requirement:
The system shall store student records safely.

### Problems Identified:
- Ambiguous ("safely")
- Not Measurable
- Not Testable
- Not Specific
- Incomplete

### ✅ Improved Requirement:
The system shall store all student records in a database encrypted using AES-256 encryption and restrict access to authorized users only.

------------------------------------------------------------

## Requirement 3

### ❌ Original Requirement:
The system should load quickly.

### Problems Identified:
- Not Measurable
- Not Testable
- Ambiguous
- Not Specific

### ✅ Improved Requirement:
The system shall load the main dashboard page within 2 seconds under normal operating conditions with a minimum internet speed of 10 Mbps.

------------------------------------------------------------

## Requirement 4

### ❌ Original Requirement:
The system shall allow users to register, login, and manage their profile.

### Problems Identified:
- Not Atomic (contains multiple requirements)
- Not Specific
- Not Completely Testable as a single requirement

### ✅ Improved Requirements (Atomic Form):

1. The system shall allow users to register using a valid email address and password.
2. The system shall allow registered users to log in using their valid credentials.
3. The system shall allow users to update their profile information including name and password.

------------------------------------------------------------

## Requirement 5

### ❌ Original Requirement:
The system shall send notifications.

### Problems Identified:
- Not Clear
- Not Specific
- Not Measurable
- Not Testable
- Incomplete

### ✅ Improved Requirement:
The system shall send an email notification to users within 5 seconds after successful account registration.

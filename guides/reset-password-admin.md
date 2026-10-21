# Reset a User's Password (Administrators)

Use this procedure when a user is locked out and cannot use self-service reset.

## Before you begin
Verify the user's identity using your organization's policy (for example, a manager confirmation or a verified callback number). Never skip this step — password resets are a common social-engineering target.

## Steps
1. Go to **Admin → Users**.
2. Search for the user and open their profile.
3. Select **Reset Password → Send Reset Link**.
4. Tell the user the link expires in 1 hour.

## You're done when
The user confirms they received the link and signed in.

## Audit note
Every administrator-initiated reset is written to the audit log with your name, the user's name, and the timestamp. This is expected and cannot be disabled.

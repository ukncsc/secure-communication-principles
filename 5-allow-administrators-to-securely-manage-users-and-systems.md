# 5. Allow administrators to securely manage users and systems

## Can administrators suitably manage their users' accounts?

If users are allowed to manage their own accounts, then an organisation will **not** have full control over how those accounts are accessed. Many organisations will need to manage how this is done, which could be as simple as a 'joiners and leavers' policy to ensure that users' accounts are revoked when they leave the organisation. Another example may be managing user access to different groups within the service, or granting permission to certain users so that they can set up groups.

The communications service should allow administrators to securely manage their organisation's users. Administrators should be able to manage user accounts throughout their lifecycle, giving them the required control to authorise or deny certain actions.

## Is administration and management protected and restricted?

Access to the administration interface of the communications service could allow new accounts to be created and user access permissions to be changed. If someone gained control of this, they could create unauthorised accounts on the system, which could then be used nefariously. They could also disable legitimate accounts, or elevate the permission levels of users to subvert security controls.

Administration and management of the system should be restricted to authorised individuals, whose privileged access should be authenticated, using two-factor authentication if supported, and logged. In addition, the enrolment of users onto the service should require identification of the user to ensure they are authorised, before provisioning security credentials for the user account. Administration should also be practical for the scale of the organisation, to ensure that administrators do not take shortcuts in performing authorisation checks before carrying out administrator functions.

# Joint Web+Core - Authentication, Authorization, and Security
This division is in charge of authentication (a user is who they say they are), authorization (the authenticated user is allowed to access X part of MARS), and the overall security of MARS (including the encryption/hashing of sensitive data) lie with this division.

## Typical users/customers of the division:
All other Engineering divisions, feature stewards, end users.

## Typical responsibilities: Delight your users/customers. Your most important role is to serve them.
**How this is done is up to you. We suggest that you:**
- [Develop and publicize well-described procedures](./procedures.md) for others to effectively interact with the division.
- Review all pull requests before they go to production for possible security vulnerabilities. Can override decisions of other divisions if there is a security concern.
- Implement the requirements developed by the folks in other divisions as they relate to the security of MARS.
- Implement and maintain MARS-wide user authentication and authorization technology, in a way which is minimally intrusive for other engineering divisions and delightful to end-users.
- Create technical requirement documents for other divisions, as applicable, and light a fire under their asses to ensure it gets developed.
- Conduct periodic "war games" and penetration testing.
- In partnership with the Infrastructure, CI/CD, and Quality division, update SSL certificates on a periodic basis and confirm that software dependencies are up to date.

## Nice-to-have skills/background for Martians in this division:
Python3, React, Next.js, SAML, OAuth2, JWTs, Hashing, Encryption, SSL Certificates

## Minimum time commitment:
- Ad hoc meetings with users/customers and other Martians.
- 1 weekly dev meeting on Thursdays at 2pm PT / 5pm ET.
- 1 monthly all-hands meeting the first Thursday of the month at 1pm PT / 4pm ET.

## Minimum deliverable commitment:
- 1 commit to GitHub per month.

Note: Failure to meet the minimum time and deliverable commitments will result in dismissal from the division.
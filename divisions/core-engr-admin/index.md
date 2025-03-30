Core (Backend) Engineering - Administration

## Description:
This division is in charge of the Command Line Interface (CLI) and other code which provides solutions for the "meta"/admin tasks of running the MARS core itself. A quintessential example is that of an end-user contacting MARS with a request to reset their password. This division writes the CLI code which allows a MARS administrator to do that password reset. It also includes all logs, "manual overrides" unavailable to outside users, and the source of all "technical / back of house" system emails (which are processed by code written by the notification division). Final technical decisions about the way MARS (when it's running in production) is accessed by Martians (except for select security areas) lie with this division.

## Typical users/customers of the division:
All of the other Core Engineering divisions, feature stewards.

## Typical responsibilities: Delight your users/customers. Your most important role is to serve them.
**How this is done is up to you. We suggest that you:**
- [Develop and publicize well-described procedures](./procedures.md) for others to effectively interact with the division.
- Implement the requirements developed by the folks in the other engineering divisions (typically through providing a CLI tool they can SSH to), in consultation with the feature stewards.
- Create technical requirement documents for other engineering divisions as needed. 
Light a fire under their asses to ensure it gets developed to the satisfaction of your customers.

## Nice-to-have skills/background for Martians in this division:
Python3, Bash scripting

## Minimum time commitment:
- Ad hoc meetings with users/customers and other Martians.
- 1 weekly dev meeting on Thursdays at 2pm PT / 5pm ET.
- 1 monthly all-hands meeting the first Thursday of the month at 1pm PT / 4pm ET.

## Minimum deliverable commitment:
- 1 commit to GitHub per month.

Note: Failure to meet the minimum time and deliverable commitments will result in dismissal from the division.
# Joint Web+Core - Infrastructure, CI/CD, and Quality Assurance
The division, our "dev ops" division, is in charge of the servers where MARS is hosted, the domain names, DNS, internal networks, deployments, ensuring that uptime is 99%+, the mechanics of how the code gets on to the server in a timely manner (e.g., containerization), and they are also the first responders when users report catastrophic issues with MARS. All Martians must receive final sign-off from this division on their work before the code goes live / is accepted into the "Main" branch. The launch files (e.g., main.py, server.ts) are owned by this division. Final decisions about code documentation, and whether the code is allowed to run in production, lie with this division.

## Typical users/customers of the division:
All other Engineering divisions, feature stewards.

## Typical responsibilities: Delight your users/customers. Your most important role is to serve them.
**How this is done is up to you. We suggest that you:**
- [Develop and publicize well-described procedures](./procedures.md) for others to effectively interact with the division.
- Procure and maintain the servers, networks, domain names, etc., for MARS.
- Implement technologies for seamless deployment of code to the servers.
- Implement the requirements developed by the folks in other divisions; namely, get their code accepted and "live" ASAP.
- Determine, publicize, and enforce GitHub contribution norms for all code contributed to MARS.
- Determine, publicize, and enforce code documentation requirements for all code contributed to MARS.
- Determine, publicize, and enforce code style/formatting requirements for all code contributed to MARS.
- Review all pull requests before they go to production for documentation and style. Resolve documentation and style issues quickly.
- In partnership with the Security division, update SSL certificates on a periodic basis and confirm that software dependencies are up to date.
- Do first response triage to catastrophic events (e.g., the site is no longer live) and get MARS back up and running as quickly as possible.

## Nice-to-have skills/background for Martians in this division:
DNS, Nameservers, Docker, Linux, Doxygen, Pip, PyPi, PDM, PEP8, NPM, Prettier

## Minimum time commitment:
- Ad hoc meetings with users/customers and other Martians.
- 1 weekly dev meeting on Thursdays at 2pm PT / 5pm ET.
- 1 monthly all-hands meeting the first Thursday of the month at 1pm PT / 4pm ET.

## Minimum deliverable commitment:
- 2 pull requests reviewed and accepted per month.

Note: Failure to meet the minimum time and deliverable commitments will result in dismissal from the division.
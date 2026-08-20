Access Management & Incident Resolution in Enterprise Environments 
A look at how identity and access management operates day-to-day in a multinational enterprise environment, based on hands-on experience supporting Active Directory and privileged server access.

Context Over the past 4-5 years, in NOC/infrastructure support roles (Infosys Consulting, SCC Service Romania), I've handled account and access management as a core, recurring responsibility — not a one-off task, but daily operational work supporting hundreds of end users across enterprise environments.

Active Directory: Day-to-Day Operations

Account lifecycle: creating, suspending, and deleting user accounts
Group management: adding and removing users from security and distribution groups
Privilege management: granting and revoking access rights based on change requests
Account recovery: password resets and unlocking locked-out accounts
Incident handling: troubleshooting individual login/access issues, as well as contributing to larger-scale incidents (e.g. organization-wide login failures), typically tracing back to Group Policy-level issues — identifying and escalating these through the ticketing system

Privileged Access Management: CyberArk My CyberArk experience centered on server-level privileged access rather than identity administration itself:

Logging into servers through CyberArk's privileged session management to perform health checks
Restarting servers or stopped services as part of incident resolution
Working within the audit/monitoring structure that CyberArk enforces around privileged access

Incident Spotlight: Compromised Executive Account Under Live Social Engineering

A high-priority directive came down from senior leadership at a client company: a specific executive's device had been physically stolen, their account was considered compromised, and the account was to be treated as a live security incident — no password resets, no access changes, no account actions of any kind, regardless of who requested it or how convincingly. If the account holder or anyone claiming to be them made contact, the caller had to be placed on hold immediately and client leadership notified right away.

A few days into the freeze, a call came in from someone identifying themselves as the executive, requesting a password reset. The request looked routine on the surface — the caller had the executive's name and enough context to sound legitimate — which is exactly what made it a live test of the directive rather than a hypothetical one.

Action taken:

No account action was taken — no reset, no exceptions, regardless of how convincing the caller was.
The caller was placed on hold immediately, per the instruction.
Client leadership was notified right away that someone claiming to be the account holder had made contact.

Why it mattered: a password reset request from someone who "sounds right" is exactly the vector an attacker would use during an active compromise — the freeze existed specifically to remove that judgment call from a support-desk interaction under time pressure. Following the directive literally, and escalating the contact attempt immediately rather than after the fact, is what turned a single blocked request into usable, real-time information for whoever was managing the wider security incident.

What This Demonstrates

Comfort operating within strict access-control and audit frameworks
Ability to triage between "fixable at my level" and "needs escalation" — recognizing when an issue sits above my access scope (e.g. GPO changes) and routing it correctly
Reliability handling high-volume, recurring identity operations without errors that could compromise security
Discipline to follow a security directive exactly under social pressure, rather than defaulting to "be helpful" when a request looks routine

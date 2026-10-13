# Security

We aim for i41 to be secure, but there is a known backlog, and nothing has been independently
reviewed or verified yet. i41 is a proof of concept, written with AI agents and tested at home. What we aim for, the known limits and what was fixed:
[security](https://github.com/i41-eu/i41eu-arch/blob/main/docs/security.md) in i41eu-arch.

## Report a vulnerability privately

Please do not open a public issue. In the repository concerned, open the **Security** tab and
choose **Report a vulnerability** (GitHub's private vulnerability reporting, on for the public
i41-eu repositories). Report it in
[i41eu-arch](https://github.com/i41-eu/i41eu-arch/security/advisories/new) instead if the
repository has no such button, for m.i41.eu (its code is not public), or if you are not sure
which repository.

It helps to say what you found, where (repository and file, release, or web address), and how
to see it. Please test with your own robot, account and home manager: do not access other
people's robots or data, and do not slow the sites down. We fix the latest release only (early
stage: no backward compatibility).

## What happens then

- We answer in the private report and keep you posted there.
- A bug that can be exploited stays in a private advisory until a fix is released. Then the
  advisory is published and the fix is listed in
  [security](https://github.com/i41-eu/i41eu-arch/blob/main/docs/security.md), with credit to
  you if you want it.
- i41 is one person's project (mj41) with AI agents: there is no bug bounty, and an answer may
  take a few days.

Problems in M5Stack's own code (the parts of the robot's firmware we did not write): report them
to us privately as well. M5Stack's [StackChan](https://github.com/m5stack/StackChan) repository
takes no private reports, so we pass them on.

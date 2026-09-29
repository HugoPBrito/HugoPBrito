### Hello there :))

I'm Hugo, a cloud security and software engineer focused on open-source tools and multi-cloud security.

- 🔒 Contributed to [Prowler](https://github.com/prowler-cloud/prowler) through GitHub, Cloudflare, and Microsoft 365 provider integrations.
- 🛠 Built [py-pwsh-session](https://github.com/prowler-cloud/py-pwsh-session), connecting Python with persistent PowerShell sessions.
- 🌐 Explore more on my [website](https://hugopbrito.cloud/).

<details>
<summary>More about my work</summary>

#### GitHub activity

<a href="https://github.com/HugoPBrito"><img src="https://streak-stats.demolab.com/?user=HugoPBrito&theme=dark&hide_border=true" alt="GitHub total contributions, current streak, and longest streak for HugoPBrito" /></a>

#### Overview

At Prowler, I worked across the path from cloud-security research to product delivery. That meant studying provider behavior, building checks and integrations, improving APIs and UI, testing edge cases, and supporting releases. The common thread was turning cloud configuration questions into useful findings while making the software dependable for people who run it. My work crossed AWS, Azure, GCP, and Microsoft 365/Entra.

#### What I do

- **Security research and accuracy:** I mapped cloud configuration checks to frameworks such as CIS, ISO/IEC 27001, and HIPAA, and investigated false positives when provider behavior did not match an assumption. I [separated GCP KMS rotation checks by compliance requirement](https://github.com/prowler-cloud/prowler/pull/11516), distinguishing a CIS 90-day limit from frameworks that only require rotation to be enabled.
- **Product engineering:** I worked on Python integrations, APIs, UI, automated tests, and CI with GitHub Actions, including documentation and release support rather than treating checks as isolated scripts.
- **Open source:** I worked in public repositories, collaborated on pull requests, and helped contributors move from an issue to a reviewed change.

#### Selected work

- **GitHub provider:** I contributed to the [GitHub provider integration](https://github.com/prowler-cloud/prowler/pull/5787) and [CIS benchmark documentation and compliance](https://github.com/prowler-cloud/prowler/pull/6116). The provider followed Prowler's existing structure, while CIS coverage made its findings useful for benchmark-based security reviews.
- **Cloudflare provider:** My contributions spanned the [provider foundation and zone security checks](https://github.com/prowler-cloud/prowler/pull/9423), [API support for registering and authenticating Cloudflare accounts](https://github.com/prowler-cloud/prowler/pull/9907), and [UI support for connecting and selecting the provider](https://github.com/prowler-cloud/prowler/pull/9910). This connected security checks to account setup and provider selection across the product.
- **Microsoft 365 integration:** I worked on [bringing PowerShell into the provider](https://github.com/prowler-cloud/prowler/pull/7331) for configurations Microsoft Graph alone did not expose, alongside Graph-based checks. Later, [certificate authentication in the API](https://github.com/prowler-cloud/prowler/pull/8538) supported non-interactive access as Microsoft enforced MFA, while preserving existing authentication options.
- **Oracle Cloud (OCI):** I contributed to [regionless SDK setup](https://github.com/prowler-cloud/prowler/pull/11740) and [API credential handling](https://github.com/prowler-cloud/prowler/pull/11741), allowing credentials without a scan-region filter while the provider discovers subscribed regions. These were SDK and API parts of a broader team change, not a new provider.
- **Okta controls:** My contributions added [network-zone coverage](https://github.com/prowler-cloud/prowler/pull/11463), [API-token checks](https://github.com/prowler-cloud/prowler/pull/11464), and [authenticator checks](https://github.com/prowler-cloud/prowler/pull/11465) for STIG-aligned assessments. They cover anonymized proxies, token restrictions, password policies, and authenticator configuration within an existing provider.

#### Open-source tooling

[py-pwsh-session](https://github.com/prowler-cloud/py-pwsh-session) grew out of the team’s Microsoft 365 integration. I worked on persistent sessions, command execution, timeouts, and JSON results so Python applications could reuse an authenticated PowerShell process instead of starting one for each query.

#### What I work with

- **Cloud security:** AWS, Azure, GCP, Microsoft 365/Entra, CSPM, and compliance mapping for CIS, ISO/IEC 27001, and HIPAA.
- **Engineering:** Python, APIs, UI, testing, PowerShell integrations, and CI/CD with GitHub Actions.

#### Writing and community

I wrote [Running PowerShell from Python](https://prowler.com/blog/py-pwsh-session-running-powershell-from-python-yes-we-actually-did-that) about the tradeoffs behind our Microsoft 365 integration, and [Certificate-based Microsoft 365 authentication](https://prowler.com/blog/adapting-to-microsofts-mfa-enforcement-prowlers-new-certificate-based-m365-authentication) about adapting to MFA enforcement. I also delivered workshops at [Hackén 2025](https://hacken.es/edicion/2025) and [Hackén 2026](https://hacken.es/edicion/2026), where I appear on the public speaker lists.

#### Background

I studied computer engineering at the University of Granada and participated in Hackiit, a cybersecurity community centered on hands-on learning, talks, and workshops. My public [education page](https://hugopbrito.cloud/education/) has more background.

</details>

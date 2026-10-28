# Module 9: Security and supply chain basics

**Level:** Practitioner  
**Time:** about 4 hours  
**Needs:** a laptop or a phone with a browser; some exercises need an internet connection once.

## Learning objectives
By the end you will be able to:
- Explain what a software supply chain is
- Make an SBOM (software bill of materials)
- Check a project with OpenSSF Scorecard and OSV

## Lesson outline
1. Supply chain: your software is built from others' software
2. SBOM: a list of every component; SPDX and CycloneDX formats
3. Scanning for known vulnerabilities
4. Scorecard and the OpenSSF Best Practices badge
5. SLSA in plain terms: proving how software was built
6. Basic secure habits: update, review, protect branches, two-factor login

## Hands-on exercise: Make an SBOM and check it
1. Install Syft from https://github.com/anchore/syft (the README lists install commands for each system).
2. Pick a project folder or container image you use.
3. Run `syft dir:. -o spdx-json > sbom.json` in that folder.
4. Open sbom.json in a text editor. Count components.
5. Pick three components. Search each on https://osv.dev/ for known vulnerabilities.
6. Look up one of your main dependencies on https://deps.dev/ and note its Scorecard score.
7. Write down: one thing to update now, one thing to watch.

## Quiz
1. What is an SBOM?
2. Name two SBOM formats.
3. Where can you look up known vulnerabilities for free?

<details><summary>Answers</summary>

1. A list of all software components in a product.
2. SPDX and CycloneDX.
3. OSV (osv.dev).

</details>

## Free resources
| Resource | License |
|---|---|
| [OpenSSF](https://openssf.org/) | See site |
| [OpenSSF Best Practices guides](https://best.openssf.org/) | CC BY 4.0 |
| [OpenSSF Best Practices Badge](https://www.bestpractices.dev/) | MIT (software) |
| [OpenSSF Scorecard (code)](https://github.com/ossf/scorecard) | Apache-2.0 |
| [SPDX](https://spdx.dev/) | See site |
| [CycloneDX](https://cyclonedx.org/) | Apache-2.0 (spec) |
| [SLSA](https://slsa.dev/) | CC BY 4.0 |
| [Syft](https://github.com/anchore/syft) | Apache-2.0 |
| [Linux Foundation LFD121: Developing Secure Software (free)](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/) | Free course; LF terms |


## More free resources from across tech

Vendor-neutral where possible. Vendor material is labeled. Links checked October 2026.

| Resource | Provider | Cost | License or terms |
|---|---|---|---|
| [OpenSSF free courses (Secure Software Development)](https://openssf.org/training/courses/) | OpenSSF | Free | Course terms; CC BY (some) |
| [OWASP Top Ten](https://owasp.org/www-project-top-ten/) | OWASP | Free | CC BY-SA 4.0 |
| [SLSA supply-chain framework](https://slsa.dev/) | SLSA | Free | CC BY 4.0 |
| [Sigstore docs](https://docs.sigstore.dev/) | Sigstore | Free | Apache 2.0 |
| [CNCF Cloud Native Security Whitepaper](https://github.com/cncf/tag-security) | CNCF | Free | Apache 2.0 |
| [Kubernetes security docs](https://kubernetes.io/docs/concepts/security/) | Kubernetes | Free | CC BY 4.0 |

Links checked October 2026. If one breaks, please open an issue.

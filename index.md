---
title: Home
layout: home
---

[Browse our documentation][just the docs] to learn more about how to use this theme.

To get started with creating a site, just click "[use this template]"!

## TPSCRM Terminology
---
#### Created by David Parker, last modified by Theodore Gauthier on Apr 06, 2021
To help you better understand some of the common terms used, we’ve collected some quick terminology and corresponding definitions for you based on the most commonly used terms in the Ecosystem.  


---

| TERM        | DEFINATION          |
|:-------------|:------------------|
| Distribute           | this is defined as any product that is for external consumption (not limited to Customers, VARS, Distributors, Field Services, Demo Depot, Capital Leasing, Partners, Labs) |
| Organization | Any development team within Cisco that distributes software externally  | 
|TPSCRM	|Third Party Software Compliance and Risk Management|
|TPS	| Third Party Software (Open Source or Commercial) |
|TPSD	 |Third Party Software Digitization (this refers to the entire platform and services, or ecosystem) |
|TPSCRM |	Third Party Software Compliance and Risk Management (this refers to the entire platform and services, or ecosystem) |
|TPSD (aka TPSCRM) |	Third Party Software Digitization - Service name changed to TPSCRM, which is synonymous |
|Security Insights (SI) |	This tool provides visibility into CSDL compliance information for projects, solutions, and hosted services in development at Cisco |
|Corona (TPS discovery, including binary scanning)	| Internal software decomposition and analytics solution harness that integrates with other Cisco development tools and processes to enable the delivery of trustworthy software to our customers by providing enhanced visibility into our products to better understand exposures to security vulnerabilities and asset accounting prior to shipping |
| Black Duck |	Risk management tool designed to help you manage the logistics of using open source software in your organization |
| TPS Compliance |	Third Party Software (Compliance) Product, Release and Image details related to the compliance requirement actions that must be fulfilled to ensure that a given Product goes from RED to GREEN state |
| CIAM	| The Cisco Internal Alert Manager (CIAM) is a Cisco-internal tool that alerts engineers about vulnerabilities in their third-party software components|
|PSIRT |	Cisco Product Security Incident Response Team (PSIRT) is a dedicated, global team that manages the receipt, investigation, and public reporting of security vulnerability information that is related to Cisco products and networks |
| BE	| (Cisco) Business Entity |
|BU	 | (Cisco) Business Unit |
|UI	 | User Interface |
| Product	| The main service or offering your team is creating | 
| Release	| Each version of your Product |
| Image	| A group of Components derived from scanning a binary file that you plan to deliver to a customer mostly automatically discovered via scanning, but can contain manually added Components |
| CG	| Component Group – Identical to Image except that binary files are not included |
| Component	| The smallest legal object that has license and vulnerability implications |
| RM | 	Reusable Module – an Image or Component group shared with other teams to share responsibility for license and vulnerability alerts |
| BYOS / TPS Manifest BOM	| Bring Your Own Scan. Officially referred to as TPS Manifest BOM. Many cloud and source-only projects don't have a binary file that Corona can scan, so you can provide a list of discovered components using source scanning tools and provide those to Corona |
| Software BOM	| BOM or Bill of Materials in manufacturing are the components that make up the product. Cisco based software projects also are required to have a Software Bill of Materials. Corona helps you determine what's in your project | 
|Triage |	Making manual updates to your Software BOM to make sure it is as accurate as possible |
|Markup	| Information manually added to your Software BOM. This could be version overrides, manually added Components or more |
| Version-less	| Components where the scanning tools did not find a version for the Component | 
| VO |	Version Override – Scanning mis-identified a version and you have manually set it |
| BDBA | Black Duck Binary Analysis (formerly Protocode) – The primary analysis tool to determine Components in a binary file |
| BDSA |	Black Duck Source Analysis – A tool for scanning source code to determine Components |
| CSDL |	Cisco Secure Development Lifecycle |
| CIAM	| Cisco Internal Alert Manager – The tool that looks for vulnerabilities in your registered Components | 
| CSERV	| Cisco Security Evaluation, Requirements and Validation |
| CSM |	Common Security Module | 
| Curioscan | 	Scanning tool focused on run time defense posturing |
| CVE	| Common Vulnerabilities and Exposures – knows vulnerabilities within a Component |
| DARE |	Data Aggregation and Reporting Engine – Part of the Cisco's Security Insights program that makes sure your project adheres to minimum security practices |
| Gambit |	Original code name for Corona. A specific satellite in the Corona program: <https://en.wikipedia.org/wiki/KH-7_Gambit> |



---

---

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[just the docs]: https://just-the-docs.github.io/just-the-docs/
[github pages]: https://docs.github.com/en/pages
[readme]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[jekyll]: https://jekyllrb.com
[github pages / actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate


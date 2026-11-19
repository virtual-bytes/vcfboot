# Security

## Reporting a vulnerability

Please report vulnerabilities privately: on this repository, **Security › Report a vulnerability**. Do not open a public issue for one.

Include the vcfboot version (the version the appliance's UI shows), what an attacker needs (network position, a login, a role), and the steps to reproduce. We aim to answer within a week.

## Supported versions

Fixes go into the latest release only.

## What vcfboot holds

vcfboot holds the keys to a site: iDRAC logins, ESX root, and every VCF password. They are kept in memory only, never written to disk, and sent only to endpoints whose certificates it has pinned. Run the appliance on a management network that only administrators can reach.

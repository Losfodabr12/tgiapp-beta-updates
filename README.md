# TGIAPP beta updates

Public metadata endpoint for beta builds of TGIAPP.

This repository must contain only release metadata. Do not add source code,
credentials, OAuth secrets, private tokens, or project files here.

Manifest URL:

`https://raw.githubusercontent.com/Losfodabr12/tgiapp-beta-updates/main/latest.json`

The beta build already uses this manifest as a mandatory version gate. An
older build or a build that cannot reach the manifest stays blocked before the
Hub and import tools are mounted. The beta artifact hashes are recorded in the
manifest and in the GitHub Release.

The `signature` field is intentionally reserved for the production release.
Before production, the app must verify that signature with an embedded public
key instead of relying only on HTTPS, GitHub branch protection, and the beta
asset hashes.

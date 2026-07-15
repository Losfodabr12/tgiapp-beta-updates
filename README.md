# TGIAPP beta updates

Public metadata endpoint for beta builds of TGIAPP.

This repository must contain only release metadata. Do not add source code,
credentials, OAuth secrets, private tokens, or project files here.

Manifest URL:

`https://raw.githubusercontent.com/Losfodabr12/tgiapp-beta-updates/main/latest.json`

The application should treat this manifest as informational until the
signature field is populated and verified with an embedded public key. The
production update gate must fail closed only after that verification flow and
the installer download flow are ready.


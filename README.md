# Transplant POC public JWKS

This repository contains public verification keys for the Transplant POC's
non-production Epic FHIR integration. It contains no private keys, access
tokens, credentials, patient data, or production key material.

Public JWKS endpoint:

`https://raw.githubusercontent.com/Transplant-Central/transport-poc-jwks/main/epic-sandbox-jwks.json`

The corresponding private key is stored outside source control. Non-production
and production integrations use separate key pairs and separate URLs.

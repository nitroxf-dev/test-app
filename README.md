# test-app

Testbed for gated pushes through [pushgate.dev](https://pushgate.dev).

- `origin` fetches from GitHub and pushes through the gate
- every push carries a gitsign certificate and a cilock test attestation
- `.nitrogate.json` / the NitroGate workflow are a separate quality-gate experiment

Every push to this repository records which coding agent produced it
(cilock's alps-evidence attestor) — observed context, honestly labelled,
never claimed as identity.

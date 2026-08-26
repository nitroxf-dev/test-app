# test-app

Testbed for gated pushes through [pushgate.dev](https://pushgate.dev).

- `origin` fetches from GitHub and pushes through the gate
- every push carries a gitsign certificate and a cilock test attestation
- `.nitrogate.json` / the NitroGate workflow are a separate quality-gate experiment
something

Branch-path test: committed on feat/my-change, pushed as feat/my-change.

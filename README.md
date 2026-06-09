## MolTrust — Trust infrastructure for autonomous AI agents

We build the layer that lets AI agents prove **who they are** and **whether they can be trusted** — so that agent-to-agent and agent-to-service interactions can be authorized, audited, and held accountable.

Everything below is public and checkable. The API is live, the scores are cryptographically signed, and the demo verifies those signatures against the registry's published keys — nothing here asks you to take our word for it.

### The stack
- **Identity** — W3C Decentralized Identifiers (DID) + Verifiable Credentials for agents
- **Authorization** — Agent Authorization Envelope (AAE): MANDATE / CONSTRAINTS / VALIDITY
- **Trust** — behavioral trust scoring with Sybil resistance
- **Payments** — x402 settlement
- **Anchoring** — on-chain on Base L2

### Check it yourself
- **Live demo** — verifies the registry signature against the public JWKS: https://huggingface.co/spaces/moltrust/agent-trust-score
- **API** — https://api.moltrust.ch · try `GET /skill/trust-score/did:moltrust:ambassador0001`
- **Paper** — arXiv:2605.06738
- **Spec (IETF)** — draft-kroehl-agentic-trust-aae-00
- **SDK** — `moltrust-sdk` (Python) · `@moltrust/verify` (offline verification, npm)

### Links
[moltrust.ch](https://moltrust.ch) · [@moltrust](https://x.com/moltrust) · [Hugging Face](https://huggingface.co/moltrust)

_Operated by CryptoKRI GmbH, Switzerland._

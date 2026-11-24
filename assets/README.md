# Terminal capture provenance

These images come from the author's actual Contabo Linux rehearsal on 24 November 2026 (UTC). They are frames rendered from `script(1)` output recordings, not screenshots of someone else's installation and not a claim of an active Testnet validator.

Only host addresses and private identifiers are masked. Terminal output is otherwise retained. Original private recordings contain the unredacted evidence and original output timings; they are deliberately excluded from this repository.

| Capture | What it records |
| --- | --- |
| `01-host.png` | Actual host capacity and installed Docker/Compose versions |
| `02-checksums.png` | Verification of the five pinned setup files and raw chain specification |
| `03-network.png` | P2P on the host interface; RPC, metrics and readiness on loopback |
| `03-startup.png` | Initial non-authority startup and the expected initial readiness failure |
| `04-snapshot.png` | Official archive snapshot verification and bootstrap |
| `04-catchup.png` | Actual block and finality observations while catching up after the snapshot |
| `05-restart-proof.png` | Finalized agreement, advancing finality and restart recovery |
| `06-backup.png` | Verification of a private identity backup without displaying its contents |

The portrait is the creator's supplied original artwork. It is displayed as a small circular channel badge with `@khenzarweb3`; no generated replacement is used.

Do not infer successful Testnet admission, validator activation, rewards, or production hardware eligibility from these captures.

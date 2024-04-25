## Collaborator call note
Call date & time: Apr 25, 2024, 11:00-11:45 UTC

Attendees: Kunho Kim, guiltygyoza, Jihoon Song, Mark Khomutskii, Giwook Han, Jay Oak, Gregory Edison

### Summary
#### Research update

Mugen is:
- Looking into TLC for compaction, specifically [this paper](https://www.epfl.ch/labs/dedis/wp-content/uploads/2020/01/report-2019-1-Manuel_Vidigueira.pdf) and [this paper](https://arxiv.org/pdf/1907.07010.pdf).
- Listing considerations for live object sdk's API.

Thomas (gg) is:
- Communicating with [James Addison](https://twitter.com/JungleSilicon) about CRDTs and [Braid Protocol](https://braid.org/).
- Looking into [Mysticeti](https://arxiv.org/pdf/2310.14821.pdf).
- Looking into [Fireproof](https://fireproof.storage/).

Action items:
- Write about the current idea of a protocol stack (not architecture stack).
- Coordinate with the engineering side on hash graph layer protocols in May.

#### Engineering update
[Engineering Weekly](./Engineering_Weekly_2024-04-25.pdf)

### What we’ve done
- Use Protocol Buffers for peer-to-peer communication.
- Migrate RPC server.

### What we're working on
- Migrate P2P server.
- Forward messages from RPC server to Execution module.
- Support `create_live_object` operation.
- Support `execute_live_object` operation.
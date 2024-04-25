## Collaborator call note
Call date & time: Apr 18, 2024, 11:00-11:45 UTC

Attendees: Kunho Kim, guiltygyoza, Jihoon Song, Mark Khomutskii, Giwook Han, Jay Oak, Gregory Edison

### Summary
#### Research update
1. Mugen is (1) looking into TLC for compaction, specifically [this paper](https://www.epfl.ch/labs/dedis/wp-content/uploads/2020/01/report-2019-1-Manuel_Vidigueira.pdf) and [this paper](https://arxiv.org/pdf/1907.07010.pdf) (2) listing considerations for live object sdk's API.

2. Thomas (gg) is (1) communicating with [James Addison](https://twitter.com/JungleSilicon) about CRDTs and [Braid Protocol](https://braid.org/) (2) looking into [Mysticeti](https://arxiv.org/pdf/2310.14821.pdf) (3) looking into [Fireproof](https://fireproof.storage/).

3. Action items: (1) write about the current idea of a protocol stack (not architecture stack). (2) coordinate with the engineering side on hash graph layer protocols in May.

#### Engineering update
### What we’ve done
- Add logger.
- Research on Rust vs Go. ([slides](./Engineering_2024-04-18.pdf) and [doc](./Engineering_Rust_vs_Go.pdf))

### What we're working on
- Migrate from Go to Rust.
- Integrate `Wasmer` in Rust.
- Use Protocol Buffers for peer-to-peer communication.
- Set up our own bootstrap node.

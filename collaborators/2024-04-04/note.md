## Collaborator call note
Call date & time: Apr 04, 2024, 11:00-11:45 UTC

Attendees: Kunho Kim, guiltygyoza, Jihoon Song, Mark Khomutskii, Giwook Han, Mugen, Jay Oak.

### Summary
#### Research update
- CRDT experiments
  - implemented & tested infinite-phase set in go
  - working on 1-D multiplayer space
- Consensus & compaction protocol
  - preparing to prototype algorithms in go.
- For details, check out the [slides](./research-slides.pdf)
- Research topics and deliverable descriptions for protocol research phase 1 are listed [here](https://hackmd.io/@YKfDHwJERJOpgEiKJZ0UkQ/HJZlCXpkA). Contribution welcome!

#### Engineering update
##### What we're working on
- Adding RPC server running over HTTP.
- Making gram robust and adding more features like RPC router.
- Integrating `Wasmer`.

##### What we'll work on
- Open endpoints for incoming messages of creating and executing Live Object.
- Use Protocol Buffers for peer-to-peer communication.
- Integrating Wasmer.
- Set up our own bootstrap node.
- Refactor `gram` to propagate error appropriately.
- Refactor HTTP router to handle different requests.

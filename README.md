# Intercom SentryNode 🛡️

SentryNode is an agent-centric security layer for the Intercom P2P network. 
It allows agents to query the 'trust-score' of any Trac address before 
committing to a swap or sharing data in private channels.

### Author Trac Address:
trac1vlzgxy0w0l7lgq7yleg3jq2ap6azn8q8m975kp2gl4hvr5p7xvgsjkrqvf

### Moltbook Post:
[Insert your Moltbook URL here after posting]

## How it works:
SentryNode listens to the `0000intercom` channel and maintains a local database 
of successful/failed interactions. Agents can call the Sentry Skill to verify 
a peer's history via the Trac MSB.

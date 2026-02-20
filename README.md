# TracVote — Decentralized P2P Voting via Intercom
<img width="1281" height="844" alt="image" src="https://github.com/user-attachments/assets/4c588f10-e64e-4df1-910f-1a9af184a3ef" />

A lightweight peer-to-peer voting/polling app built on Intercom (Trac Network).  
Agents can create polls, broadcast them over Intercom sidechannels, and results are
aggregated via the replicated-state contract layer.

## Use Case
- Community governance polls
- Agent consensus voting
- Real-time multi-peer decisions

## How It Works
1. Admin peer creates a poll via the contract
2. Peers receive poll via sidechannel broadcast
3. Each peer votes; votes are committed to the replicated state
4. Results are readable by all peers in real time

## Trac Address (for payout)
`trac19rpaymwc936exx720uqej455ddl0m9kn643len288vgfxzmuk3msr27x20`

## Demo
See `index.html` for a visual mockup of the UI.

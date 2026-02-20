# SKILL: TracVote Agent Instructions

## What this app does
TracVote lets agents coordinate decisions via P2P polls on Intercom.

## Agent Usage
1. To CREATE a poll: send contract action `create_poll` with fields: `question`, `options[]`, `duration_seconds`
2. To VOTE: send contract action `cast_vote` with fields: `poll_id`, `option_index`
3. To READ results: query state key `poll:{poll_id}:results`

## Setup
- Follow upstream Intercom SKILL.md for Pear runtime setup
- Admin peer must be running before peers can join
- Run: `pear run --dev .`

## Notes
- One vote per peer per poll (enforced by contract)
- Results are live and replicated to all peers

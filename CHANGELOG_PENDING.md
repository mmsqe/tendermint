# Unreleased Changes

## v0.34.25

### BREAKING CHANGES

- CLI/RPC/Config
  - [config] \#9491 Add new event subscription options and defaults. (@creachadair)
  - [config] \#9259 Rename the fastsync section and the fast_sync key blocksync and block_sync respectively
  - [rpc] \#7982 Add new Events interface and deprecate Subscribe. (@creachadair)

- Apps

- P2P Protocol

- Go API

- Blockchain Protocol

### FEATURES

### IMPROVEMENTS

- [crypto] \#9250 Update to use btcec v2 and the latest btcutil. (@wcsiu)
- [consensus] \#9760 Save peer LastCommit correctly to achieve 50% reduction in gossiped precommits. (@williambanfield)
- [metrics] \#9733 Add metrics for timing the consensus steps and for the progress of block gossip. (@williambanfield)

### BUG FIXES


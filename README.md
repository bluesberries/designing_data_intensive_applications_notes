# Notes on Designing Data-Intensive Applications

## Transactions

**A**tomicity

**C**onsistency
* Not a database property

**I**solation
* Weak Isolation
  * Read Committed
  * Snapshot Isolation
* Serializable Isolation
  * Actual Serial Execution
  * Two-Phase Locking (2PL)
  * Serializable Snapshot Isolation
 
**D**urability


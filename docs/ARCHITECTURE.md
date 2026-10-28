# Traditional Chinese Hundred-Ke Clock — architecture

Executable clock formatting and tick semantics are provider-owned. All shared C helpers, time coordinate mathematics and public resource ABIs come from the real Common 1.19.80 git submodule (commit dc4aac326964ca4400b6e21851d16eea674040c8), linked as its canonical static archive. Prior 1.19.78 copies are retained only as provenance, not compiled dependencies. The native installer and source archive include an immutable source snapshot for offline builds; qualification includes original provider and accuracy fixtures.

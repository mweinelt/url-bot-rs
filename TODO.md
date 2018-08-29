# Panics on:

 - extended network dropouts
 - poorly formatted toml configuration

# Other panics

 - thread 'main' panicked at 'called `Result::unwrap()` on an `Err` value: Error(Io(Error { repr: Os { code: 101, message: "Network is unreachable" } })

# Extra features

 - more efficient use of curl (stop fetching page once title has been obtained)
 - Better handling of IRC connection errors (don't panic)
 - Set config file path on command line option / have default search paths, local last
 - Update to updated rust IRC API

# Tests

 - Previous postings
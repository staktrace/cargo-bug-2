STR:
cd test-repo2/subproj3
cargo update

expected: the workspace in test-repo/Cargo.toml generates a lockfile
actual: error

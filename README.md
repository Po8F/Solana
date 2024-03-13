## Solana
# The process and precautions for writing Solana contracts in Rust and deploying them on-chain for testing.
# Solana contracts need a entrypoint to start the program that's --> entrypoint!(function_name); .
# The cargo.toml need to set the [lib], including the filename -->//name = "/Project_name/" and crate-type -->//crate-type = ["cdylib"].
# Also at lest need to add the solana-program, under the [dependencies] in cargo.toml.

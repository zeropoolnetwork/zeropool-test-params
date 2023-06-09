# ZeroPool Test Parameters

This repository contains pre-generated trusted setup parameters for various ZeroPool circuits.

Do not use these parameters in production. They are provided for testing purposes only.

To generate the parameters manually, run the following libzeropool CLI (https://github.com/zeropoolnetwork/libzeropool) commands:
```bash
cargo run --release -- setup -c transfer -p transfer_params.bin -v transfer_verification_key.json
cargo run --release -- setup -c tree_update -p tree_params.bin -v tree_verification_key.json
```


# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below.

| file | SHA-256 |
|---|---|
| `equal-radicals-consecutive-products-v1.pdf` | `fa1a7800e024dd6dc636a9080e30650fd00a65d2c5d875e829ac644bb45ccc6c` |
| `equal-radicals-consecutive-products-v1.tar.gz` | `19ed9d7f968f0cf3cf09dc4ce0fe5e1b93a31e8d35dde6e2990d44c876f47ac2` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots

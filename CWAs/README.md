# Index of CosmWasm Advisories

## 2024

| Severity[^1] | Scope[^2] | ID                                                                 | Aliases                                    |
| ------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------ |
| Medium       | Contracts | [CWA-2024-002: Arithmetic overflows in cosmwasm-std][CWA-2024-002] | [RUSTSEC-2024-0338]                        |
| Low          | Contracts | [CWA-2024-001: Stack overflow in serde-json-wasm][CWA-2024-001]    | [RUSTSEC-2024-0012], [GHSA-rr69-rxr6-8qwf] |

[CWA-2024-002]: ./CWA-2024-002.md
[CWA-2024-001]: ./CWA-2024-001.md
[RUSTSEC-2024-0338]: https://rustsec.org/advisories/RUSTSEC-2024-0338.html
[RUSTSEC-2024-0012]: https://rustsec.org/advisories/RUSTSEC-2024-0012.html
[GHSA-rr69-rxr6-8qwf]: https://github.com/advisories/GHSA-rr69-rxr6-8qwf

## 2023

| Severity[^1] | Scope[^2] | ID                                                                          |
| ------------ | --------- | --------------------------------------------------------------------------- |
| High         | VM        | [CWA-2023-004][CWA-2023-004]                                                |
| Medium       | x/wasm    | [CWA-2023-003: Inefficient ListChannels query implementation][CWA-2023-003] |
|              | VM        | [CWA-2023-002: Stack overflow crash (Codename Cherry)][CWA-2023-002]        |
|              | VM        | [CWA-2023-001: Potential overflow in cache statistics][CWA-2023-001]        |

[CWA-2023-004]: ./CWA-2023-004.md
[CWA-2023-003]: ./CWA-2023-003.md
[CWA-2023-002]: ./CWA-2023-002.md
[CWA-2023-001]: ./CWA-2023-001.md

## 2022

| Severity[^1] | Scope[^2] | ID                                                                                     |
| ------------ | --------- | -------------------------------------------------------------------------------------- |
|              | x/wasm    | [CWA-2022-005: Denial of service through predictable contract addresses][CWA-2022-005] |
|              | x/wasm    | [CWA-2022-004: Unlimited query stack][CWA-2022-004]                                    |
|              | x/wasm    | [CWA-2022-003: Nondeterministic Stargate queries][CWA-2022-003]                        |
|              | VM        | [CWA-2022-002: Non-normalized bech32 casing in Addr type][CWA-2022-002]                |
|              | x/wasm    | [CWA-2022-001: Non-deterministic queries][CWA-2022-001]                                |

[CWA-2022-005]: ./CWA-2022-005.md
[CWA-2022-004]: ./CWA-2022-004.md
[CWA-2022-003]: ./CWA-2022-003.md
[CWA-2022-002]: ./CWA-2022-002.md
[CWA-2022-001]: ./CWA-2022-001.md

## 2021

| Severity[^1] | Scope[^2] | ID                                                                                          |
| ------------ | --------- | ------------------------------------------------------------------------------------------- |
|              | VM        | [CWA-2021-003: Nondeterministic stacktrace in VmError][CWA-2021-003]                        |
|              |           | CWA-2021-002: reserved                                                                      |
|              | VM        | [CWA-2021-001: Logic error in none handling in copyAndDestroyUnmanagedVector][CWA-2021-001] |

[CWA-2021-003]: ./CWA-2021-003.md
[CWA-2021-002]: ./CWA-2021-002.md
[CWA-2021-001]: ./CWA-2021-001.md

[^1]: following Amulet's Severity Classification Framework: https://github.com/interchainio/security/blob/e0227a1fb4059144aab4f6003eeee7f09912db3a/resources/CLASSIFICATION_MATRIX.md
[^2]: Contracts: everything compiled into Wasm (comswasm-std, other contract libraries); VM: everything executing contracts (cosmwasm-vm, wasmvm); x/wasm: integration of the VM into the chain (wasmd)

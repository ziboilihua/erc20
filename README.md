### [Tutorials Link](https://docs.substrate.io/tutorials/v3/ink-workshop/pt1/)

#### Clone Contract Node Project

```
gh repo clone paritytech/substrate-contracts-node
git checkout 35eeb847a8e02738dd8333ef7779429371ae50d8
```

#### Build Node
```
cargo build
```

#### Start Node
```
./target/release/substrate-contracts-node --dev --tmp
```

#### [Connect Local Node User Polkadot Apps](https://polkadot.js.org/apps/?rpc=ws%3A%2F%2F127.0.0.1%3A9944#/contracts)

<br/>

#### Testing Contract

```
cargo +nightly test
```

#### Building Contract

```
cargo +nightly contract build
```

#### Upload & Deploy Code


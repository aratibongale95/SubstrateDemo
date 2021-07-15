# Substrate Node Template
In this repository, Here we build 3 pallets

## Rust Setup
First, complete the basic [Rust setup instructions](https://www.rust-lang.org/tools/install).

### Run
Use Rust's native cargo command to build and launch the template node:

cargo run --release -- --dev --tmp
### Build
The cargo run command will perform an initial build. Use the following command to build the node without launching it:

cargo build --release


### Run
The provided cargo run command will launch a temporary node and its state will be discarded after you terminate the process. After the project has been built, there are other ways to launch the node.

This command will start the single-node development chain with persistent state:

./target/release/node-template --dev

## Connect with Polkadot-JS Apps Front-end
Once the node template is running locally, you can connect it with Polkadot-JS Apps front-end to interact with your chain. [Click here](https://polkadot.js.org/apps/#/explorer?rpc=ws://127.0.0.1:9944) connecting the Apps to your local node template.

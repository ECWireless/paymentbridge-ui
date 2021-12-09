# PaymentBridge

PaymentBridge is a UI wrapper combining both the xDAI bridge and OmniBridge extension. Using URL route parameters, a payer can send any ERC20/ERC677/ERC827 token to any receiving address on xDAI (including bridging DAI to the xDAI native token).

See the OmniBridge docs here: https://docs.tokenbridge.net/eth-xdai-amb-bridge/multi-token-extension

## Available Scripts

In the project directory, you can run:

### React App

#### `yarn dapp:start`

Runs the React app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will automatically reload if you make changes to the code.<br>
You will see the build errors and lint warnings in the console.

#### `yarn dapp:test`

Runs the React test watcher in an interactive mode.<br>
By default, runs tests related to files changed since the last commit.

#### `yarn dapp:build`

Builds the React app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

### Subgraph

#### `yarn subgraph:auth`

```sh
GRAPH_ACCESS_TOKEN=your-access-token-here yarn subgraph:auth
```

#### `yarn subgraph:prepare-<network>`

Generates subgraph.yaml for particular network.
Supported networks are kovan, sokol, xdai and mainnet.

#### `yarn subgraph:codegen`

Generates AssemblyScript types for smart contract ABIs and the subgraph schema.

#### `yarn subgraph:build`

Compiles the subgraph to WebAssembly.

#### `yarn subgraph:deploy-<network>`

Deploys the subgraph for particular network to the official Graph Node.<br/>

-

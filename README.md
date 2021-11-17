# PetShop with Solidity
A petshop was built by solidity and javascript.

## Contents

* [Development environment](##development-environment)
* [App Structure](##app-structure)
* [Install, Configure & Run](##install-configure--run)

## Development environment

* node (>= v12.21.0)
* lite-server (^2.3.0)

## App Structure

> _Note: .

```bash
├── LICENSE
├── README.md
├── box-img-lg.png
├── box-img-sm.png
├── bs-config.json
├── contracts
│   ├── Adoption.sol
│   └── Migrations.sol
├── migrations
│   ├── 1_initial_migration.js
│   └── 2_deploy_contracts.js
├── package-lock.json
├── package.json
├── src
│   ├── css
│   │   ├── bootstrap.min.css
│   │   └── bootstrap.min.css.map
│   ├── fonts
│   │   ├── glyphicons-halflings-regular.eot
│   │   ├── glyphicons-halflings-regular.svg
│   │   ├── glyphicons-halflings-regular.ttf
│   │   ├── glyphicons-halflings-regular.woff
│   │   └── glyphicons-halflings-regular.woff2
│   ├── images
│   │   ├── boxer.jpeg
│   │   ├── french-bulldog.jpeg
│   │   ├── golden-retriever.jpeg
│   │   └── scottish-terrier.jpeg
│   ├── index.html
│   ├── js
│   │   ├── app.js
│   │   ├── bootstrap.min.js
│   │   ├── truffle-contract.js
│   │   └── web3.min.js
│   └── pets.json
├── test
│   ├── TestAdoption.sol
│   └── testAdoption.test.js
└── truffle-config.js
```

## Install, Configure & Run

Below mentioned are the steps to install, configure & run.

```bash
# Clone the repo.
git clone https://github.com/
Go to main project directory
Rename .env.example to .env file and config server POST and NODE_ENV with values you want. 
```

```bash
# using truffle to compile and migrate the smartcontract to blockchain
truffle compile
truffle migrate


# Note: It is preassumed here that you have mongoose running in background & you have created the database.

# Install NPM dependencies.
# Note: You can review the list of dependencies from the below link.
npm install;

# Run unit test
npm run test

# Run the app
npm run dev;
```

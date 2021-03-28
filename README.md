# HackAtom

![logo](./resources/logo.png)

`Starway Monster is a project that we created at the HackAtom hackathon.`
* [starway.monster](https://starway.monster) - a site that clearly shows how you can work with ibc.
* [github.com/starway-monster](https://github.com/starway-monster) - github project repository, which contains all the developments of this project.

## Content
* [Content](#Content)
* [Architecture](#Architecture)
* [Installation and Configuration](#Installation-and-Configuration)
* [Repositories](#Repositories)

## Architecture
### Solution architecture

### Database schema
![db_schema](./resources/db_schema.png)

## Installation and Configuration
`All components of our solution use Docker. By following the instructions in each individual repository, you can
quickly and easily deploy the work bench. We use our services in kubernetes, but you can do it directly without any problems.`

## Repositories

* [starway-monster/HackAtom](https://github.com/starway-monster/HackAtom) - starway monster project root documentation repository
* [starway-monster/front](https://github.com/starway-monster/front) - source code of a site written in angular. Displays route lookup data and allows users to perform interblockchain transactions
* [starway-monster/database](https://github.com/starway-monster/database) - source code of scripts for the database, code for configuring its deployment, migrations and graphql (hasura) api.
* [starway-monster/server](https://github.com/starway-monster/server) - source code of a site written in angular
* [starway-monster/deploy](https://github.com/starway-monster/deploy) - CI/CD setup code via argocd
* [starway-monster/cosmos-sdk](https://github.com/starway-monster/cosmos-sdk) - fork cosmos/cosmos-sdk that fixes FungibleTokenPacketData decoding error
* [starway-monster/cosmos-watcher](https://github.com/starway-monster/cosmos-watcher) - this is a fork of mapofzones/cosmos-watcher that has been modified for use in the starway monster. Allows you to connect to the blockchain fullnode and collect blockchain blocks
* [starway-monster/txs-processor](https://github.com/starway-monster/txs-processor) - this is a fork of mapofzones/txs-processor that has been modified for use in the starway monster. Allows you to process data received from watchers


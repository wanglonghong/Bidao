# Bidao


- About Bidao
Bidao is building a decentralized finance (DeFi) and trustless stablecoin system to create a more open, borderless, transparent world through financial services.
A decentralized stablecoin system creates the opportunity for an open financial system, where anyone willing to provide collateral can generate our stablecoin.

- Ecosystem
Bidao’s mission for an open financial world is supported by a decentralized governance system that allows holders of our token to take decisions and vote for proposals.
An open ecosystem where people can freely use, transact and create applications using the Bidao stablecoin will be the new standard for decentralized finance.

- Features

 o Secure
  Programmable digital money that anyone can safely store, transfer and interact with.
 o Stable
  100% collateralized by cryptocurrency and price stable through blockchain technology.
 o Instant
  Permissionless, open for anyone to use, send, and open to be used in DeFi applications. Anytime, anywhere.

- Bidao-Ethereum Bridge

Peggy is the starting point for cross chain value transfers from the Ethereum blockchain to Bid blockchain 
as part of the Ethereum Cosmos Bridge project. 
The system accepts incoming transfers of Ethereum tokens on an Ethereum smart contract, 
locking them while the transaction is validated 
and equitable funds issued to the intended recipient on the Bidao bridge chain. 
The system supports value transfers from Bidao blockchain to the Ethereum blockchain as well through a reverse process.

 o How to transfer Ethereum to Bidao asset
  With a local Ethereum blockchain running, you can participate in Ethereum -> Bidao asset transfers by starting the Relayer service and acting as a validator. 
  Validators witness the locking of Ethereum/ERC20 assets and sign a data package containing information about the lock, 
  which is then relayed to the Bid chain and witnessed by the EthBridge module. 
  Once a quorum of validators have confirmed that the transaction's information is valid, 
  the funds are released by the Oracle module and transferred to the intended recipient's address. 
  In this way, Ethereum assets can be transferred to Bidao blockchain. 

 o How to transfer Bidao to Ethereum asset
  Bid -> Ethereum asset transfers are facilitated by a reverse process 
  where validators witness transactions on tendermint and sign a data package containing the information. 
  Bid assets can be locked, resulting in the release of funds held on Ethereum, or burned, 
  resulting in the minting of new ERC20 tokens on Ethereum which represent the burned assets. 
  The data package containing the validator's signature is then relayed to the contracts deployed on the Ethereum blockchain. 
  Once enough other validators have confirmed that the transaction's information is valid, 
  the funds are released/minted to the intended recipient's Ethereum address. 
  In this way, assets on Bidao blockchain can be transferred to Ethereum

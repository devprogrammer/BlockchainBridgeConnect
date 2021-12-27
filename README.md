<div style="text-align:center">

<p>

# Unity-Solana Wallet
The First Open-Source Unity-Solana Wallet with NFT support

The Unity-Solana Wallet is an essential bridge connecting game developers and the Solana blockchain. With Solana’s quick and low-cost transactions, games can start using blockchain technology like never before - in real-time. Thousands of developers will bring millions of players into the Solana ecosystem. This will, in turn, make the Solana projects benefit from an increased number of participants, and cross-protocol interoperability in games will take us beyond the current understanding of DeFi.  
  
Unity-Solana Wallet uses Solnet's implementation .NET SDK, but we had to modify the library to make it Unity compatible with .NET Standard 2.0 and .NET 4.x.
Solnet is Solana's .NET SDK to integrate with the .NET ecosystem.  [Solnet](https://blockmountain.io/Solnet/).

</p>

</div>


## Features
- Create/Backup wallet with mnemonic phrase
- Account handling
- Transaction building
- SOL balance 
- SPL-token balances
- SPL-token transfers
- Basic UI examples

## Dependencies
- Newtonsoft.Json
- Chaos.NaCl.Standard
- Portable.BouncyCastle
- Zxing

## Roadmap
- Multiple wallet accounts
- Camera support with QR code scanning for token transfers
- Improved UI for in-game easy integration
- Metaplex NFT / NFT-PRO support with GameObjects 
- Token swaps
- NFT swaps
- One-click in-game currency creator
- Themed UI support
- Metaplex auctions for in-game store items

## Installation

1. Clone this repository outside of the main Unity project
2. Change Api Compatibility Level in Player Settings to .NET 4.x
3. Go to Package Manager in your project
4. Click on the plus in the top left corner and select "Add package from disk"
5. Select package.json file from a cloned dir
6. Once the package is installed, in the Package Manager inspector you will have Samples. Click on Import
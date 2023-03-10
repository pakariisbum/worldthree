<p align="center">
  <a href="https://github.com/king-technologies/Project-Initiator" title="Project Initiator">
    <img src="./src/assets/img/logo2.svg" width="40px" alt="Project Initiator"/>
  </a>
</p>
<h1 align="center">π World3 π π</h1>

<p align="center"> 
<a href="https://github.com/pakariisbum/worldthree/blob/master/LICENSE" title="License">
<img src="https://img.shields.io/github/license/pakariisbum/world3" alt="world3"/>
</a>
<a href="https://github.com/pakariisbum/worldthree/fork" title="Forks">
<img src="https://img.shields.io/github/forks/pakariisbum/world3" alt="world3 Forks"/>
</a>
<a href="https://github.com/pakariisbum/worldthree" title="Stars">
<img src="https://img.shields.io/github/stars/pakariisbum/world3" alt="world3 Stars"/>
</a>
<a href="https://img.shields.io/github/stars/pakariisbum/world3/issues" title="Issues">
<img src="  https://img.shields.io/github/issues/pakariisbum/world3" alt="world3 Issues"/>
</a>

</a>
</p>

<p align="center" title="Project Initiator"><img src="./src/assets/img/world3.jpg" alt="Project Initiator"/></p>

<h2 align="center">π Links π</h2>
<p align="center">
    <a href="https://www.youtube.com/watch?v=P0ydk-wvisM" title="">π₯οΈ Video</a>
    .
    <a href="https://worldthree.netlify.app/" title="">π Website</a>
    Β·
    <a href="https://github.com/pakariisbum/worldthree" title="">π Repo</a>
    Β·
    <a href="https://github.com/pakariisbum/worldthree" title="πReport Bug/πRequest Feature">π Got Issue</a>
</p>

## πͺ Motivation

When I was a kid, I used to wonder how long the earth has been around, how creatures underwater survive, why animals go extinct, and what causes rain to fall. When I started high school, I realized that most of the answers I was looking for were right in front of me. Our actions have a significant impact on our world. How can we address these concerns? Individuals must dedicate themselves as explorers to assist in the management of these environmental and social issues.

## π How it works

World 3 is a web 3.0 platform that will bring together explorers to solve social and environmental problems of the SDG goals. Our mission is to use blockchain to achieve real world impact, especially in areas where there is no other solution. We believe that the technology exists today, and more importantly, we have built World3 to be easily adopted by anyone that needs a tool for managing social issues.

Follow the steps below to get started with web3.

- **Click on the profile icon at the top right corner of the homepage**

- **Setup a your profile**

- **Setup a project.**

- **Get Sponsorship from user all over the world**

## π¦ Prerequisite

- [Nodejs](https://nodejs.org/en// "Node") Installed

- [Git](https://git-scm.com/ "Git OFficial") Installed

- [npm](https://www.npmjs.com/ "npm ") Installed

- [Hardhat](https://hardhat.org/ "Hardhat ") Installed

## π οΈ Installation Steps

1. Clone the repository

```Bash
git clone https://github.com/pakariisbum/worldthree
```

2. Change the working directory

```Bash
cd world3
```

3. Start the local Hardhat node

```Bash
npx hardhat node
```

4. With the network running, deploy the contracts to the local network in a separate terminal window

```Bash
npx hardhat run scripts/deploy.js --network localhost
```

5. Start the app

```Bash
npm run start
```

**π You are Ready to Go!**

## βοΈ Configuration

The chain ID should be 80001. If you have a localhost rpc set up, you may need to overwrite it.

<p align="center" title="Project Initiator"><img src="./src/assets/img/rpc.jpg" alt="Project Initiator"/></p>

To deploy to Polygon test or main networks, update the configurations located in hardhat.config.js to use a private key and, optionally, deploy to a private RPC like Infura.

```Bash
require('@nomiclabs/hardhat-waffle');
const privateKey = 'xx';
const projectId = 'xx';
module.exports = {
  defaultNetwork: 'hardhat',
  networks: {
    hardhat: {
      chainId: 1337,
    },
    mantel: {
      url: "https://rpc.testnet.mantle.xyz",
      allowUnlimitedContractSize: true,
      accounts: [privateKey],
    },
  },
  solidity: {
    version: '0.8.4',
    settings: {
      optimizer: {
        enabled: true,
        runs: 200,
      },
    },
  },
};
```

## π· Built with

- [Solidity](https://docs.soliditylang.org/en/v0.8.17/ "Solidity"): as Main Coding Language for writing smart contract

- [ReactJs](https://reactjs.org/ "React Js"): as Main Coding Language for Creating The UI components (Front End)

- [TailwindCss](https://tailwindcss.com/ "Tailwind Css"): as Main Coding Language for styling UI components

- [IPFS](https://ipfs.tech/ "IPFS"): For Storing of files

- [Web3 Storage](https://www.google.com/search?q=web3storage "Web3 Storage"): For Storing of files

- [Github](https://github.com/ "Github") : For Repo Storage and source code management

- [Git](https://git-scm.com/ "Git") : For Version Control System

## π Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

- Fork the Project

- Create your Feature Branch (git checkout -b feature/AmazingFeature)

- Commit your Changes (git commit -m 'Add some AmazingFeature')

- Push to the Branch (git push origin feature/AmazingFeature)

- Open a Pull Request

## π Future Updates

- [ ] Mint memories as an NFT for explorers

- [ ] A mapping algorithm that displays explorers close to your location

## π§π» Author

**Sensurus Irupus**

- π [Profile](https://github.com/sensurusirupus "Pakari Isbum")

- π? [Email](sensurusirupus@gmail.com "Hi!")

<h2 align="center">π€ Support</h2>

<p align="center">π Contributions (<a href="https://guides.github.com/introduction/flow" title="GitHub flow">GitHub Flow</a>), π₯ issues, and π₯? feature requests are most welcome!</p>

<p align="center">π If you like this project, Give it a β­ and Share it with friends!</p>

<p align="center">Made with Solidity and Javascript & β€οΈ </p>

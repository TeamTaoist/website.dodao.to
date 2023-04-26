# https://dodao.to

**Dawn of DAO is a tool for DAOs to manage their treasury in a totally decentralized way.**   

There are lots of tools helping DAOs to do DAO governance, but most of them are partially decentralized and still rely on several people in DAO. When we tried to create our own venture DAO, we met lots of problems of lacking tools. For example, we cannot have a tool to manage our treasury publicly, since current multisig wallets are EOA address based. When we want to sign a contract with projects, we have to sign the contract personally under the name of our DAO. When we want to sell our assets in our treasury, we cannot do it securely. We tried to search for the best tools for us to start our DAO but failed. So we decided to create a tool based on the knowledge of the previously used DAO tools and ideas, to have a tool for DAO totally decentralized, as Uniswap brings the dex to a new level.  

Dawn of DAO provides a more decentralized way for the members of a DAO to manage their assets, a well-integrated voting system for governance, a contract signing tool for DAO, and a decentralized escrow service for DAO.  

In Dawn of DAO, we have three components at present.  

- A contract signing tool, named DAOSigner, provides the interface for DAOs to sign the contract with anyone, including other DAOs, using the multi-sign wallet integrated. Anyone who wants to sign a contract with a DAO just fills in the smart contract address of the DAO in the contract, then signs it.  

- A decentralized escrow tool, named entrust3, with this tool, DAO can publish specific tasks with a commission, those who have such resources or the ability to complete it will get the commission. It will solve the security problems for DAO. The assets in DAO are owned by each of the DAO members. For example, if a DAO owns several NFTs, such as Punk, the DAO members decide to sell it, but they cannot. Because most of the NFT marketplace is not designed for DAO, it's not possible to list NFTs by a DAO.  

- A treasury management tool, named dodao, the short name of Dawn of DAO, provides a multi-sign solution with a weighted voting system. dodao integrates DAOSigner and entrust3 and provides a smooth governance experience for DAOs. In our plan, 4337 wallet will be integrated to optimize the UE of dodao.  

### Build

All commands are run from the root of the project, from a terminal:

(no problem if you use NPM or Yarn)

| Command             | Action                                             |
| :------------------ | :------------------------------------------------- |
| `pnpm install`      | Installs dependencies                              |
| `pnpm dev`          | Starts local dev server at `localhost:3000`        |
| `pnpm build`        | Build your production site to `./dist/`            |
| `pnpm preview`      | Preview your build locally, before deploying       |
| `pnpm astro ...`    | Run CLI commands like `astro add`, `astro preview` |
| `pnpm astro --help` | Get help using the Astro CLI                       |


### Thanks

This website is based on [https://www.elian.codes](<https://www.elian.codes/>) and Brutal.  

Brutal is a minimal neobrutalist theme for [Astro](https://astro.build/). It's based on Neobrutalist Web Design, a movement that aims to create websites with a minimalistic and functional design. It has some integrations like Image Optimization, RSS, Sitemap, ready to get your SEO done right.  

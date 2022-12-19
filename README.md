# Launchpad
This repository contains intentionally organized and curated content for Protocol Labs' Launchpad program.
We welcome contributions, but please read the Contributing section below.

See the staging stite at: [https://empty-poetry-5978.on.fleek.co/](https://empty-poetry-5978.on.fleek.co/)

The default branch for this repository is **main** for the curriculum published on: https://curriculum.pl-launchpad.io/. 

**!Important** The content published on the now deprecated Gitbook at https://protocol-labs.gitbook.io/launchpad-curriculum is configured & published from the **gitbook** branch.  

## Contributing to the Launchpad Curriculum

Please work with the team to review and organize Launchpad Curriculum. In order to contribute, visit the public Launchpad repository: [https://github.com/protocol/launchpad](https://github.com/protocol/launchpad)


1. First, check out this README.md and [STYLE-GUIDE.md](https://github.com/protocol/launchpad/blob/gitbook/STYLE-GUIDE.md) in the root repo for how to format and organize your content.
2. Find the section in the [SUMMARY.md](https://github.com/protocol/launchpad/blob/main/SUMMARY.md) file where you want to add your content.
3. Create a new branch or fork, and find the .md doc (or create a new .md file) in the `/content/en/curriculum` [directory](https://github.com/protocol/launchpad/tree/main/content/en/curriculum) where you would like to add your content.
  * Each section IPFS, IPLD, etc has a directory. In that directory a section may be _either_ a .md file, or a directory with an `index.md` file and assets (images).
4. Create a PR for your change to the `main` branch. Flag the [most active contributors](https://github.com/protocol/launchpad/graphs/contributors). 

**Questions?** [ping the core contributors](https://github.com/protocol/launchpad/graphs/contributors) to this repository, or open an [Issue](https://github.com/protocol/launchpad/issues).

## Sections

### Pre-Requisites
* Web3 and Protocol Labs
* Building Web3
* Web3 Tools

### Launchpad Learning Resources
* [The Protocol Labs Network](docs/protocol-labs-network/README.md)
* [IPFS](docs/ipfs/README.md)
* [IPLD](docs/ipld/README.md)
* [LibP2p](docs/libp2p/README.md)
* [Filecoin](docs/filecoin/README.md)

### Dev Tools
* [Protocol Labs Toolkits & SDKs](docs/protocol-labs-toolkits-sdks/README.md)
* [Built on IPFS and Filecoin](docs/built-on-ipfs-filecoin/README.md)
* [Additional Learning](docs/additional-learning-resources/README.md)

## Hugo
Use Hugo to statically serve & preview files on your machine

* Create a [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) of this repo or simply use `git clone git@github.com:protocol/launchpad.git`
* Open the `/launchpad` folder where you cloned it 
* Install version 0.101.1 + of Hugo with `brew install hugo`
* Run `npm install` from the top level of the launchpad repository
* Run `hugo server` to start hugo & preview this on `localhost:1313`

> Note that you may have the run `npm install` on new/ others' branches you checkout and server before running `hugo server`

#### Editing Content

Content is located in `content/en/` and the directories in there will be one of the links along the top of the page.

Edit the landing pages in `section-name/index.html` or `section-name.md`

Edit Sidebar content in `config/_default/menus/menus.en.toml`

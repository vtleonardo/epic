# Information about this repository

This repository is a fork from the https://github.com/EpicCash/epic. 

The epic project was developed on GitLab by the company Brick Abode and later migrated to Github. The EPIC project is an Open-Source project completely written in Rust.

This fork was created to highlight my contributions when working at Brick Abode with a different GitLab/GitHub account. 

All of my contributions can be seen on:
https://github.com/vtleonardo/epic/commits?author=leonardo-brickabode

**Some contributions were lost between project migrations from internal repositories to public repositories.**

During this project, I worked with:
- Implementing the new consensus algorithm to work with the 3 different Prof of work (PoW) algorithms: Cuckoo, ProgPow, and Random X
- Changing the blockchain structure to generate the blocks every 1 minute with a deflationary structure
- Refactoring the blockchain Rest and JSON-RPC APIs
- Refactoring the rust tests to use the [Gherkin Syntax](https://cucumber.io/docs/gherkin/)
- Bug-fixes

**I don't intend to update/develop this repository, check the original repository for code changes and updates.**

# Epic Cash

Epic Cash is an in-progress implementation of the MimbleWimble protocol. Epic Cash redefined new core characteristics of this new privacy focused blockchain forked from Grin, following constitutes a first set of choices:

  * Block rewards epoch & total supply to match Bitcoin
  * Support diversity of mining hash powers using a combination of algorithms
  * Clean and minimal implementation, and aiming to stay as such.
  * Follows the MimbleWimble protocol, which provides great anonymity and scaling characteristics.
  * Cuckoo Cycle proof of work with the CuckAToo31+ (ASIC-targeted).
  * Relatively fast block time: one minute.
  * Transaction fees are based on the number of Outputs created/destroyed and total transaction size.
  * Smooth curve for difficulty adjustments.

## Status

Epic is live with mainnet.

## Getting Started

To build and try out Epic, see the [build docs](doc/build.md).

To run the Epic Cash blockchain on Linux distributions, see the tutorial of [How to run the Epic Cash blockchain on Linux](doc/running.org).

To run the Epic Cash blockchain on windows, see the tutorial of [How to run the Epic Cash blockchain on Windows](doc/windows.org).

## Credits

Tom Elvis Jedusor for the first formulation of MimbleWimble.

Andrew Poelstra for his related work and improvements.

John Tromp for the Cuckoo Cycle proof of work.

Grin Developers for the initial implementation

J.K. Rowling for making it despite extraordinary adversity.

## License

Apache License v2.0.

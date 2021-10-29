# Menace Improvement Proposals

This is the repository that contains the Menace Improvement Proposals (MIPs) used by the Fantom Menace DAO to run our DAO. 


## How to Contribute (THIS IS WORK-IN-PROGRESS)

Review MIP-1 (To be implemented) 

Fork the repository by clicking "Fork" in the top right.
Add your MIP to your fork of the repository. There is a template MIP here.
Submit a Pull Request to `FantomMenaceDAO/MIPs` repository.

Your first PR should be a first draft of the final MIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new MIP and assign it a number before merging it. Make sure you include a discussions-to header with the URL to a new thread on research.synthetix.io where people can discuss the MIP as a whole.

If your MIP requires images, the image files should be included in a subdirectory of the assets folder for that MIP as follow: `proposals/mip-X` (for MIP X).

When you believe your MIP is mature and ready to progress past the Draft phase, and you need help either reach out to (@0xJuly for now) or just post it on the #governance channel. We can schedule a call with the MIP author to go through the MIP in more detail.

Once assessed, a MIP is moved into Feasibility and a Owners should largely be self-assigned. The Core Contributor will work with the author to conduct a feasibility study. Once the Author and the Core Contributor are satisfied, a MIP is moved to Review Pending. 

A vote is conducted within the spartancouncil.eth snapshot space connected on the staking dApp. If a vote by the Spartan Council reaches a super majority, the MIP is moved to Approved, otherwise it is Rejected.

Once the MIP has been implemented by either the protocol DAO or the MIP author and relevant parties, the MIP is assigned the Implemented status. 

There is a 500 USDC bounty for proposing a MIP that reaches the Implemented phase.

## MIP Statuses
- `Draft` - The initial state of a new MIP before the Council and core contributors have assessed it.
- `Proposed` - a MIP that has been proposed for feasibility by core contributors and is awaiting a vote pending priority of proposals
- `InVoting` - a MIP that is in the voting period
- `Approved` - a MIP that has successfully reached a vote in favor
- `Rejected` - a MIP that has failed to reach a vote in favour
- `Executed` - a MIP that has been executed

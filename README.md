# WIPs
WIRE Improvement Proposals (WIPs) describe standards for the WIRE platform, including core protocol specifications, client APIs, and contract standards.

# Contributing

 1. Review [WIP-1](WIPS/wip-1.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your WIP to your fork of the repository. Please follow the format described in [WIP-1](WIPS/wip-1.md) under the 'What belongs in a successful WIP?' section.
 4. Submit a Pull Request to the WIRE [WIPs repository](https://github.com/siliconswampio/WIPs).

Your first PR should be a first draft of the final WIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new WIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the WIP as a whole.

If your WIP requires images, the image files should be included in a subdirectory of the `assets` folder for that WIP as follow: `assets/wip-X` (for wip **X**). When linking to an image in the WIP, use relative links such as `../assets/wip-X/image.png`.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft WIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your WIP contains either your GitHub username or your email address within triangle brackets (ex: < example@email.com >). If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

When you believe your WIP is mature and ready to progress past the draft phase, you should open a PR changing the state of your WIP to 'Submitted'. An editor will review your submission, mark it 'Ready for Review', and set an ad-hoc meeting to discuss the proposal. The discussions will determine how the proposal will flow through the WIPs lifecycle.

# WIP Status Terms
* **Draft** - the WIP is currently a work in progress and has not yet been submitted
* **Submitted** - the final draft of the WIP has been subitted by the WIP author
* **Ready for Review** - the WIP has been reviewed by an WIP editor and has been added to the agenda for the next WIP review meeting
* **Accepted** - the WIP was analyzed and discussed by the WIP reviewers and has sufficient support for implementation
* **Under Development** - the WIP is currently under developmnet
* **Pending PR Review** -the WIP implementation is currently being reviewed for final acceptance
* **Final** - the WIP has been successfully implemented and is now active
* **Deferred** - the WIP has been shelved for future consideration
* **Living** - this is similar to Final, but denotes an WIP which requires regular updates for accuracy (good for token/wallet standards)
* **Archived** - the WIP is no longer under consideration (withdrawn by author, not enough support for the proposal, etc.)

# Connect 
If you are interested in discussing proposal ideas, providing feedback on existing proposals or the WIPs process, or want to get more involved, join the [WIRE discord](https://discord.gg/UfbEx2rSwz)
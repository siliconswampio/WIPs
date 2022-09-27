---
WIP: 1
title: WIP Purpose and Guidelines
author: WIRE Network
status: Living
type: Draft
created: 2022-9-27
updated: 2022-9-27
---

## What is an WIP?

WIP stands for WIRE Improvement Proposal. An WIP is a design document providing information to the WIRE community, or describing a new feature for WIRE or its processes or environment. The WIP should provide a concise technical specification of the feature and a rationale for the feature. The WIP author is responsible for building consensus within the community and documenting dissenting opinions.

This process is specifically for the WIRE protocol. Proposals for EOS mainnet are out of scope for WIPs.

## WIP Rationale

We intend for WIPs to be the primary mechanism for proposing new features, for collecting community input on an issue, and for documenting the design decisions that have gone into WIRE. Because WIPs are maintained as text files in a versioned repository, their revision history is the historical record of the feature proposal.

For WIRE implementers, WIPs are a convenient way to track the progress of their implementation. Ideally each implementation maintainer would list the WIPs that they have implemented. This will give end users a convenient way to know the current status of a given implementation or library.

## WIP Roles & Responsibilities

Parties involved in the process are the champion or WIP author, the WIP editors, and the WIP reviewers.

### Role of an WIP champion or author

The role of the champion is to write the WIP using the style and format described below, shepherd the discussions in the appropriate forums, and build community consensus around the idea.

### Role of an WIP editor

#### For each new WIP that comes in, an editor does the following:
* Reviews the WIP to check if it is ready, sound, and complete.
* Verify the proposal makes technical sense, even if it does not seem likely to get to final status.
* Verifies the title accurately describe the content.
* Check the WIP for language (spelling, grammar, sentence structure, etc.), markup (Github flavored Markdown), code style.

If the WIP isn’t ready, the editor will send it back to the author for revision, with specific instructions.

#### Once the WIP is ready for the repository, the WIP editor will:
* Assign an WIP number (generally the PR number or, if preferred by the author, the Issue # if there was discussion in the Issues section of this repository about this WIP).
* Merge the corresponding pull request.
* Mark the WIP with a 'Ready for Review' status and schedule an ad-hoc WIP review meeting with the WIP author and WIP reviewers to discuss next steps

Many WIPs are written and maintained by developers with write access to the WIRE codebase. The WIP editors monitor WIP changes, and correct any structure, grammar, spelling, or markup mistakes we see.

The editors don’t pass judgment on WIPs. We merely do the administrative & editorial part.

The current WIP editors are:
...
...

### Role of the WIP reviewers

The WIP reviewers are responsible for reviewing WIP submissions and deciding next steps. Once an WIP has been submitted by an author and reviewed by an WIP editor, it is added to the agenda for the next review meeting.

WIP review meetings will be held ad-hoc at the beginning of the WIP launch and a regular cadence will be determined at a later date. The agenda and meeting details, minutes, and recording will be shared publicly (similar to Ethereum's approach) and facilitated by the WIP editors. Anyone from the WIRE community is welcome to participate and provide technical input and feedback on WIP submissions.

## WIP Workflow

#### Before Submitting An WIP
* Vet your idea, this will save you time. Ask the WIRE community first if an idea is original to avoid wasting time on something that will be rejected based on prior research (searching the Internet does not always do the trick).
* It also helps to make sure the idea is applicable to the entire community and not just the author. Just because an idea sounds good to the author does not mean it will work for most people in most areas where WIRE is used.

#### Examples of appropriate public forums to gauge interest around your WIP include:
* [the WIRE discord](https://discord.gg/UfbEx2rSwz)

> In particular, the issues section of the WIPs repository is an excellent place to discuss your proposal with the community and start creating more formalized language around your WIP.

#### Submit an WIP
1. Navigate to WIRE’s official [WIP repository](https://github.com/siliconswampio/WIPs)
1. Navigate to WIRE’s official WIP repo here
2. Use a pull request to update the status. Please include a link to where people should continue discussing your WIP.
3. The WIP editors will process these requests. Once you’ve submitted your WIP, the WIP will have a ‘Submitted’ status.

#### WIP Review by an WIP Editor
* An WIP editor will review the submitted WIP.
* If the WIP is ready for review at the next WIP review meeting, the WIP editor will merge the WIP into the main repository.
* If the editor has feedback, the WIP editor will correspond with the author until the WIP is ready for review.
* Review new proposals at the WIP review meeting.
* Once an WIP editor has approved an WIP submission into “Ready for Review” status, it is added to the agenda for the next WIP review meeting.
* At the WIP review meeting, proposals are reviewed and discussed. There are four possible paths an WIP submission may take at the WIP review meeting:
  * **Deferred:** the WIP submission presents a good idea for the future but cannot be accepted immediately; it will be revisited in the future
  * **Accepted:** the WIP submission presents a good idea and can begin development immediately
  * **Living:** the WIP requires regular updates and will be a living proposal
  * **Archived:** either the author retracts their WIP submission or the WIP does not obtain the consensus it needs to be implemented

#### WIP Next Steps
Based on the next steps decided at the WIP review meeting:
  * **If Deferred:** the WIP will be revisited at a future meeting
  * **If Accepted:** the WIP is now available for development
  * **If Living:** the WIP will be regularly reviewed to ensure accuracy
  * **If Archived:** the justification will be recorded and the WIP will no longer be pursued

#### WIP Happy Path
1. An WIRE community member submits an WIP proposal in the correct format and a "Submitted" status.
2. An WIP editor reviews the submission, verifies it is ready for review, schedules time to discuss the WIP with WIP reviewers.
3. WIP reviewers accept the WIP, making the proposal available for development. Any interested entity may begin the implementation of the WIP.
4. Once an WIP has been developed, it will go under PR review.
5. The WIP will pass the PR review and achieve a “Final” status.

## WIP Statuses
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

## What belongs in a successful WIP?
It is highly recommended that a single WIP contain a single key proposal or new idea. The more focused the WIP, the more successful it tends to be. A change to one client doesn’t require an WIP; a change that affects multiple clients, or defines a standard for multiple apps to use, does.

#### An WIP must meet certain minimum criteria:
* It must be a clear and complete description of the proposed enhancement.
* The enhancement must represent a net improvement.
* The proposed implementation, if applicable, must be solid and must not complicate the protocol unduly.
* The proposal must be chain-agnostic.

#### Each WIP should have the following parts:
**Preamble:** RFC 822 style headers containing metadata about the WIP, including the WIP number, a short descriptive title (limited to a maximum of 44 characters), and the author details. See below for details.

**Simple Summary:** “If you can’t explain it simply, you don’t understand it well enough.” Provide a simplified and layman-accessible explanation of the WIP.

**Abstract:** a short (~200 word) description of the technical issue being addressed.

**Motivation (*optional):** The motivation is critical for WIPs that want to change the WIRE protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the WIP solves. WIP submissions without sufficient motivation may be rejected outright.

**Specification:** The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current WIRE platforms (eos-go, eosjs).

**Rationale:** The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

**Backwards Compatibility:** All WIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The WIP must explain how the author proposes to deal with these incompatibilities. WIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

**Test Cases:** Test cases for an implementation are mandatory for WIPs that are affecting consensus changes. Other WIPs can choose to include links to test cases if applicable.

**Implementations:** The implementations must be completed before any WIP is given status “Final”, but it need not be completed before the WIP is merged as draft. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of “rough consensus and running code” is still useful when it comes to resolving many discussions of API details.

**Security Considerations:** Discuss the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surface risks and can be used throughout the life cycle of the proposal.

**Intellectual Property:** All WIPs submissions must contain the following text: “I hereby agree that this WIP is subject to this [copyright waiver](https://creativecommons.org/publicdomain/zero/1.0/) and I certify that I have all necessary rights and permissions to make this submission and to agree to such waiver.”

## WIP Types
There are four types of WIPs:
1. A **Standard WIP** describes any change that affects most or all WIRE implementations, such as a change to the network protocol, a change in block or transaction validity rules, proposed application standards/conventions, or any change or addition that affects the interoperability of applications using WIRE. 

Furthermore Standard WIPs can be broken down into the following categories. Standards Track WIPs consist of three parts, a design document, implementation, and finally if warranted an update to the formal specification.
  * **Core:** improvements requiring a consensus fork, as well as changes that are not necessarily consensus critical but may be relevant to Block Producer and WIRE discussions 
  * **Networking:** improvements around the p2p protocol
  * **Interface:** includes improvements around client API specifications and standards, and also certain language-level standards like contract ABIs. For contract ABIs, it aligns with the [wire.contracts repo](http://git.siliconswamp.io:3000/Air_Wire/wire.contracts) and discussion should primarily occur in that repository before an WIP is submitted to the WIRE/WIPs repository
  
2. An **Informational WIP** describes an WIRE design issue, or provides general guidelines or information to the WIRE community, but does not propose a new feature. Informational WIPs do not necessarily represent WIRE community consensus or a recommendation, so users and implementers are free to ignore Informational WIPs or follow their advice.

3. A **Meta WIP** describes a process surrounding WIRE or proposes a change to (or an event in) a process. Process WIPs are like Standard Track WIPs but apply to areas other than the WIRE protocol itself. They may propose an implementation, but not to WIRE's codebase; they often require community consensus; unlike Informational WIPs, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in WIRE development. Any meta-WIP is also considered a Process WIP.

4. An **Archived WIP** desribes a previously submitted WIP submission that does not have a type or category from the list above.

## WIP Formats and Templates

WIPs should be written in [markdown](https://www.markdownguide.org/basic-syntax/) format.

Image files should be included in a subdirectory of the `assets` folder for that WIP as follows: `assets/wip-X` (for wip **X**). When linking to an image in the WIP, use relative links such as `../assets/wip-X/image.png`.

#### WIP Header Preamble
Each WIP must begin with an RFC 822 style header preamble, preceded and followed by three hyphens (`---`). The headers must appear in the following order. Headers marked with an asterisk are optional and are described below.

All other headers are required.

`wip:` <WIP number> (this is determined by the WIP editor)

`title:` <WIP title> (a high-level title of the WIP)

`author:` <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s). Details are below.>

`* discussions-to:` <add a link>

`status:` <Draft | Submitted | Ready for Review | Accepted | Under Development | Pending PR Review | Final | Deferred | Living | Archived>

`* review-period-end:` YYYY-MM-DD

`type:` <Standard | Informational | Meta | N/A>

`* category:` <Core | Networking | Interface | N/A> 

`created:` <date created on, in ISO 8601 (yyyy-mm-dd) format>
 
`* updated:` <date the wip was last updated on, in ISO 8601 (yyyy-mm-dd) format>

`* requires:` <WIP number(s)>

`* replaces:` <WIP number(s)>

`* superseded-by:` <WIP number(s)>

`* resolution:` <add a link>

#### Author Header
 
The author header optionally lists the names, email addresses or usernames of the authors/owners of the WIP. Those who prefer anonymity may use a username only, or a first name and a username.

The format of the author header value must be Random J. User &lt;address@dom.ain&gt;

or Random J. User (@username) if the email address or GitHub username is included,
 
or Random J. User if the email address is not given.

#### Additional Header & Template Guidelines

The resolution header is required for Standards Track WIPs only. It contains a URL that should point to an email message or other web resource where the pronouncement about the WIP is made.

While an WIP is a draft, a `discussions-to` header will indicate the mailing list or URL where the WIP is being discussed. As mentioned above, examples for places to discuss your WIP include:
* [the WIRE discord](https://discord.gg/UfbEx2rSwz)
 
No `discussions-to` header is necessary if the WIP is being discussed privately with the author.

The `type` header specifies the type of WIP: Standards Track, Meta, or Informational. If the track is Standards please include the subcategory (core, networking, interface, or RFC). 

The `category` header specifies the WIP's category. This is required for standards-track WIPs only.

The `created` header records the date that the WIP was assigned a number. Both headers should be in yyyy-mm-dd format, e.g. 2001-08-14.

WIPs may have a `requires` header, indicating the WIP numbers that this WIP depends on.

WIPs may also have a `superseded-by` header indicating that an WIP has been rendered obsolete by a later document; the value is the number of the WIP that replaces the current document. The newer WIP must have a Replaces header containing the number of the WIP that it rendered obsolete.

Headers that permit lists must separate elements with commas.

#### Auxiliary Files

WIPs may include auxiliary files such as diagrams. Such files must be named WIP-XXXX-Y.ext, where “XXXX” is the WIP number, “Y” is a serial number (starting at 1), and “ext” is replaced by the actual file extension (e.g. “png”).

## Transferring WIP Ownership

It occasionally becomes necessary to transfer ownership of WIPs to a new champion. In general, we’d like to retain the original author as a co-author of the transferred WIP, but that’s not always possible or may not be the preference of the original author. A good reason to transfer ownership is because the original author no longer has the time or interest in updating it or following through with the WIP process, or has fallen off the face of the net (i.e. is unreachable or isn’t responding to email). A bad reason to transfer ownership is because you don’t agree with the direction of the WIP. We try to build consensus around an WIP, but if that’s not possible, you can always submit a competing WIP.

If you are interested in assuming ownership of an WIP, send a message asking to take over, addressed to both the original author and the WIP editor. If the original author doesn’t respond to email in a timely manner, the WIP editor will make a unilateral decision (it’s not like such decisions can’t be reversed).

## History

This document was derived heavily from [Ethereum’s EIP-1] & [EOS's EEP-1] written by Martin Becze, Hudson Jameson, and others, which was derived from [Bitcoin’s BIP-0001] written by Amir Taaki which in turn was derived from [Python’s PEP-0001]. In many places text was simply copied and modified. Although the PEP-0001 text was written by Barry Warsaw, Jeremy Hylton, and David Goodger, they are not responsible for its use in the WIRE Improvement Proposal process, and should not be bothered with technical questions specific to WIRE or WIPs. Please direct all comments, questions, and feedback to the WIP editors.

## Legal

By participating in the WIP process you agree to terms set forth in this document. If you do not agree to these terms, you may not participate in the WIPs process.

#### Conduct
While participating in this process, please be respectful and constructive, so that participation in our project is a positive experience for everyone.

##### Examples of behavior that contributes to creating a positive environment include:
* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

##### Examples of unacceptable behavior include:
* The use of sexualized language or imagery and unwelcome sexual attention or advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others’ private information, such as a physical or electronic address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a professional setting

#### Confidentiality
All WIPs, editor feedback on WIPs, and WIPs reivew meeting discussions or feedback on WIPs are considered non-confidential information and may be disclosed to third parties. This could lead to a third party developing an idea, concept, design or standard described in your WIP without your permission or involvement.

#### Additional Requirements
  
##### By participating in the WIP process, you certify that:
You are not, are not acting on behalf of another party that is, and no party with a beneficial interest in you is: subject to sanctions administered or enforced by any country or government or otherwise designated on any list of prohibited or restricted parties (including but not limited to the lists maintained by the United Nations Security Council, the U.S. Government, the European Union or its Member States, or other applicable government authority)(“Sanctions”); or
organized or resident in a country or territory that is the subject of country-wide or territory-wide Sanctions.

##### And you acknowledge and agree that:
 * All WIPs, editor feedback on WIPs and WIP review meeting discussions or written feedback on WIPs are subject to this [copyright waiver](https://creativecommons.org/publicdomain/zero/1.0/).
 * The WIP process does not create an obligation to consider, develop or implement any idea, design, concept or standard that you include in an WIP

The WIP process, including but not limited to WIP editing and WIP reviewer feedback is provided without warranty, guarantee or undertaking of any kind, whether express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. 
  
In no event shall an WIP editor, an WIP reviewer or Bullish Global or its affiliates (“WIP Participants”) be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the WIP process and you waive any claim that you may have against such parties related to their participation in the WIP process 

You will not make WIP materials available to any person or entity that is the subject of Sanctions or organized or resident in a country or territory that is the subject of country-wide or territory-wide Sanctions.  You will comply with all applicable import, re-import, sanctions, anti-boycott, export, and re-export control laws and regulations.  If this is not accurate or you do not agree, then you must immediately cease accessing the WIP materials and delete all copies thereof.

Any reference to any third party or third-party product, resource or service is not an endorsement or recommendation by an WIP Participant. WIP Participants are not responsible for, and disclaim any and all responsibility and liability for, your use of or reliance on any of these resources.

#### Forward Looking Statements

When an WIP Participant makes statements expressing its vision, it does not guarantee anything, and all aspects of its vision are subject to change at any time and at such participant’s sole discretion, with or without notice. We call these “forward-looking statements”, which includes statements on an WIP Participant’s website and in other materials, such as statements regarding WIRE’s development, expected performance, and future features, or business strategy, plans, prospects, developments and objectives. These statements are based on assumptions and are subject to risk, uncertainties and change at any time.

WIP Participants operate in a rapidly changing environment and new risks emerge from time to time. Given these risks and uncertainties, you are cautioned not to rely on these forward-looking statements. Actual results, performance or events may differ materially from what is predicted in the forward-looking statements. Some of the factors that could cause actual results, performance or events to differ materially from the forward looking statements include, without limitation: technical feasibility and barriers; market trends and volatility; continued availability of capital, financing and personnel; product acceptance; the commercial success of any new products or technologies; competition; government regulation and laws; and general economic, market or business conditions.

All statements are valid only as of the date of first posting and WIP Participants are not under and expressly disclaim any obligation to update or alter any statements, whether as a result of new information, subsequent events or otherwise. Nothing provided in the WIP process constitutes technological, financial, investment, legal or other advice, either in general or with regard to any particular situation or implementation. Please consult with experts in appropriate areas before implementing or utilizing any content, guidance or feedback received as part of the WIP process.
Trademarks: WIRE, EOS, the heptahedron and associated logos and related marks are Bullish Global’s trademarks.

## Bibliography

* [wire..contracts](http://git.siliconswamp.io:3000/Air_Wire/wire.contracts)

* [eosio.contracts](https://github.com/eosio/eosio.contracts)
  
* [the EOS subreddit](https://www.reddit.com/r/eos/)
  
* [WIP Telegram Channel](https://t.me/eos_enhancements_proposals)
  
* [pull request](https://github.com/eoscanada/EEPs/pulls)
  
* [the Issues section of this repository](https://github.com/eoscanada/EEPs/issues)
  
* [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  
* [Ethereum's EIP-1](https://github.com/ethereum/EIPs/)
  
* [Bitcoin's BIP-0001](https://github.com/bitcoin/bips)
  
* [Python's PEP-0001](https://www.python.org/dev/peps/)

* [EOS's EEP-1](https://github.com/EOSIO/EEPs/blob/master/EEPS/eep-1.md)

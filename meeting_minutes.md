# Meeting Minutes: Technical Specification of General Layer 2 Blockchain Scalability Solutions for EVM-compatible public Blockchains WG

## Meeting Wed, 19th Jan 2022, 7 am PT

Attending: Andreas Freund, Tas Dienes, Samrat Kishore, Cody Burns, Matthias Geihs, David Katz, Sebastian Stammler, Kyle Thomas

Scribe: Tas Dienes

Proposed agenda:
* Welcome and reminder of the WG rules
* Introduction of new members
* Selection of Scribe
* Update on OASIS WG infrastructure set-up and required steps from the WG e.g. selection of chairs
* Discussion of suggested approach to alternate meeting times
* Discussion on Work Items and selecting at least one work item to begin work

### Notes
New members: Matthias Geihs from Perun, working on state channels with Sebastian Stammler; David Katz from Accenture

Github repo has been set up https://github.com/eea-oasis/general-L2-scalability

Repo name will be changed to “L2”.  

Kyle proposes to be an admin.  Motion approved. 

Contributors will have to add themselves to the readme.md file via a PR
Directories for work items and docs will be created

Andreas and Kyle will be initial maintainers who can approve PRs.  PRs require 2 approvals.

Chair and vice-chair need to be chosen; AF to call for nominations by email.

Doodle poll for new meeting time(s) has been sent out 

Slack will be set up by AF, starting with a business account 

Work item discussion.  We will start with these. AF to create folders.
* “Managing assets with residuals” 
* “Precompiles of most common L2 onboarding or exit functions to reduce L2 gas costs”
* “Layer 2 privacy guarantees that do not compromise on security”


## Meeting Wed, 12th Jan 2022, 7 am PT

Attending: Andreas Freund, Tas Dienes, Dan Shaw, John Wolpert, Samrat Kishore, Alim Karim
Scribe: Tas Dienes

Proposed Agenda:
* Welcome and rules reminder
* Selection of Scribe
* Introduction of new members
* Next steps to set up WG with OASIS (Github, Gitbook etc.)
* Review, prioritize and select the first work items to work on and the first timelines for delivery based on our existing work item list.

### Notes
The project has been approved by PGB!  

Next, request OASIS to create a github repo, and select maintainer(s).  Then add charter and governance docs to the repo, readme.md.
Discussion of the work item list

JW suggests defining what is not an L2 and what is not

JW asks if we need a new “L2IP” standards system or use EIP system. The consensus is that we can probably use EIP system for now.

How to increase attendance:
Consider alternating between two times  
Tas is to create a Doodle poll 

Contact potential participants 1 on 1, mention proposed work items, ask if a different meeting would help

In emails to the group, consider BCCing people who have expressed interest but don’t show up regularly 

## Meeting Wed, 15th Dec 2021, 7 am PT

Attending: Andreas Freund, Tas Dienes, John Wolpert, Bobbin Threadbare (Polygon Miden), Ravikant Agarwal (Polygon)

Scribe: Tas Dienes

### Notes
Governance doc status - resolving comments from Chaals (EEA).  Will be discussed in tomorrow’s EEA Community Project PGB meeting.

Bobbin Threadbare introduction.  

Reviewed work item brainstorming doc.

Next meeting is on January 12th

## Meeting: Wed, 8th Dec, 2021, 7 am PT / 10 am ET / 16:00 BST

Scribe: Tas Dienes

Proposed Agenda:
* Selection of Scribe
* Introduction of new participants
* Meeting Minute Corrections (if required)
* Update from the EEA Community Projects' Project Governance Boards meeting with regard to their feedback a-on Charter and Governance Document (TL/DR: WG is good to go to start working. Just some clarifying minor edits/additions -- will review those during our meeting. Nothing substantial)
Review Workitem Backlog document --   https://docs.google.com/document/d/1AzcuzBNkeQUGJ3EbtaxNHRmq91fSjAspBak26wZjSRo/edit?usp=sharing
 
Attendees: Andreas, Tas, Samrat, Kyle, Dan Shaw, Cody Burns, Alim Karim, Julien Marchand, Kartheek Solipuram

Tas volunteered to scribe

No new participants

Governance doc
https://docs.google.com/document/d/1MNl3jjR5EJF3xM5QSteslklVJUKKEPCP7wHaTxSSK8c/edit?pli=1

Minor edits made to governance doc based on feedback from Dan Burnett.

The WG is also the TSC

We can switch the license from CC0 to Apache 2.0 - but Kartheek is going to check with EY legal about this

Charter doc
https://docs.google.com/document/d/16LZluUzG0RSHpVpYiXVucibv_A7ZWN0GZQvvfW21tiQ/edit?pli=1

Edits made to governance doc based on feedback from Dan Burnet and others.
PGB is expected to vote on these when all comments are resolved. Aim to have them approved by end of the year.

Work items
https://docs.google.com/document/d/1AzcuzBNkeQUGJ3EbtaxNHRmq91fSjAspBak26wZjSRo/edit?pli=1#heading=h.n59e8xyug3dx

Kyle brought up virtualizing a L2 - containerized version of an L2 with a generalized interface. Unified interface application facing API.

Ideas from Vitalik - Tas to add to work item list 
* Standard or recommendation for transitioning from a sidechain to a true L2
* Support the L2 ENS effort, and make sure every dapp that supports ENS also supports it
* L2 state data availability backup 

Kyle will work on item 2b 

Andreas and Alim will work on 4b

NFTs/NFT transfer? NFT royalties cross-chain - Kartheek is interested in working with Andreas on this. Kyle too. 

Next meeting December 15, then January 12.  AF will send cancellations for 3 weeks in between.


## Meeting: Wed, 17th Nov, 2021, 7 am PT / 10 am ET / 16:00 BST

Scribe: Dan Shaw

Attending: Andreas, Tas Dienes, Dan Shaw, Chet Ensign,
Alim Karim,
Karthik Solimpuram,
Samrat Kishor,
Sandeep Nailwal, Polygon (new member),
Samrat Kishor,
Sebastian Stammler,
Steven Goldfeder

Andreas introduces Chet Ensign of OASIS.

Chet is the point of contact with the OASIS staff who is responsible for facilitating participants.

Explains the rules

Find a way to complete the work

OASIS has been involved in Open Source and OPEN Standards since 1993. Ensure IPR. Ensure correct voting procedures.

OASIS is particularly beneficial when the work you’re working on is desired to be an international standard.

Chet notes changes to how folks are building things. Open Source now exceeds Open Standards as a starting point. Provides open source work a path to standards. Most projects want to start as an Open Project. EEA retains the brand, governed by the OASIS process.

EEA Open Projects is the umbrella group for Baseline Protocol, JSON

The project chair reports regularly to the EEA Community Projects project governing board (PGB).

Benefits: Projects get both the EEA stamp of approval and the OASIS stamp of approval. You can determine what goes forward as an OASIS standard. OASIS can steward the standardization process through a number of international standards bodies.

Process for PGB approval: likely within 2 weeks.

Thank you, Chet.

7:25: Sandeep Nailwal representing Polygon introduces himself and provided an overview of Polygon’s offerings, involvement in the ecosystem, and interest in Layer 2.

7:30: Back to the governance review

A suggestion has been made to consider changing the license from CC0 1.0 Universal to Apache 2.0. Apache 2.0 is the default for EEA Community Projects. Chet Ensign noted that CC0 is needed by companies like EY and Accenture (organizations with audit departments).

Sebastian expressed concern that CC0 might deter some contributors from engaging with the project since it is an unknown license.

Chet asks if there were any explicit objects to Apache 2.0 as the license.

Kartheek will check with EY legal to make sure if the project only produces specification text that Apache 2.0 will be OK.

Sebastian expresses concern that solidity interface files might not be adopted if they are using the CC0 license.

No objections were made to the improved definition of the “substantial” participation requirement for working group membership.

Decision-Making Process was reviewed and ratified without objection.

The ratification Process was reviewed and ratified without objection.

Andreas called for final objections. None were made. The governance doc will be submitted with a known open issue for final license selection between CC0 and Apache 2.0, both of which are approved licenses.

From Chat:

Alim: Andreas — re. License — on my side checking with the VMW legal team as well for our participation. Expect to have an answer by next week.

Action Items:
* Kartheek: To check with EY legal to make sure if the project only produces specification text that Apache 2.0 will be OK 
* Alim: To check with the VMW legal team as well for our participation. Expect to have an answer by next week.
* Tas (as PGB member): Submit Charter and Governance doc for approval to EEA - OASIS PGB during next PGB meeting; Status: Submitted awaiting a decision on 1st of December meeting.


## Meeting: Wed, 10th Nov, 2021, 7 am PT / 10 am ET / 16:00 BST

Canceled due to lack of attendance.


## Meeting: Wed, 3rd Nov, 2021, 7 am PT / 10 am ET / 16:00 BST

Participants: Alim (VMWare), Cody (Accenture), Robert (ConsenSys), Julien (ConsenSys), Kyle (Provide), Samrat (Golden Next Ventures), Sebastian (Perun), Tas (Ethereum Foundation), Dan (Ethereum Foundation), Andreas (Ethereum Foundation), 

11/3 Meeting Agenda
* Previous Meeting Notes Corrections (if required)
* Introduction of new participants
* Selection of Scribe
* Continue Review of WG Charter (continuing with Key Stakeholders Section)
* Start WG Governance Draft Review

* Action items from 11/3 WG meeting
* Action item: WG members to review & provide feedback on any headlines/sections missing from governance doc
* Action item: WG members to review details of sections in governance doc
* Action item: Andreas to invite Chad from OASIS to the next meeting to give feedback on charter, governance & license (CC0)

1. Review & Correction of notes from the last meeting
Notes for this meeting will include corrections from Samrat

2. Intro of new members
Kyle, Alim, Julien
3. Selection of Scribe for this meeting
Alim
4. Review of WG Charter

4.1 Stakeholder section

Sponsors definition - intended to be organizational supporters of this WG. Sponsors don't have other commitments other than favorable PR mention.

Sponsors of EEA Community Projects indirectly are sponsors of this initiative - to be added into Stakeholder section

Chains this WG will focus on

Definition: Which chains are we actively writing standards for?
Focus on public blockchains, add specificity by targeting EVM compatible chains so that standards developed are not overly generic

Team members

Keep as a rolling list as orgs join

4.2 WG milestones - 2021

Reviewed milestones in doc

Launch -- done

Charter by mid-Nov -- on track

Success metrics for WG by EO Nov -- on track

Kick off one workstream by EO 2021 --

Goals:

Added goal #6 ("Facilitate interoperability between different applications ...") based on the last WG discussion.

Refine wording to include environment/tooling aspects

List of L2 projects out there?

Published by EEA (authored by Andreas) this week.

L2 beat.

4.3 Budget
N/A at this time

4.4 Constraints

Constraints
WG members are
Proposal: Lean/agile standards development - smaller initiatives with frequent delivery. Example: defining smart contract input/output standards. No objections to this.

Assumptions
EVM-compatible was added as an assumption.
Risks & Dependencies
No changes

Charter doc walkthrough & edits complete

Governance Doc (link):

Doc originated from Baseline governance doc
Action item: WG to provide feedback on any headlines/sections missing from governance doc

Decision: Will run current doc by the OASIS representative on the PGB to get early feedback

License and Patent Policies

Repo to be provided by OASIS free of charge

Once this is an official working group in the EEA, members will have to sign entity (org contribution) and individual CLAs (community contribution)
Code of conduct

Linked to Baseline Code of Conduct. Reviewed pledge & other sections.
WG members to review and agree on the code of conduct linked in Governance Doc. Applies to other sections as well.

License:
Creative Commons License: CC0 - Overview provided by Andreas, key point: all contributors pledge they're not going to sue anyone for the code/IP, it's their IP, give up right to sue anyone that is using this IP within the established context of newly created IP. A commercial product could be built from

Apply to all code created by this group or specific repos? Any contributions/PRs fall under this license.

* Action item: Andreas to invite Chad from OASIS to the next meeting to give feedback on charter, governance & license (CC0)
No objections to this license model

The Working Group:

WG initial members - anyone that signs the charter is eligible to participate and pledges to contribute, bound by governance, etc. WG addition - same process as initial members i.e. signing charters. Non-members can lurk but only members that have signed can contribute & be vote-eligible. Added "and signed charter" to the WG section.

Decision-making process:

The section is lengthy & will require discussion. Skipped for the next session.

Contributors
No comments/changes

Maintainers

Contributions

Ratification

no comments/changes
--------------------------------------------------

## Updated Meeting Minutes: Meeting: Wed, 27th Oct, 2021, 7 am PT / 10 am ET / 16:00 BST

Changes: 
* Corrected Smart's Company Name to Golden Next Ventures
* Added Scribe
 
Scribe: Imran

Participants:
John Wolpert (Consensys), Samer Falah (J.P. Morgan), Imran Bashir (J.P. Morgan),  Andreas Freund (QLC Chain), Tas (Ethereum Foundation), Dan Shaw (Ethereum Foundation), Samrat Kishor (Golden Next Ventures), A.J. Warner (Arbitrum), Sebastian Stammler (Perun), San Safai (Perun), Bruno Maia (Cartesi), Steven Goldfeder (Arbitrum), Kartheek Solipuram (Ernst & Young), Julien Marchand (Consensys), Cody Burns (Accenture)

Introductions:
1. Tas: standards development, risks of the ecosystem, mitigate risks, L2 interoperability
2. Dan Shaw: year and a half, helping enterprises for Mainnet adoption, it turns out that enterprises need L2. focused on enterprise adoption, and expectations from enterprise
3. Sam: This is an interesting topic. We should focus on performance, scalability, and privacy with L2, looking for a Layer 2 solution. Focus on industry standards and ensure scalability. We can engage existing projects too.
4. John Wolpert: chair of baseline protocol / Oasis, baseline protocol is a new standard for coordination under zero-knowledge, have a clear framework to ensure following standards, shouldn’t require things like state machine to do coordination
5. Samrat Kishor: L2 is the next wave of growth, strategy background, baseline community, technical steering committee. regional head of EEA for India
6. Sebastian Stammer  (Perun): academic background, a group doing state channels, from the technical university of Darmstadt
7. AJ Warner: from Arbitrum :
8. Sasan Safai : from Perun,
9. Bruno Maia: from Cartesi, excited to see what this group will bring to standards and interoperability.
10. Steven Goldfeder - optimistic rollup, Arbitrum, CEO Arbitrum , working with different enterprise
11. Kartheek Soluipuram - at EY, solution architecture, baseline protocol. EY scalability and privacy, a family of layer 2 solutions, nightfall, keen on how to standardize
12. Julien Marchand - Consensys - zk-rollups , happy to be here,
13. Robert Drost, (16502792061 - ) R&D effort at Consensys mesh , L1 and L2 protocols, largely around state channels
14. Andreas Freund – active in the blockchain ecosystem, lead author of baseline protocols standards, was at Consensys.  Worked on ZK-rollup, apply learnings from baseline to large ecosystem for scalability, what looks sensible for the enterprise, very excited to be here.
 
Minutes:

Andreas: described meeting rules which were emailed earlier
- Have a transcriber on a rotating basis to take notes, post them in the channel, if the meeting is recorded, notes are automatically recorded
- Scribe required
- Meeting rules described
- Governance emailed
- Rules: everyone to be kind, for the betterment

Cody burns: introduction . . ., from Accenture

Andreas: question to the group, is everyone OK with meeting rules

Andreas: charter of the group. Two ways, quick review, share screen, Q&A session, specific questions, went through the charter. Available at google docs (insert link)

Tas: I like goals, but standards should be mentioned more explicitly.

Samrat: should we include ESG?

Andreas:  probably we can

Bruno: good idea,

Samrat: Blockchains consume a lot of  energy and generate carbon .. Standardize to switch to greener protocols

Sam: I will comment on ESG after but  scalability is the main focus and we should focus on privacy and performance as well … ESG is not our core focus at this point

Bruno: ESG could be the indirect result . . .  I believe that we should align early to  ESG

Samrat: we can add it later if clearer goal in future

Andreas: Leave ESG as an open topic

Tas: Added a suggestion, facilitating interoperability  among different L2s and L1s, and developing appropriate standards

Andreas: ESG should be incorporated now? Poll taken? Some +1s

Cody: intro: Accenture blockchain, metaverse, identity, happy to work on L2

Andreas: read Scope from the google docs document

Samrat: where is this initiative going, would L2 will evolve into Layer 3.

Andreas: go with the flow... We’ll see

Bruno: good question, the difference between L2 and L3, L2 on top of sidechain, it can be named as layer 3

Andreas: recited scope in the charter

John Wolpert: if this group works under EEA, then participants must be members of EEA, otherwise if OASIS then it can be open,  need some money from sponsors, if OASIS route: add some cash, as it’s a community project, if under EEA: grants can be given . .  Emphasized coordination issues when it comes to money and grants.

Andreas: agree with John, however, once something significant is produced. Then donation bucket can be passed around at that time

John: it's serious business .   . .

Andreas: True

John: I’ll rest here

Andreas: Segway, to WG chains

Andreas: proposal for WG chains

Andreas: park that item for next week,  discuss it at next week’s meeting, thank you for a great meeting

Meeting adjourned

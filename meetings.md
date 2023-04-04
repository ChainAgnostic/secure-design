# Secure Design WG - Community Call #2

[![hackmd-github-sync-badge](https://hackmd.io/_FozN2RTT56IjTIhch_V9A/badge)](https://hackmd.io/_FozN2RTT56IjTIhch_V9A)


April 4, 8am PST • [Register](https://lu.ma/iolqdlow)

## Preamble:

Our second ever Secure / Design Working Group community call!

Secure / Design WG aims to produce:
1. A set of **design principles** to guide teams
2. **Heuristics** to evaluate whether those principles are upheld, and 
3. A set of **UX patterns and best practices** to make upholding the principles a bit easier for the protocols, platforms and products that folks rely upon every day.

We're targeting design and product folks but all with a UX bent are welcome.

More background on us can be found here: 
+ [Twitter/@SecureDesignWG](https://twitter.com/securedesignwg)
+ [Secure Design: A draft of 7 principles](https://depatchedmode.mirror.xyz/4t_7BUzz5q3XlPtH7EgtGL61nh9U8plsfH23i7x5_lU)

## In attendance:

+ Ryan Betts (aka [depatchedmode](https://twitter.com/depatchedmode)), Head of Design @ [Fission](fission.codes), [Causal Islands](causalislands.com) & [Webnative](webnative.dev)
   + **I'm here because**: I want to ensure the products and systems I help to design leave folks feeling secure in every sense of the word. And I'm not smart enough to figure that out on my own.
   + **Most pressing secure design problem for me right now is:** Account creation and recovery.
+ Antonela, Lead Designer @ [MetaMask](metamask.io), [Tor Project](torproject.org)'s core contributor, [PITG](https://pitg.gitlab.io/about/) member, [0xche](0xche.org) peer
    + **I’m here** interested in end-users' impact on protocol design, with a focus on usable security.
    + **Most pressing secure design problem for me right now is:** abstracted accounts permissions, MetaMask confirmation screens, permissionless distribution.
+ Ira, Creative Director @ Protocol Labs, and @ DWeb / DWeb Camp (Join the camp! https://dwebcamp.org/what-to-expect/)
    + **I'm here because**: I don't know a lot about secure design, beyond the surface knowledge, I'm here to learn, and contribute as I can. 
    + **Most pressing secure design problem for me right now is:** curating headless brands (not the topic on this WG, though)
+ Jonny Howle, Free Agent (formerly: Co-founder, Head Product and Strategy @ Disco.xyz)
    + **I'm here because**: Identity (and its related concerns in security and privacy) is at the root of most of the problems with online life and our inability to create a decentralized and sufficiently ethical identity system stands between us and the feature we want to create.
    + **Most pressing secure design problem for me right now is**: Account management, recovery, and key delegation
+ Michelle Lai aka ML, Free Agent (Universal Privacy Alliance; formerly: head of BD at Anchorage, Zcash grants board); Twitter @michlai007
    + **I'm here because**: I want to be able to sleep and go on holidays instead of wondering when my next heart attack from crypto will happen
    + **Most pressing secure design problem for me right now is:** multiple-identity management for privacy and security
+ Howard Tam, Senior Protocol Engineer @ Lit Protocol
    + **I'm here because**: _not_ a designer, but interested in providing technical perspective on (end-user) design and feeding back any insights into protocol layer development.
    + **Most pressing secure design problem for me right now is:** secure web2 authentication schemes for onboarding to web3 platforms.
+ Salief Lewis: Core Contributor @ Public Assembly
    + I’m here because I want to help codify user aligned design practices.
    + Most pressing secure design problem for me right now is... hmm
+ Ligi: https://ligi.de
    + **I'm here because**: Learn from designers and represent CASA
    + **Most pressing secure design problem for me right now is:** how to make sure users know what they are signing
+ Meesh Lin [nf.td/meesh](https://nf.td/meesh): Head of Design @ [Commonwealth](https://www.commonwealth.im/), Design Lead @ [AIFS](https://mirror.xyz/0x7B7aE39D0ffA8d2a5128b251d332E9d0bF22cfa1/dUNKKmbIjhPdD0_UtIZIU-iUX_nR12hSwUm9cRf8-xw) ((Krause House Experiment))
    + **I'm here because**: ...
    + **Most pressing secure design problem for me right now is:** ...
+ Agost Biro: Founder @ [SealVault](https://sealvault.org/)
    + **I'm here because**: I'd like to make Web3 clients secure by default
    + **Most pressing secure design problem for me right now is:** How to simplify signature aproval (automate through [dapp isolation](https://ethereum-magicians.org/t/dapp-isolation-mechanisms/13611) / reduce to sign in or pay type of approval when it cannot be automated)

+ Tamara Adlin, Advisor & Consultant, adlininc.com
    + **I'm here because**: I've been in UX since the 90s and blockchain since 2017. I want to make UX more usable for Web 3 / product teams.
    + **Most pressing secure design problem for me right now is**: deigning UX itself--how it's communicated and modified for Web 3. Relevant article: [Why blockchain and Web3 user interfaces will suck for a while.](https://uxdesign.cc/why-blockchain-and-web-3-user-interfaces-will-suck-for-a-while-7575b7515757). More recent [Wallet UX teardown at EthDenver](https://www.youtube.com/watch?v=oTpuxYj8JWI).
    
+ Bruno Monts: Graphic Designer @ [Fission](fission.codes) & [Causal Islands](causalislands.com)
    + **I'm here because**: Coming from a design visual only, I am completely new to the subject and wanted to learn more a bit about Secure Design, especially to help me understand the aspects and problems that we find in the field.
    + **Most pressing secure design problem for me right now is:** Trying to find out and hear from you!

+ COPY ME: Name, Profession & Links
    + **I'm here because**: ...
    + **Most pressing secure design problem for me right now is:** ...

## Agenda:

### (10 min) Hello & Intros

Please make sure you've added your details to "In Attendance" section.
Ryan'll give a quick pre-amble on why the group was started.

- [antonela] Want to focus on cross-disciplinary approaches to protocol design and development. Need help w/ permissions through abstraction; make sure that people don't inadvertently lose ownership. And don't want to take ownership away from people!
- [meesh] Consumer security at the product level needs to be untangled. Current offerings are scattered and need to be features pulled together into one thing. Specific problem: permissionless-ness vs respecting the boundaries of people's identities
- [ml] Identity is the way to manage privacy and safety. Having a lot of accounts and managing between them is not easy; leads to co-mingling, leaking connections. Separation of identity concerns?
- [johnny] Has been working on Account Abstraction-like things for a while via things like DIDs. Narrow slice right now: delegation of authority.
- [agost] Working on seal vault. Signature approval: how can we automate it? Or at least reduce it.
- [howard] Working on a transaction signing protocol/network to preserve security of wallets. How do we onboard folks from web2 into web3? Secure authentication flows via biometrcis.
- [tamara] We need to focus on the specific problems but also communicating the value of UX and the importance of involving it early.
- [salief] How are tools like account abstraction able to be synthesized into good practices that normal people recognize as trustable?

### (20 min) Principles & purpose review

Open discussion about the 7 draft principles and the proposed working group outcomes.

- [tamara] we need documents that speak to various different groups including engineers: 
   - EG “how to sell UX effort into your tech team"
   - “Patterns you can use in your wallet"
   - “Landmines to avoid."
- [meesh] need resources that can help us feel confident in speaking to other strong minded folks on our team
- [ml] people who built chainalysis think of it simply as a tool. might be impossible to change their minds.
- [meesh] how do you differentiate from info synthesis tools and give users back a bit of agency
- [antonela] simply secure and decentpatterns is a great place to look. how do we work on proposals from CASA? We could have more impact if we get involved in active PRs.
- [ml] if we're not careful we might make a web3 that's worse than web2

### (20 min) Choose an async home

Let's choose a public place to host the ongoing async discussion. Leading proposal right now is to roll it into [CASA (Chain Agnostic Standards Alliance)](chainagnostic.org):

- unanimous agreement. Ryan will coordinate with Ligi/Juan

#### Potential CASA Pros:

- **Likeminded folks:** A lot of wallet client teams (Brave, Metamask, etc) and protocols such as Wallet Connect are active there, which means it'd be a good point of leverage for affecting change at those UX touchpoints.
- **UX is already a key concern:** though it is couched from an engineering / protocol perspective, a lot of what CASA is tackling are building blocks to improve the user experience in the ecosystem.
- **Lots of momentum:** there's been significant growth in CASA activity over the past year
- **Visibility / working in the open:** the whole CASA org infra is focused on working out in the open, and as a result it's getting a lot of visibility
- **Ability to impact emergent dev standards:** lots of new dev patterns are starting or at least routing through CASA, so we'd be in a great position to help build out prototypes, etc.

#### Potential CASA Cons:
- **Tying ourselves to blockchains:** The scope of this working group to be broader than just the commonly understood "web3" stack. Being in CASA might turn off anybody who is instinctively anti-web3. That said:
	- despite CASA having "chain" in the name, most members truly are "chain agnostic" in that a good deal of the work they do resides offchain and bumps up against DIDs, VCs, and a whole lot of "web2" tech and standards processes.
- **Dev heavy culture:** the tooling at present is all Github, markdown, etc. Don't think there'd be resistance to us adding a few more tools to the mix, as long as they don't duplicate. And Github is a lot friendlier to non-devs these days. But, it's something to consider.
- **IPR Concerns**: 
   - [@bumblefudge] "My only warning is to check with the other participants what level of IPR they're comfortable with-- sometimes people here the word "standards" and assume it's recorded, patent-waived, etc.  If people work for the kind of companies that, ahem, "close-source" their design work, we'd have to bump up the IPR policy of that WG, which is currently in #yolo mode because protocol design IP isn't generally as sensitive as UX"


## Action items / Tabled for async:

- Setup Github Discussions
    - Let's gather heuristics resources 
    - Let's start evaluating patterns
    - Let's get involved in existing CAIPs / PRs seeing how best to support the UX concern side of things
- Tweet announcement from SecureDesignWG twitter about forum 
- Organize next call - what other timezones to accomodate and how best to do it?

## Links:

https://depatchedmode.mirror.xyz/4t_7BUzz5q3XlPtH7EgtGL61nh9U8plsfH23i7x5_lU
https://decentpatterns.com/
https://www.ietf.org/archive/id/draft-iab-for-the-users-03.html
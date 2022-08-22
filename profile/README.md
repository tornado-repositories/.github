## Tornado-Repositories: an archival fork of the Tornado Cash source code

These repositories contain an archival fork of the Tornado Cash and Tornado Cash Nova source code base. 
They are maintained on Github by [Matthew D. Green](https://isi.jhu.edu/~mgreen/) of Johns Hopkins for teaching and research purposes.

### What is Tornado Cash and what is this repository?

Tornado Cash and Tornado Nova are open-source coin mixing tools that were developed by an independent team of software
developers and deployed onto Ethereum and several other blockchains. On August 8, 2022 the Office of Foreign
Assets Control (OFAC), a division of the US Treasury, [declared "Tornado Cash" and "Tornado Cash Nova" to be
Specially Designated Nationals (SDNs)](https://home.treasury.gov/news/press-releases/jy0916): the result was to effectively sanction the Tornado Cash organization and its deployment on Ethereum.

This move to sanction Tornado Cash represents the first instance in which the US government has 
applied economic sanctions to an open source software project. As a result of this announcement, several cryptocurrency
exchanges have banned users who interact with the Tornado Cash smart contract address on Ethereum. 
At the same time, Github shut down the user accounts of all known Tornado Cash developers, and removed the source code repositories owned by Tornado's Github organization. 

While Github succeeded in removing the original copies of all Tornado source code repositories, several recent "forks" of the code can be found on Github. These were recently collected together by contributors to the [tornadocash-community](https://github.com/tornadocash-community) organization. This current repository is simply a second fork of the repositories collected by that organization.  

### Why preserve the Tornado Cash source code?

In my role as a researcher and instructor at Johns Hopkins, I have made extensive use of the Tornado Cash and Tornado Nova source code 
to teach concepts related to cryptocurrency privacy and zero-knowledge technology. The loss or decreased availability of this 
source code will be harmful to the scientific and technical communities.

Moreover, I am uncomfortable with the implications of the Github decision. Github is a private company, and of course it can suspend 
users for any perceived violation of its Terms of Service. At the same time, it is hard to believe that Github's decision was unrelated to the government's action. In my opinion it is much more likely that Github censored the 
Tornado Cash code repositories as part of a risk-mitigation procedure they engaged in *as a direct result of the OFAC order*. Moreover, I believe that this removal of protected speech was a predictable consequence of OFAC's action.

Given that much of the Internet publishing infrastructure is operated by private firms, the example of Tornado Cash forces us to confront the the prospect that OFAC may have the power to effectively ban source code distribution and scientific speech. This would not be accomplished through explicit action, but rather by imposing severe perceived sanctions risk to private companies and US citizens that host the speech. This creates a "chilling effect" on speech, and allows the US government to determine which citizens and organizations have the right to publish their source code and scientific artifacts. 

The creation of the current archival repository organization does not solve this issue, nor will it repair the damage that has already been done. Instead, this repository exists to make clear to Treasury and Github that *this code has value*, and its removal has consequences to researchers and students in the United States. Moreover, it exists to test the proposition that code removal should ever been an appropriate response to sanctions orders, no matter how justifiable the order may seem. I have discussed my concerns with the [Electronic Frontier Foundation](https://www.eff.org/) and they have agreed to represent me as a client.  See their blog post here. 

### But Git is decentralized (and IPFS exists) so what's the big deal?

Git is a decentralized version control system. Hence other copies of the Tornado Cash code certainly exist 
on other machines and at other locations (in fact, go ahead and make a clone right now!) You should be able to verify that these 
are authentic by comparing hashes to a main trusted repository, like the one that used to be hosted here on Github. (Since that no longer exists, you can use the forks in this repository. Alternatively here's a [Wayback Machine copy](https://web.archive.org/web/20220808144505/https://github.com/tornadocash) that still sort of works.)

Hence  Github's removal of the Tornado Cash code repositories and developer accounts is not a total ban on the source code. It does have two critical effects: first, it halts the ongoing development of this source code *even as a pure software 
development and research project.* Second, it makes discovery of the code much more difficult. (It is more analogous to removing a book from major commercial bookstores, while still allowing users to exchange PDF files on USB sticks.) At present a non-expert user searching for the Tornado Cash code on Google will have a difficult time. Try it yourself.

If you want a copy of the code on a more durable decentralized medium, there are some copied of (limited) repositories on IPFS. I certainly don't warranty these (or any of this code), and you should carefully check hashes against the repositories on Github and in the Wayback Machine just in case:

* Tornado Nova: `ipfs://bafybeicu2anhh7cxbeeakzqjfy3pisok2nakyiemm3jxd66ng35ib6y5ri`
* Tornado Cash Classic: `ipfs://bafybeicu2anhh7cxbeeakzqjfy3pisok2nakyiemm3jxd66ng35ib6y5ri`

You can also find recent clones of the Tornado Cash repositories on [Software Heritage](https://archive.softwareheritage.org/browse/search/?q=tornadocash&with_visit=true&with_content=true).

### Will you take PRs for Tornado Cash, or host other projects?

These repositories are intended as an archival project only. They are yours to clone and fork. They will not be actively developed,
which means that over time they will gradually become obsolete. In the future this organization may evolve to host archival forks of other non-TC privacy projects, should I determine that they are also at risk of sanctions-based code  
removal.

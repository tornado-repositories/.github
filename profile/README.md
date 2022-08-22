## Welcome to Tornado-Repositories: an archival fork of the Tornado Cash source code

These repositories contain an archival fork of the Tornado Cash and Tornado Cash Nova source code base. 
They are maintained on Github by [Matthew D. Green](https://isi.jhu.edu/~mgreen/) of Johns Hopkins for teaching and research purposes.

### What is Tornado Cash and what is this repository?

Tornado Cash (and Tornado Nova) are open-source coin mixing tools that were developed by an independent team of software
developers and deployed onto Ethereum and several other blockchains. On August 8, 2022 the Office of Foreign
Assets Control (OFAC), a division of the US Treasury, [declared "Tornado Cash" and "Tornado Cash Nova" to be
Specially Designated Nationals (SDNs)](https://home.treasury.gov/news/press-releases/jy0916): the result was to effectively sanction the Tornado Cash organization and its deployment on Ethereum.

This move to sanction Tornado Cash represents the first example of which Treasury
applying economic sanctions to an open source software project. As a result of this announcement, several cryptocurrency
exchanges have banned users who interact with the Tornado Cash smart contract address on Ethereum. 
At the same time, Github shut down the user accounts of all known Tornado Cash developers, and removed the source code repositories owned by Tornado's Github organization. 

While Github succeeded in removing the original copies of all Tornado source code repositories, several recent "forks" of the code can be found on Github. These were recently collected together by contributors to the [tornadocash-community](https://github.com/tornadocash-community) organization. This current repository is simply a second fork of the repositories collected by that organization.  

### Why preserve the Tornado Cash source code?

In my role as a researcher and instructor at Johns Hopkins, I have made extensive use of the Tornado Cash and Tornado Nova source code 
to teach concepts related to cryptocurrency privacy and zero-knowledge technology. The loss or decreased availability of this 
source code will be harmful to the scientific and technical communities.

Moreover, I am uncomfortable with the implications of the Github decision. Github is a private company, and of course it can suspend 
users for any perceived violation of its Terms of Service. However: it defies credibility to believe that Github's decision was made independently from the Treasury order. In my opinion it is much more likely that Github censored the 
Tornado Cash code repositories as the result of a risk-mitigation exercise *following the receipt of the OFAC order*. Moreover, I believe that the removal of protected speech was an entirely predictable consequence when OFAC issued its order.

Given that much of the Internet publishing infrastructure is operated by private firms, the example of Tornado Cash forces us to confront the the prospect that OFAC may hae the power to effectively ban source code distribution and scientific speech. This would not be accomplished through explicit action, but rather by imposing severe perceived sanctions risk to private companies and US citizens that host the speech. This creates a "chilling effect" on speech, and allows the US government to determine which citizens and organizations have the right to publish their source code and scientific artifacts. 

The creation of the current archival repository organization does not solve this issue, nor will it repair the damage that has already been done. Instead, this repository exists to make clear to Treasury and Github that *this code has value*, and its removal has consequences to researchers and students in the United States. Moreover, it exists to test the proposition that code removal should ever been an appropriate response to sanctions orders, no matter how justifiable the order may seem. I have discussed my concerns with the [Electronic Frontier Foundation](https://www.eff.org/) and they have agreed to represent me as a client, should legal representation become necessary.  See their blog post here. 

### Will you take PRs for Tornado Cash, or host other projects?

These repositories are intended as an archival project only. They are yours to clone and fork. They will not be actively developed,
which means that over time they will gradually become obsolete. In the future this organization may evolve to host archival forks of other non-TC privacy projects, should I determine that they are also at risk of sanctions-based code  
removal.

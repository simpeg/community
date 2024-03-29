# SimPEG Project Governance

The purpose of this document is to formalize the governance process used in both ordinary and extraordinary situations. It is also meant to clarify how decisions are made. 

## The Project

The SimPEG Project (The Project) is a community-driven project that develops and maintains open-source software for simulations and inversions of geophysical data. Software repositories include those in the [SimPEG github organization](https://github.com/simpeg). They are developed openly and hosted on public repositories. Software developed by The Project is released under the MIT (or similar) open source license. 

The Project is developed by a team of distributed developers, called Contributors. Contributors are individuals who have contributed code, documentation, designs, examples, or other work to The Project, including answering questions and participating on discussion forums. Anyone can be a Contributor. Contributors can be affiliated with any legal entity or none. Contributors participate in the project by submitting, reviewing, and discussing GitHub Pull Requests and Issues and participating in open and public Project discussions on GitHub, discussion forums, and other channels. 

The Project Community consists of all Contributors and Users of The Project. Contributors work on behalf of and are responsible to the larger Project Community and we strive to keep the barrier between Contributors and Users as low as possible.

The Project is not a legal entity, nor does it currently have any formal relationships with legal entities.

## Governance 

This section describes the governance and leadership model of The Project.

The Project roles are:
- Founders
- BDFL
- Maintainers
- Owners
- Community

### Founders 
The project founders are the people who started SimPEG. They hold no special authority in The Project, other than if a successor to the BDFL is not able to be appointed. They are consulted on decisions concerning project leadership, governance, and vision. The project founders are:
- Rowan Cockett ([@rowanc1](https://github.com/rowanc1))
- Lindsey Heagy ([@lheagy](https://github.com/lheagy))
- Seogi Kang ([@sgkang](https://github.com/sgkang))

### Benevolent Dictator for Life (BDFL)

This person is responsible for planning, organization, and direction of the organization's operations and programs. There is an expectation that this person invests efforts in community & organizational strategy as well as in working with the community to develop and act on the long-term vision of the project.

The role of a BDFL (Benevolent Dictator for Life) is common in other open-source projects. As Dictator, they, have the authority to make all final decisions for The Project. As Benevolent, they, in practice, chooses to defer that authority to the consensus of the community discussion channels (see below). It is expected, and in the past has been the case, that the BDFL will only rarely assert their final authority. Because rarely used, we refer to the BDFL’s final authority as a “special” or “overriding” vote. When it does occur, the BDFL override typically happens in situations where there is a deadlock in building concensus among the Community. The Project encourages others to fork the project if they disagree with the overall direction the BDFL is taking. The BDFL may delegate their authority on a particular decision or set of decisions to any other Contributor at their discretion.

The BDFL can appoint their successor, but it is expected that the Community (through the community discussion channels) would be consulted on this decision. If the BDFL is unable to appoint a successor, the Founding Team will make this decision - preferably by consensus, but if needed, by a majority vote.

Note that the BDFL can step down at any time, and acting in good faith, will also listen to serious calls to do so. 

The current BDFL is 
- Lindsey Heagy ([@lheagy](https://github.com/lheagy))


### Maintainers

Maintainers help facilitate pull request reviews, triaging of issues, and software releases. Note that this doesn’t mean that they have to do all of the Pull Request Reviews and Releases; they can delegate or request involvement from other Project Contributors. Maintainers are included in the [Admin Team](https://github.com/orgs/simpeg/teams/simpeg-admins) on GitHub. They have administrative rights on all repositories in the SimPEG GitHub organization. They also have admin rights on PyPI and Conda Forge. 

Maintainers are appointed by the BDFL, in consultation with current maintainers and project Founders.

These people are “Maintainers” in the SimPEG GitHub organization: 
- Joseph Capriotti ([@jcapriot](https://github.com/jcapriot))
- Santiago Soler ([@santisoler](https://github.com/santisoler))

### Owners
Owners have the permissions as outlined in the [GitHub docs](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization#organization-owners). To ensure continuity of ownership, as a project, we will always have a minimum of 2 owners, with one being the BDFL. 

These people are the “Owners” of the SimPEG GitHub organization: 
- Rowan Cockett ([@rowanc1](https://github.com/rowanc1))
- Lindsey Heagy ([@lheagy](https://github.com/lheagy))

### Community Discussion Channels 

Conversation and consensus building are an important part of SimPEG governance, and thus here, we specify the main communication channels used by The Project. 
- The [SimPEG Mattermost Team][mattermost] is the main place for day-to-day communication and chat. This is where meeting links are circulated, and development discussions prompted.
- Meetings are held weekly. The video-conferencing link is circulated in the #meetings channel on Mattermost prior to the meeting. All meetings are recorded and available on [youtube](https://www.youtube.com/playlist?list=PLd9tNwsUm9jOagLQEnxdeIPE4L4bx5Ujg)
- [Discourse](https://simpeg.discourse.group/) is used as a forum for asking and answering questions among the community. 

### Institutional Partners

Multiple stakeholders from academia, industry, and non-profit sectors participate in The Project as contributors and community members. No outside institution, individual, or legal entity has the ability to own, control, usurp, or influence the project other than by participating in The Project as Contributors. However, because institutions can be an important funding mechanism for The Project and people who contribute to it, it is important to formally acknowledge institutional participation in the project. These are Institutional Partners.

An Institutional Contributor is any individual Project Contributor who contributes to the project as part of their official duties at an Institutional. An Institutional Partner is any recognized legal entity in any country that employs at least 1 Institutional Contributor. Institutional Partners can be for-profit or non-profit entities.

Institutions become eligible to become an Institutional Partner by employing individuals who actively contribute to The Project as part of their official duties. To state this another way, the only way for a Partner to influence the project is by actively contributing to the open development of The Project, in equal terms to any other member of the community of Contributors. Merely using Project Software in institutional context does not allow an entity to become an Institutional Partner. Financial gifts do not enable an entity to become an Institutional Partner. However, they can be acknowledged on The Project website. Once an institution becomes eligible for Institutional Partnership, any Contributor can nominate them; nominations are approved by the BDFL.

If, at some point, an existing Institutional Partner stops having any contributing employees, then a one year grace period commences. If, at the end of this one-year period, they continue not to have any contributing employees, then their Institutional Partnership will lapse, and resuming it will require going through the normal process for new Partnerships.

An Institutional Partner is free to pursue funding for their work on The Project through any legal means. This could involve a non-profit organization raising money from private foundations and donors or a for-profit company building proprietary products and services that leverage Project Software and Services. Funding acquired by Institutional Partners to work on The Project is called Institutional Funding. However, no funding obtained by an Institutional Partner can override the BDFL. If a Partner has funding to do SimPEG work and the Community and BDFL decides to not pursue that work as a project, the Partner is free to pursue it on their own. However, in this situation, that part of the Partner’s work will not be under the SimPEG umbrella and cannot use The Project trademarks in any way that suggests a formal relationship.

Institutional Partner benefits are:
- acknowledgement on the SimPEG website and in talks
- ability to acknowledge their own funding sources on the SimPEG website and in talks
- ability to influence the project through the participation
- invitation of the Council Members to SimPEG Developer Meetings

A list of current Institutional Partners is maintained at TODO.

### Changes to Governance

The authority to change the governance model is held by the BDFL, but any changes to the governance model will be done in a consensus building process between the BDFL, Maintainers and the Community. 

Suggestions to governance processes can always be raised in the interm at weekly meetings, in the `~governance` channel on [Mattermost][mattermost], or directly to the BDFL. 

## Document History

- 2024 Mar 20: update governance to retire "Director" titles in favour of Maintainers (replacing the "Director of Operations") and a BDFL (replacing the "Managing Director"). This brings SimPEG more in line with BDFL language used by other projects. Changes were made in https://github.com/simpeg/community/pull/18.
- 2021 Apr 5: SimPEG governance suggested next steps [doc](https://docs.google.com/document/d/1Y8FZjDGZFC0dJveh-JNRuCXkOrtbrSFpZ55xi5VXDQ4/edit#), [video recording](https://youtu.be/EeoqqxmBGf0)
- 2020 Dec 10: Governance sketch [doc](https://docs.google.com/document/d/1O9jiYvKClRvV0tcrQOA5PgEoTZ4e-gvAut2sgYM_-ho/edit#), [video recording](https://youtu.be/oLUHdmpbHNI)

## Acknowledgement

Substantial portions of this document were adapted from the [Jupyter/IPython project governance document](https://github.com/jupyter/governance/blob/master/governance.md), the [NumPy governance document](https://github.com/numpy/numpy/blob/master/doc/source/dev/governance/governance.rst) and the [SciPy governance document](https://docs.scipy.org/doc/scipy/reference/dev/governance/governance.html). 

## License 

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to the SimPEG project governance document, as per the [CC-0 public domain dedication / license](https://creativecommons.org/publicdomain/zero/1.0/).


[mattermost]: https://mattermost.softwareunderground.org/simpeg

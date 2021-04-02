(general:community)=
# Community

It is important for software projects to have active user/developer communities around them.
These guidelines focus on enabling software project communities.

(general:community:must)=
## Must items

These are strongly suggested

(general:community:must:1)=
### The source code for the software **must** be hosted on a publicly accessible resource

The source code for the software **must** be hosted on a publicly accessible resource, and should be freely downloadable.

Keeping in line with the Free/Open Source Software (FOSS) and Open Science philosophies, the source code of the software must be openly available.
(See also: {ref}`Licensing <general:licensing>`)

Services that provide free version controlled hosting for FOSS projects are (order does not imply preference):

- [GitHub](https://github.org)
- [GitLab](https://gitlab.com)
- [Bitbucket](https://bitbucket.org)
- [SourceForge](https://sourceforge.net)

One may also use a self-hosted service.

*Requiring registration/e-mail submission for the download of source code is discouraged.*

(general:community:must:2)=
### The software **must** have support channels

Mailing lists, forums, chat channels help users engage with the developers to request assistance, make suggestions, report bugs, or just provide feedback.
Platforms where users may ask "drive by" questions are preferred, since these allow users to quickly join, have a conversation, and then leave the platform.
Some examples of FOSS chat platforms are:

- [Gitter](https://gitter.im) (FOSS, free of cost)
- [Element.io(formerly Matrix)](https://element.io/) (FOSS, free of cost, bridged to Gitter/IRC)
- [IRC via Freenode](https://freenode.net/) (FOSS, free of cost, can be bridged to Matrix/Gitter)
- [Discord](https://discord.com/) (not FOSS, free of cost to use with paid tiers)

While [Slack](https://slack.com) is frequently used by small teams nowadays, it is not recommended for public end user troubleshooting
It:

- does not scale to larger numbers of users
- requires invitations to join
- is not FOSS,

A FOSS alternative is [Mattermost](https://mattermost.com//) which can either be self-hosted and also provides paid hosting.

Forums/mailing list platforms:

- [Discourse](https://discourse.org) (can be self hosted, paid hosting available)
- [GNU Mailman](http://www.list.org/) (FOSS, commonly used, but generally requires hosting)
- [Google Groups](https://groups.google.com/) (free of cost, but not FOSS)

(general:community:must:3)=
### The software **must** have user documentation

User documentation can either be hosted on the web space itself, or using other commonly used resources depending on where the source code is hosted:

- [Read the Docs](https://readthedocs.org/)
- [GitHub pages](https://pages.github.com/)
- [GitLab pages](https://about.gitlab.com/stages-devops-lifecycle/pages/)


- The software **must** have developer documentation.

To ensure the simplest contribution path, developer documentation is necessary.
This includes:

- Contribution guidelines,
- Code guidelines,
- Pull request requirements,

See also: {ref}`Documentation <general:documentation>`.

(general:community:should)=
## Should items

(general:community:should:1)=
### The software **should** have a web-page

The software **should** have a web-page/web site that is easily searchable using common web search tools.

This ensures that the software is easy to find/access.
A unique name also provides more visibility on search engines.

(general:community:should:2)=
### The software **should** include [Code of Conduct guidelines](https://www.cnsorg.org/code-of-conduct)


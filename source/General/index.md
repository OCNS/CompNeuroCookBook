# General guidelines

These are general guidelines about the software, their licensing, management, and their communities.
The review template can be found on the next page.

## Community


- The software **should** have a web-page/web site that is easily searchable using common web search tools.

  This ensures that the software is easy to find/access.
  A unique name also provides more visibility on search engines.

- The software **should** include [Code of Conduct guidelines](https://www.cnsorg.org/code-of-conduct).

- The source code for the software **must** be hosted on a publicly accessible resource, and should be freely downloadable.

  Keeping in line with the Free/Open Source Software (FOSS) and Open Science philosophies, the source code of the software must be openly available.
  (See section on Licensing below)
  Services that provide free version controlled hosting for FOSS projects are (order does not imply preference):

  - [GitHub](https://github.org),
  - [GitLab](https://gitlab.com),
  - [Bitbucket](https://bitbucket.org),
  - [SourceForge](https://sourceforge.net).

  Self hosted services are also acceptable.
  *Requiring registration/e-mail submission for the download of source code is discouraged.*

- The software **must** have user documentation.

  User documentation can either be hosted on the web space itself, or using other commonly used resources depending on where the source code is hosted:

  - [Read the Docs](https://readthedocs.org/),
  - [GitHub pages](https://pages.github.com/),
  - [GitLab pages](https://about.gitlab.com/stages-devops-lifecycle/pages/).

  User documentation should include:

  - steps on installing the software
  - clear lists of dependencies, both build and runtime with their required versions.

- The software **must** have support channels.

  Mailing lists, forums, chat channels help users engage with the developers to request assistance, make suggestions, report bugs, or just provide feedback.
  Platforms where users may ask "drive by" questions are preferred, since these allow users to quickly join, have a conversation, and then leave the platform.
  Some examples of FOSS chat platforms are:

  - [Gitter](https://gitter.im), (FOSS, free of cost)
  - [Element.io(formerly Matrix)](https://element.io/), (FOSS, free of cost)
  - [IRC via Freenode](https://freenode.net/), (FOSS, free of cost, can be bridged to Matrix/Gitter)
  - [Discord](https://discord.com/), (not FOSS, free of cost to use with paid tiers)

  While [Slack](https://slack.com) is a mainstream collaborative chat platform used by small teams nowadays, it is not recommended for public end user troubleshooting:

  - does not scale to larger numbers of users,
  - requires an invitation to join (or setting up an invitation management website),
  - is not FOSS,

  A FOSS alternative is [Mattermost](https://mattermost.com//) which is FOSS, can be self-hosted and also provides paid hosting.

  Forums/mailing list platforms:

  - [Discourse](https://discourse.org), (can be self hosted, paid hosting available)
  - [GNU Mailman](http://www.list.org/), (FOSS, commonly used, but generally requires hosting)
  - [Google Groups](https://groups.google.com/), (free of cost, but not FOSS)

- The software **must** have developer documentation.

  To ensure the simplest contribution path, developer documentation is necessary.
  This includes:

  - Contribution guidelines,
  - Code guidelines,
  - Pull request requirements,


## Licensing

- The software **must** be licensed under a Free/Open Source Software (FOSS) license.

  A FOSS license is necessary to permit unencumbered usage, development, study, and dissemination of software and tools.
  References:

  - [Free Software Foundation license list](https://www.gnu.org/licenses/license-list.html),
  - [Debian license list](https://www.debian.org/legal/licenses/).
  - [Fedora Project license list](https://fedoraproject.org/wiki/Licensing:Main?rd=Licensing#Good_Licenses),
  - [TLDR legal: software license in plain English](https://tldrlegal.com/).
  - [licensecheck: simple licensechecker for source files](https://metacpan.org/pod/distribution/App-Licensecheck/bin/licensecheck).

- The software **should** include an up to date copy of the license.

  While not all licenses require the license text to be included in the software, quite a few of them do.
  It is therefore suggested to include a copy of the license text in the released artefacts.

# Governance

The Selenium Project wants as much as possible to operate using procedures that
are fair, open, inviting, and ultimately good for the community. For that reason,
we find it valuable to codify some of the ways that the Project goes about its
day-to-day business. We want to make sure that no matter who you are, you have
the opportunity to contribute to Selenium. We want to make sure that no
corporation can exert undue influence on the community or hold the Project
hostage. And likewise, we want to make sure that corporations which benefit
from Selenium are also incentivized to give back. This document describes how
various types of contributors work within the Selenium project.

## Roles and Responsibilities

### Users

Users are community members who have a need for the project. Anyone can be a
User; there are no special requirements. Common User contributions include:

* Evangelizing the project (e.g., display a link on a website and raise
awareness through word-of-mouth)
* Informing strengths and weaknesses from a new user perspective 
(e.g., raising a bug as a GitHub issue, proposing a new feature)
* Providing moral support (a "thank you" goes a long way).

Users who continue to engage with the project and its community will often
become more and more involved. Such Users may find themselves becoming
Contributors, as described in the next section.

### Contributors

Contributors are community members who contribute in concrete ways to the project,
most often in the form of code and/or documentation. Anyone can become a Contributor,
and contributions can take many forms, e.g.:
* Help other users through any of the [communication channels](#communication-channels)
made for that purpose.
* Triage GitHub issues.
* Organize Selenium meetups.
* Organize and collaborate in Selenium Conferences.

There is no expectation of commitment to the project, no specific skill requirements,
and no selection process.

Some Contributors might have some basic privileges to the GitHub repos, based on
their type of contribution (e.g., close an issue after triaging it).

Contributors have read-only access to source code and submit changes via pull
requests. Contributor pull requests have their contribution reviewed and merged
by a TLC member or a Committer. TLC members and Committers work with Contributors
to review their code and prepare it for merging.

As Contributors gain experience and familiarity with the project, their profile within,
and commitment to, the community will increase. At some stage, they may find themselves
being nominated for the Committer role by an existing Committer or TLC member.

### Project Committers

Committers are community members who have shown that they are committed to the
continued development of the project through ongoing engagement with the community.
Committers are given push access to the project's GitHub repos where they
contribute to.

Committers:

* Should bring their proposals for large changes to the project's code first to
a GitHub issue, and all relevant committers should be pinged so they can weigh
in on the discussion if desired. 
* Debates between committers about whether code should be merged should happen
in GitHub pull requests to keep the project decision history.
* In general any committer can review and merge a pull request. Committers
should only merge code they are qualified to review, which might entail pinging
another committer who has greater ownership over a specific code area.
* May label and close issues.

To become a Committer:

* One must have shown a willingness and ability to participate in the project as
a team player.
* Committers are expected to be respectful of every community member and to work
collaboratively in the spirit of inclusion.
* Have submitted a minimum of 10 qualifying pull requests. Where significant
technical weight is present and requires little effort to accept because it is
well documented and tested.

New Committers can be nominated by any existing Committer or TLC member. Once
they have been nominated, there will be a vote by the TLC members.

It is important to recognize that having the Committer role is a privilege, not
a right. That privilege must be earned and once earned, it can be removed by
the TLC members by a standard TLC motion. However, under normal circumstances
the Committer role will exist for as long as the Committer wishes to continue
engaging with the project.

A Committer who shows an above-average level of contribution to the project,
particularly with respect to its strategic direction and long-term health, may 
be nominated to become a TLC member, described below.

#### Process for Adding Committers

1. Add the GitHub user to relevant GitHub team:
    * `selenium-committers` for the main Selenium repo
    * `selenium-ide` for the Selenium IDE repo
    * `documentation` for the website and documentation repo
    * `docker-owners` for the Docker-Selenium repo
1. Invite to Slack team chat room (`selenium-committers`)
1. Tweet congratulations to the new committer from the SeleniumHQ Twitter account


### Technical Leadership Committee (TLC)

The technical decisions and roadmap of the Selenium project are governed by
a Technical Leadership Committee (TLC) which is responsible for a high-level
technical guidance of the project.

The TLC has final authority over this project including:

* Technical direction
* Repository hosting
* Contribution policy (shared with the PLC)

TSC seats are not time-limited. There is no fixed size of the TLC. The TLC
should be of such a size as to ensure adequate coverage of important areas
of expertise balanced with the ability to make decisions efficiently.

The TLC may add additional members to the TLC by a standard TLC motion.

A TLC member may be removed from the TLC by voluntary resignation, or by a stand
ard TLC motion.

No more than 1/3 of the TLC members may be affiliated with the same employer.
If removal or resignation of a TLC member, or a change of employment by a TLC
member, creates a situation where more than 1/3 of the TLC membership shares an
employer, then the situation must be immediately remedied by the resignation or
removal of one or more TLC members affiliated with the over-represented employer(s).

TLC members have additional responsibilities over and above those of a Committer.
These responsibilities ensure the project has a technical viability and sustainability
in a smooth way. TLC members are expected to review code contributions, approve
changes to this document, and manage the copyrights within the project outputs.

TLC members fulfill all requirements of Committers, and also:

* May merge external pull requests for accepted issues upon reviewing and approving
the changes.
* Push code directly to the repos or, when necessary, create and merge their own pull
requests once they have collected the feedback they deem necessary.
* Discuss once a month the technical status and project roadmap.

To become a TLC member:

* Work in a helpful and collaborative way with the community.
* Have given good feedback on others' submissions and displayed an overall understanding
of the code quality standards for the project.
* Commit to being a part of the community for the long-term.
* Have submitted a minimum of 20 qualifying pull requests.

A Committer is invited to become a TLC member by existing TLC members. A nomination
will result in discussion and then a decision by the TLC.

#### Process for Adding TLC Members

1. Add the GitHub user to the `Selenium TLC` team
1. Set the GitHub user to have the "Owner" role for the SeleniumHQ organization
1. Invite to the Slack TLC chat room (`selenium-tlc`)
1. Add the TLC member to the different package distribution organizations
    * NPM
    * SonarType (maven)
    * pypi.org
    * rubygems.org
    * nuget.org
1. Tweet congratulations to the new TLC member from the SeleniumHQ Twitter account

### Project Leadership Committee (PLC)

The overall continuity and future of the project is overseen by the Project
Leadership Committee (PLC), which acts as a bridge between the Selenium project
and the Software Freedom Conservancy (SFC).

Since there are many different facets to the Selenium project, the PLC wants to
reflect more than just people who sling code about. The PLC gets involved in
different ways, such as whenever the project spends money, enters legal agreements,
or has to deal with lawyers. Typically the PLC will discuss the topic with the rest
of the community, and then a voting session will take place.

PLC seats are not time-limited. Only one person may be affiliated with the any
given employer can be on the PLC at a time. The PLC member count should be always
odd so that no votes are ever tied, an ideal minimum number is 5. PLC members
should also be active members of the community.

To become a PLC member:

* An existing PLC member steps down and suggests someone (or some people) to replace them.
* Be a committer or a contributor.
* Commit to being a part of the community for the long-term.
* The existing PLC consults with the TLC and the active Committers, who vote on whether or
not to add those people.
    * No-one is ever suggested publicly without first discussing the idea with 
      them first (to make sure that they are okay with it).


The PLC has final authority over this project including:

* Project governance and process (including this policy).
* Contribution policy (shared with the PLC).
* Budget and legal related issues.

The PLC also should discuss once a month the overall status of the project and any pending or
upcoming topics.

A PLC member may be removed from the PLC by voluntary resignation, or by a stand
ard TSC motion.

#### Process for Adding PLC Members

1. Invite to the Slack PLC chat room (`selenium-plc`)
1. Tweet congratulations to the new PLC member from the SeleniumHQ Twitter account
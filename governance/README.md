# Node.js Community Committee (CommComm) Governance

The Node.js Community Committee initiatives are governed by its Collaborators,
including the Community Committee (CommComm) which is responsible for the high-level guidance of the
initiatives.

<!-- TOC -->

- [Contributors](#contributors)
  - [Becoming a Contributor](#becoming-a-contributor)
- [Collaborators](#collaborators)
  - [Collaborator Activities](#collaborator-activities)
- [Members](#members)
  - [CommComm Meetings](#CommComm-meetings)
- [Collaborator Nominations](#collaborator-nominations)
  - [Onboarding](#onboarding)
- [Consensus Seeking Process](#consensus-seeking-process)

<!-- /TOC -->

## Contributors

An individual begins contributing as a "Contributor". A contributor is an individual
participating in working groups or initiatives of the Community Committee by:

* commenting on an issue or pull request, OR
* creating an issue or pull request

Contributors have no special access to the repositories under the Community Committee.

### Becoming a Contributor

To begin contributing to working groups and initiatives, start participating!

Attend the meetings of the working group or initiative, investigate issues tagged
as `good first issue`, open issues and pull requests, or provide insight via GitHub.

## Collaborators

CommComm Collaborators are active contributors with write access to the repo(s)
relevant to their initiative or working group.

Active Contributors in the CommComm repositories can be nominated by another
Collaborator to become a Collaborator. On approval by existing Collaborators
through the consensus process, the nominated Contributor becomes a Collaborator.

Typical activities of a Collaborator include:

* Helping users and novice contributors
* Contributing code, non-code, and documentation changes that improve the project
* Reviewing and commenting on issues and pull requests
* Participating in working groups or initiatives
* Merging pull requests

The CommComm periodically reviews the Collaborator list to identify inactive Collaborators. Past Collaborators are typically given Emeritus status. 

Emeriti may request that the CommComm restore them to active status. The process is as follows:
1. The Emeriti opens a PR on [README.md](https://github.com/nodejs/community-committee/blob/master/README.md) moving themselves from the `Community Committee Emeriti` section to the active section.
2. The CommComm votes during the next meeting to validate the return of the Emeriti as an active collaborator.

Please refer to the Committee's [Collaborators Guide](./COLLABORATOR_GUIDE.md) for further information.

## Members

Active Collaborators of a CommComm initiative or working group
can self-nominate or be nominated by a CommComm Member to
become a Member of CommComm. On approval by the consensus
process, the Collaborator becomes a Member.

Collaborators voted in as Members are given write access to all repositories of
the Community Committee, the admin repos, and the moderation repo.

CommComm Members are administrative and help to remove barriers for initiatives and working
groups under CommComm’s scope. CommComm Members are involved primarily with decisions that have
wider reaching effects than within a single initiative or individual working group.
CommComm Members are responsible for making decisions when consensus cannot be reached
among Collaborators.

Working groups and initiatives should check-in with CommComm. As the CommComm Members serve
as a point of reference for initiatives and working groups, this check-in helps
to keep all stakeholders across the Node.js project up-to-date. This improves the
initiatives' and working groups' accountability and success.

### CommComm Meetings

The CommComm meets regularly in a voice conference call. The meeting is run by a
designated meeting chair approved by the CommComm. Each meeting is streamed on
YouTube.

Items are added to the CommComm agenda which are considered contentious or
are modifications of governance, contribution policy, CommComm membership,
or release process.

The intention of the agenda is not to approve or review all patches.
That should happen continuously on GitHub and be handled by the larger
group of Collaborators.

Any community member or contributor can ask that something needs to be reviewed
by the CommComm by logging a GitHub issue. Any Collaborator, CommComm member.
If consensus-seeking among CommComm members fails for a particular issue, it
may be added to the CommComm meeting agenda by adding the `cc-agenda` label.

The CC will elect from amongst voting CC members a CC Chairperson to work on building an agenda for CC meetings and a CC Director to represent
the CC to the Board for a term of one year according to the Node.js Foundation’s By-laws. The Chair and Director may be (but are not required to be)
the same person. The CC shall hold annual elections to select a CC Chairperson and Director; there are no limits on the number of terms a CC Chairperson
or Director may serve.

The CommComm may invite additional persons to participate in a non-voting capacity.

The meeting chair is responsible for ensuring that minutes are taken and that a
pull request with the minutes is submitted after the meeting.

Due to the challenges of scheduling a global meeting with participants in
several time zones, the CommComm will seek to resolve as many agenda items as possible
outside of meetings using
[the Community-Committee issue tracker](https://github.com/nodejs/community-committee/issues). The process in
the issue tracker is:

* A CommComm member opens an issue explaining the proposal/issue and @-mentions
  @nodejs/community-committee.
* After 72 hours, if there are two or more `LGTM`s from other CommComm members and no
  explicit opposition from other CommComm members, then the proposal is approved.
* If there are any CommComm members objecting, then a conversation ensues until
  either the proposal is dropped, or the objecting members are persuaded. If
  there is an extended impasse, a motion for a vote may be made.

## Collaborator Nominations

Active Contributors of a CommComm initiative or working group can be
nominated by another Collaborator to become a Collaborator of
that initiative or working group. Contributors making
significant, ongoing, and valuable contributions are also
identified by the CommComm, and their addition as Collaborators is
discussed during the weekly CommComm meeting. On approval by the
consensus process, the Contributor becomes a Collaborator and is
given commit-access to the repo(s) relevant to their initiative.

Modifications to the contents of the git repositor(y/ies) under
the responsibility of the Collaborators are made on a
collaborative basis as defined in the development process.
Collaborators may opt to elevate significant or controversial
modifications, or modifications that have not found consensus,
to the CommComm for discussion by assigning the `cc-agenda` tag to a
pull request or issue. The CommComm should serve as the final arbiter
where required. The CommComm will maintain and publish a list of
current Collaborators by Project, as well as a development
process guide for Collaborators and Contributors looking to
participate in the effort.

Collaborators may request Emeritus status when they find themselves inactive. The
CommComm also periodically reviews the Collaborator list to identify inactive Collaborators.
Past Collaborators are typically given Emeritus status. Emeriti may request that
the CommComm restore them to active status.

### Onboarding

All collaborators added as CommComm members should be on-boarded in a timely manner
and be given write access to the repository.

This template can be used when onboarding new members:

```
CommComm Membership Checklist:

- [ ] Invite to CommComm GitHub Team (and Node.js GitHub org, if not already a member)
- [ ] Submit PR to add to the [CommComm email alias](https://github.com/nodejs/email/blob/master/iojs.org/aliases.json)
- [ ] Submit PR to add to the (CommComm README.md](https://github.com/nodejs/community-committee/blob/master/README.md#community-committee-members)
- [ ] Add person to the invited list in the templates for the [process that generates meeting issues](https://github.com/nodejs/create-node-meeting-artifacts)
```

Please refer to the Committee's [onboarding documentation](./ONBOARDING.md) for further information.

### Offboarding

When CommComm members need to be off-boarded, we should attempt to off-board them in a timely
manner.

```
CommComm Offboarding Checklist:

- [ ] Remove the person from CommComm GitHub Team
- [ ] Submit PR to remove the person from the [CommComm email alias](https://github.com/nodejs/email/blob/master/iojs.org/aliases.json)
- README:
  - [ ] If leaving on good terms, submit PR to move the individual to Emeriti the [CommComm README.md](https://github.com/nodejs/community-committee/#community-committee-emeriti)
  - [ ] If not leaving on good terms, submit PR to remove the person from [CommComm README.md](https://github.com/nodejs/community-committee/#community-committee-members)
- [ ] Remove the person from the invited list in the templates for the [process that generates meeting issues](https://github.com/nodejs/create-node-meeting-artifacts)
```

## Consensus Seeking Process

The CommComm follows a [Consensus Seeking][] decision-making model as described by
the [CommComm Charter][].

[collaborators-discussions]: https://github.com/orgs/nodejs/teams/collaborators/discussions
[Consensus Seeking]: https://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[CommComm Charter]: https://github.com/nodejs/community-committee/blob/master/Community-Committee-Charter.md
[nodejs/node]: https://github.com/nodejs/node

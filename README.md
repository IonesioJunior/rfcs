# OpenMined Request for Comments

A place to make request for contributions.

The purpose of an OpenMined RFC is to engage the OpenMined community in
development, by getting feedback from stakeholders and experts, and
communicating design changes broadly. This repository is heavily influenced
by the [Tensorflow RFC process](https://github.com/tensorflow/community).

## What is a RFC?

RFC stands for Request For Comments.

RFCs are a way to describe a design change facilitating interaction and discussion.

Before submitting an RFC, it is a good idea to discuss your aims with project
contributors at the #team-pysyft [Slack channel](http://slack.openmined.org/).

## RFC Template

Use the template [from
GitHub](https://github.com/OpenMined/rfcs/blob/master/yyyymmdd-rfc-template.md),
being sure to follow the naming conventions described above.

## Who is involved?

Any **community member** may help by providing feedback on whether the RFC will
meet their needs.

An **RFC author** is one or more community member who writes an RFC and is
committed to championing it through the  process.

An **RFC sponsor** is any maintainer who sponsors the RFC and will shepherd it
through the RFC review process.

A **review committee** is a group of maintainers who have the responsibility of
recommending the adoption of the RFC.

## What is an OpenMined RFC?

An RFC is a document that describes a requirement and the proposed changes that
will solve it. Specifically, the RFC will:

* be formatted according to the RFC template
* be submitted as a pull request to this repo
* be subject to discussion and a review meeting prior to acceptance

## RFC process

Before submitting an RFC, it is a good idea to discuss your aims with project
contributors and maintainers and get early feedback. Use the appropriate team
channel (e.g. #team_pysyft or #team_syft_js) in Slack when getting feedback from
core contributor and experts.

Most often, your idea will not require a full RFC. If your idea requires changes
that would affect a large enough cross-section of the OpenMined community, a
core contributor will recommend filing an RFC. After writing the RFC draft, get
feedback from these experts before submitting it.

1. Recruit a sponsor from the maintainers of the project which your RFC concerns.

   Identify them in the RFC, before posting the PR in step 2.
   If no sponsor is found you may still post the RFC, but if
   within a month of posting the PR there is still no sponsor,
   it will be closed.

2. Submit your RFC as a pull request to OpenMined/rfcs.

   Name your RFC file using the [template](https://github.com/OpenMined/rfcs/blob/master/yyyymmdd-rfc-template.md) `YYYYMMDD-descriptive-name.md`, where
   YYYYMMDD is the date of submission, and ‘descriptive-name’ relates to the
   title of your RFC. For instance, if your RFC is titled “Parallel Widgets API”,
   you might use the filename `20180531-parallel-widgets.md`. If you have images
   or other auxiliary files, create a directory of the form
   `YYYYMMDD-descriptive-name` in which to store those files.

   Include the header table and the contents of the **Objective** section
   in the comment of your pull request, using Markdown. For an example,
   please see TODO [this example
   RFC](#). Include a mention of any of the GitHub handles of co-authors,
   reviewers, and sponsors.

   At the top of the PR identify how long the comment period will be. This
   should be a minimum of TODO from posting the PR.

3. Make an announcement in Slack regarding the new RFC with a brief description,
   and a link to the
   PR and a request for review. Follow the example of previous announcements,
   as you can see in TODO [this
   example](https://groups.google.com/a/tensorflow.org/forum/#!topic/developers/PIChGLLnpTE).

4. The sponsor will request a review committee meeting, no sooner than TODO
   after the RFC PR is posted. If discussion is lively, wait until it has
   settled before going to review. The goal of the review meeting is to resolve
   minor issues; consensus should be reached on major issues beforehand.

5. The meeting may approve the RFC, reject it, or require changes before it
   can be considered again. Approved RFCs will be merged into OpenMined/rfcs, and
   rejected RFCs will have their PRs closed.

6. Implementations of a successful RFC should reference it in their
   documentation, and work with the sponsor to successfully land the code.

While implementation code is not necessary to start the RFC process, its
existence in full or part may help the design discussion.

If in any doubt about this process, feel free to ask on the
developers mailing list or file an issue in this repository.

## Community members

As the purpose of RFCs is to ensure the community is well represented and served
by new changes to OpenMined projects, it is the responsibility of community
members to participate in reviewing RFCs where they have an interest in the
outcome.

Community members should:

* provide feedback as soon as possible to allow adequate time for consideration
* read RFCs thoroughly before providing feedback
* be civil and constructive

## Review committees

The constitution of a review committee may change according to the particular
governance style and leadership of each project. For core OpenMined repositories
like PySyft, the committee will consist of Core Contributors (i.e. team leads)
expertise in the relevant domain area. For changes only relevant to particular
teams like Crypto or Syft.JS, the committee will mainly consist of members of
that team.

Review committees must:

* ensure that substantive items of public feedback have been accounted for
* add their meeting notes as comments to the PR
* provide reasons for their decisions

If a review committee requires changes before acceptance, it is the
responsibility of the sponsor to ensure these are made and seek subsequent
approval from the committee members.

## RFC sponsors

A sponsor is a project maintainer responsible for ensuring the best possible
outcome of the RFC process. In particular this includes:

* advocating for the proposed design
* guiding the RFC to adhere to existing design and style conventions
* guiding the review committee to come to a productive consensus
* if the RFC moves to implementation:
  * ensuring proposed implementation adheres to the design
  * liaison with appropriate parties to successfully land implementation

## Keeping the bar high

While we encourage and celebrate every contributor, the bar for RFC acceptance
should be kept intentionally high. A design may be rejected or need significant
revision at any one of these stages:

* initial design conversations on the relevant mailing list
* failure to recruit a sponsor
* critical objections during the feedback phase
* failure to achieve consensus during the design review
* concerns raised during implementation (e.g., inability to achieve backwards
  compatibility, concerns about maintenance appearing once a partial
  implementation is available)

If this process is functioning well, RFCs are expected to fail in the earlier,
rather than later, stages.

An approved RFC is no guarantee of a commitment to implement, and acceptance of
a proposed RFC implementation is still subject to the usual code review
process.

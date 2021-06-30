# How to contribute

We are really glad you are reading this, because we need volunteer developers to help this project come to fruition.

- [How to contribute](#how-to-contribute)
  - [Code of Conduct](#code-of-conduct)
    - [Issues](#issues)
    - [Triaging](#triaging)
      - [More about labels](#more-about-labels)
    - [Pull Requests](#pull-requests)
    - [Reviews](#reviews)
    - [Commit convention](#commit-convention)
  - [Coding Guidelines](#coding-guidelines)
  - [Developer Certificate Of Origin](#developer-certificate-of-origin)

## Code of Conduct

All the projects here have a [Code of Conduct](CODE_OF_CONDUCT.md) to which all contributors must adhere.
Please read it before interacting with the repository or the community in any way.

### Issues

Issues are the heartbeat ❤️ of projects. There are mainly three kinds of issues you can open:

* Bug report: you believe you found a problem in a project and you want to discuss and get it fixed,
  creating an issue with the **bug report template** is the best way to do so.
* Enhancement: would you like a new feature/rule to be added? This is the kind of issue you'll need then.
  Do your best at explaining your intent, it's always important that others can understand what you mean in order to discuss.
  Be open and collaborative in letting others help you getting things done!
* Failing tests: did you notice a flaky test or a problem with a build? This is the kind of issue to triage that!

The best way to **get involved** in the project is through issues. You can help in many ways:

* Issues triaging: participating in the discussion and adding details to open issues is always a good thing;
sometimes issues need to be verified, you could be the one writing a test case to fix a bug!
* Helping to resolve the issue: you can help in getting it fixed in many ways, more often by opening a pull request.

### Triaging

We need help in categorizing issues. Thus any help is welcome!

When you triage an issue, you:

* assess whether it has merit or not

* quickly close it by correctly answering a question

* point the reporter to a resource or documentation answering the issue

* tag it via labels, projects, or milestones

* take ownership submitting a PR for it, in case you want 😇

#### More about labels

These guidelines are not set in stone and are subject to change.

Anyway a `kind/*` label for any issue is mandatory.

You can use commands - eg., `/label <some-label>` to add (or remove) labels or manually do it.

The commands available are the following ones:

```console
/[remove-](area|kind|priority|triage|label)
```

Some examples:

* `/area rules`
* `/remove-area rules`
* `/kind kernel-module`
* `/label good-first-issue`
* `/triage duplicate`
* `/triage unresolved`
* `/triage not-reproducible`
* `/triage support`
* ...

### Pull Requests

Thanks for taking time to make a [pull request](https://help.github.com/articles/about-pull-requests) (hereafter PR).

In the PR body, feel free to add an area label if appropriate by typing `/area <AREA>`, PRs will also
need a kind, make sure to specify the appropriate one by typing `/kind <KIND>`.

The PR template is there to guide you through the process of opening it.

Also feel free to suggest a reviewer with `/cc @theirname`, or to assign an assignee using `/assign @nickname`.

Once your reviewer is happy, they will say `/lgtm` which will apply the
`lgtm` label, and will apply the `approved` label if they are an
[owner](/OWNERS) for the project.

Your PR will be automatically merged once it has the `lgtm` and `approved`
labels, does not have any `do-not-merge/*` labels, and all status checks (eg., rebase, tests, DCO) are positive.

### Reviews

Reviewing a pull request is also a very good way of contributing.

### Commit convention

As commit convention, we adopt [Conventional Commits v1.0.0](https://www.conventionalcommits.org/en/v1.0.0/), we have an history
of commits that do not adopt the convention but any new commit should follow it.

Pull requests towards projects using the `release-note` plugin MUST have release note following such convention to be eligible for merge.

## Coding Guidelines

This is handled on a per-repository basis.

## Developer Certificate Of Origin

The [Developer Certificate of Origin (DCO)](https://developercertificate.org/) is a lightweight way for contributors
to certify that they wrote or otherwise have the right to submit the code they are contributing to the project.

Contributors to the project sign-off that they adhere to these requirements by adding a `Signed-off-by` line to commit messages.

```console
This is my commit message

Signed-off-by: Jane Doe <jane@doe.org>
```

Git even has a `-s` command line option to append this automatically to your commit message:

```console
git commit -s -m 'This is my commit message'
```

If you have already made a commit and forgot to include the sign-off, you can amend your last commit
to add the sign-off with the following command, which can then be force pushed.

```console
git commit --amend -s
```

**Remember**: you don't have to be a maintainer to make a difference here, just start helping and our community will immediately
recognize and make you feel at home!
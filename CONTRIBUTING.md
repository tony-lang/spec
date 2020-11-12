# Contributing

Thank you in showing interest in contributing to Tony! We greatly value every contribution from

* fixing a syntax error, improving style or adding a paragraph;
* adding to the documentation;
* reporting a bug; to
* proposing a change to the language spec.

## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Contributing ideas and reporting bugs

We use GitHub issues as a ticket system. You should open an issue if

* you want to [report a bug](https://github.com/tony-lang/spec/issues/new?assignees=&labels=bug&template=bug_report.md&title=);
* you want to [open a proposal](https://github.com/tony-lang/spec/issues/new?assignees=&labels=discussion%2C+proposal&template=proposal.md&title=); or
* you want to [make changes to the documentation](https://github.com/tony-lang/spec/issues/new?assignees=&labels=documentation&template=documentation.md&title=) (that go beyond fixing a syntax error here or adding a paragraph there).

You should **not** open an issue if

* you have a question. If you have a question use [Stack Overflow](https://stackoverflow.com) instead or send an email to the project team at jonas.huebotter@gmail.com.
* you want to fix a syntax error or otherwise adjust a sentence in the documentation. You may immediately propose your changes in a pull request.

When you open an issue we urge you to use the provided templates.

**Note of caution**: Please only report a bug in this repository if it is a bug of the language specification itself. If instead, an implementation of this specification has a bug, open an issue in the corresponding repository.

## Proposals

The Tony programming language is improved and changed through a rigorous process.

### Opening a proposal

Every proposal starts with an idea. If you have an idea please consider sharing it with everyone by opening a proposal in this repository.

A finished proposal should consist of the following:

1. a brief description of the motivation behind the change
1. a description of the syntactic changes
1. a description of the semantics of the changed syntax
1. a description of possible implementations of the updated spec

When you first open a proposal you do not have to tick all of these boxes. It is encouraged to start with a proposal as small and concise as possible to incorporate feedback as soon as possible.

Only proposals that satisfy all of the above will be accepted.

### Accepting a proposal

After a proposal is accepted (i.e. merged into `main`), that does not mean the proposal is now part of the language spec. Now the actual work of implementation begins.

First, the proposed changes have to be implemented in a pull request in this repository.

Whenever a new version of the spec is released all proposals accepted up to this point are locked. This means that implementors of the spec can now depend on the changes to the spec.

There are two phases to the release-process:

* pre-releases

  Every accepted proposal will first be released in a pre-release. This is when the core componenents of Tony (such as the parser and the compiler) will implement the proposal. At this stage proposals may not be changed anymore. Proposals my be disregarded, however, in case its its implementation turns out to be harder and less worthwhile than originally anticipated.

* releases

  Once all accepted proposals of a pre-release are implemented by the core components of Tony, the proposals that were not disregarded are incorporated into the specification of Tony.

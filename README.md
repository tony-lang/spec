# Tony spec

This repository is home to the formal syntax specification of the Tony programming language. The semantics are specified by the [Tony compiler](https://github.com/tony-lang/tony).

Tony is a functional, strongly typed, high level, general purpose programming language. Tony employs refinement types, allowing its type checker to catch domain-specific bugs at compile time.

Other core components of Tony can be found through the following links:

* [Compiler and Type Inference algorithm](https://github.com/tony-lang/tony)
* [Parser](https://github.com/tony-lang/tree-sitter-tony)
* [CLI](https://github.com/tony-lang/cli)

New proposals to Tony are made in this repository. You can learn more about proposals to Tony [here](CONTRIBUTING.md#proposals).

## Releases

[Here](https://github.com/tony-lang/spec/releases/) you can find details on all past releases.
Unreleased breaking changes that are on the current master can be found [here](CHANGELOG.md).

Tony follows Semantic Versioning 2.0 as defined at http://semver.org.

### Publishing

1. Review breaking changes and deprecations in `CHANGELOG.md`
1. Reset `CHANGELOG.md`
1. Create a new release listing the breaking changes, deprecations and commits on `main` since the last release.

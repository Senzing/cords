# cords

This repository holds the community artifacts for `cords` in the Senzing
organization: README, CONTRIBUTING, CODE_OF_CONDUCT, LICENSE, CHANGELOG,
SECURITY, documentation scaffolding and the GitHub workflows. Project content
is added by the development team.

Development work happens in
<https://github.com/senzing-garage/cord-development>.

## Files

For directory structure, see [Directory layout].

Senzing community files:

1. .claude/
   1. [CLAUDE.md]
   1. [commands/senzing.md]
   1. [settings.json]
1. .github/
   1. [CODEOWNERS]
   1. [dependabot.yml]
   1. [senzing-corporate-contributor-license-agreement]
   1. [senzing-individual-contributor-license-agreement]
   1. linters/
   1. workflows/
1. .vscode
   1. [cspell.json]
1. [docs/]
1. [CHANGELOG.md]
1. [CODE_OF_CONDUCT.md]
1. [CONTRIBUTING.md]
1. [LICENSE]
1. [README.md]
1. [SECURITY.md]

## .claude

### .claude/commands/senzing.md

The [.claude/commands/senzing.md file] contains a [Claude custom command] which is a "router" to all Senzing custom commands.

### .claude/settings.json

The [.claude/settings.json file] contains repository-scoped Claude settings.

## .github

### .github/CODEOWNERS

The [.github/CODEOWNERS file] implements GitHub's [code owners].
The teams that may appear in a `CODEOWNERS` file can be seen at [github.com/orgs/Senzing/teams].

### .github/dependabot.yml

The [dependabot.yml file] is configuration for [GitHub's dependabot].

### .github/linters

The [.github/linters directory] holds the linter configuration used by [lint-workflows.yaml]. Each file is described in [.github/linters/README.md].

### .github/senzing-corporate-contributor-license-agreement.pdf

The Senzing, INC. Software Grant and Corporate Contributor License Agreement (CCLA), [senzing-corporate-contributor-license-agreement.pdf], is the standard agreement for a corporation's contribution to a Senzing repository.

### .github/senzing-individual-contributor-license-agreement.pdf

The Individual Contributor License Agreement (ICLA), [senzing-individual-contributor-license-agreement.pdf], is the standard agreement for an individual's contribution to a Senzing repository.
_Note:_ if an individual is contributing on behalf of a company, the [senzing-corporate-contributor-license-agreement] must also be submitted and accepted.

### .github/workflows

The [.github/workflows directory] holds the GitHub Actions workflows. Each is described in [.github/workflows/README.md].

## docs

The [docs directory] subdirectory may be published as [GitHub Pages].
They become visible at [hub.senzing.com].
URLs have the format:

```console
https://hub.senzing.com/<repository-name>
```

Example:
[hub.senzing.com/sdk-components-ng]

## .vscode

### .vscode/cspell.json

The [.vscode/cspell.json file] is used to maintain a list of acceptable spellings for [cspell] checking

## CHANGELOG.md

The contents of the [CHANGELOG.md file] are meant to be consumed by users of the repository.
As such, they need to know what changes affect them as users.
In general, changes that do not affect users should not be captured in `CHANGELOG.md`.

The format of `CHANGELOG.md` is based on [Keep a Changelog] and [CommonMark].
Also, projects adhere to [Semantic Versioning].

## CODE_OF_CONDUCT.md

The [CODE_OF_CONDUCT.md file] describes the social conventions among contributors to the repository.

> A _code of conduct_ defines standards for how to engage in a community.
> It signals an inclusive environment that respects all contributions.
> It also outlines procedures for addressing problems between members of your project's community.
> For more information on why a code of conduct defines standards and expectations for how to engage in a community, see the [Open Source Guide].
>
> -- <cite>GitHub's [Adding a code of conduct to your project]</cite>

The [CODE_OF_CONDUCT.md file] in this repository is based on GitHub's "[Contributor Covenant]".

## CONTRIBUTING.md

The [CONTRIBUTING.md file] describes the process for contributing to the repository.

> To help your project contributors do good work, you can add a file with contribution guidelines to your project repository's root.
> When someone opens a pull request or creates an issue, they will see a link to that file.
>
> -- <cite>GitHub's [Setting guidelines for repository contributors]</cite>

## LICENSE

The `LICENSE` file describes the terms and conditions under which the code in the repository can be used.
The recommended license file is "[Apache License 2.0]".
A comparison of licenses can be found at [choosealicense.com].

The [LICENSE file] in this repository is based on "[Apache License 2.0]".

## README.md

The file you are reading lists the files in this repository and what each is for.

## SECURITY.md

The contents of the [SECURITY.md file] explain the security aspects of the repository.
This includes how to report a suspected vulnerability.

## Directory layout

```console
├── .claude
│   ├── CLAUDE.md
│   ├── commands
│   │   └── senzing.md
│   └── settings.json
├── .github
│   ├── CODEOWNERS
│   ├── dependabot.yml
│   ├── linters
│   │   ├── .checkov.yaml
│   │   ├── .jscpd.json
│   │   ├── .yaml-lint.yml
│   │   ├── README.md
│   │   └── zizmor.yaml
│   ├── senzing-corporate-contributor-license-agreement.pdf
│   ├── senzing-individual-contributor-license-agreement.pdf
│   └── workflows
│       ├── README.md
│       ├── add-labels-standardized.yaml
│       ├── add-to-project-senzing-dependabot.yaml
│       ├── add-to-project-senzing.yaml
│       ├── check-claude-attribution.yaml
│       ├── claude-pr-review.yaml
│       ├── dependabot-approve-and-merge.yaml
│       ├── link-issues-to-pr-post-merge.yaml
│       ├── lint-workflows.yaml
│       ├── move-pr-to-done-dependabot.yaml
│       └── spellcheck.yaml
├── .gitignore
├── .project
├── .vscode
│   ├── cspell.json
│   └── settings.json
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── SECURITY.md
└── docs
    ├── README.md
    ├── best-practices.md
    ├── development.md
    ├── errors.md
    └── examples.md
```

[.claude/commands/senzing.md file]: .claude/commands/senzing.md
[.claude/settings.json file]: .claude/settings.json
[.github/CODEOWNERS file]: .github/CODEOWNERS
[.github/linters directory]: .github/linters
[.github/linters/README.md]: .github/linters/README.md
[.github/workflows directory]: .github/workflows
[.github/workflows/README.md]: .github/workflows/README.md
[lint-workflows.yaml]: .github/workflows/README.md#lint-workflowsyaml
[.vscode/cspell.json file]: .vscode/cspell.json
[Adding a code of conduct to your project]: https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/
[Apache License 2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[CHANGELOG.md file]: CHANGELOG.md
[CHANGELOG.md]: #changelogmd
[choosealicense.com]: https://choosealicense.com/licenses/
[Claude custom command]: https://code.claude.com/docs/en/slash-commands#custom-slash-commands
[code owners]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
[CODE_OF_CONDUCT.md file]: CODE_OF_CONDUCT.md
[CODE_OF_CONDUCT.md]: #code_of_conductmd
[CODEOWNERS]: #githubcodeowners
[commands/senzing.md]: #claudecommandssenzingmd
[CommonMark]: https://commonmark.org/
[CONTRIBUTING.md file]: CONTRIBUTING.md
[CONTRIBUTING.md]: #contributingmd
[Contributor Covenant]: https://www.contributor-covenant.org/version/3/0/code_of_conduct/
[cspell.json]: #vscodecspelljson
[cspell]: https://cspell.org/
[dependabot.yml file]: .github/dependabot.yml
[dependabot.yml]: #githubdependabotyml
[Directory layout]: #directory-layout
[docs directory]: docs
[docs/]: #docs
[hub.senzing.com]: https://hub.senzing.com/
[hub.senzing.com/sdk-components-ng]: https://hub.senzing.com/sdk-components-ng/
[GitHub Pages]: https://pages.github.com/
[github.com/orgs/Senzing/teams]: https://github.com/orgs/Senzing/teams
[GitHub's dependabot]: https://docs.github.com/en/code-security/dependabot
[Keep a Changelog]: https://keepachangelog.com/en/1.1.0/
[LICENSE file]: LICENSE
[LICENSE]: #license
[Open Source Guide]: https://opensource.guide/code-of-conduct/
[README.md]: #readmemd
[SECURITY.md file]: SECURITY.md
[SECURITY.md]: #securitymd
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
[senzing-corporate-contributor-license-agreement.pdf]: .github/senzing-corporate-contributor-license-agreement.pdf
[senzing-corporate-contributor-license-agreement]: #githubsenzing-corporate-contributor-license-agreementpdf
[senzing-individual-contributor-license-agreement.pdf]: .github/senzing-individual-contributor-license-agreement.pdf
[senzing-individual-contributor-license-agreement]: #githubsenzing-individual-contributor-license-agreementpdf
[Setting guidelines for repository contributors]: https://help.github.com/articles/setting-guidelines-for-repository-contributors/
[settings.json]: #claudesettingsjson
[CLAUDE.md]: .claude/CLAUDE.md

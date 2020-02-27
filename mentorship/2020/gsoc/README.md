# GraphQL / Google Summer of Code 2020

The [GraphQL Foundation](https://foundation.graphql.org) has been accepted as a mentor for the [2020 Google Summer of Code.](https://summerofcode.withgoogle.com/) We encourage you to apply!

We encourage you to be creative when submitting proposals for GSoC! All ideas will be considered. If you are familiar with GraphQL and have an idea which isn't on the list, please feel free to submit it as a proposal.

Here is a list of all current and deferred proposals, as well as information on submitting them, and resources for learning about GraphQL and the ecosystem

- [GraphQL / Google Summer of Code 2020](#graphql--google-summer-of-code-2020)
    - [1. GraphQL Compatibility Acceptance Tests (medium)](#1-graphql-compatibility-acceptance-tests-medium)
    - [2. GraphiQL Plugins (medium)](#2-graphiql-plugins-medium)
    - [3. Add streaming support and error recovery to reference GraphQL parser (medium/hard)](#3-add-streaming-support-and-error-recovery-to-reference-graphql-parser-mediumhard)
  - [Deferred for another mentorship opportunity](#deferred-for-another-mentorship-opportunity)
    - [1. Help with the documentation redesign (easy/medium)](#1-help-with-the-documentation-redesign-easymedium)
  - [Submitting Mentorship Proposals](#submitting-mentorship-proposals)
  - [Resources](#resources)
    - [Official GraphQL Documentation](#official-graphql-documentation)
    - [Reccomended Links](#reccomended-links)

Good luck! If you have questions, please reach out to [gsoc@graphql.org](mailto:gsoc@graphql.org). You can also find us and ask questions to the mentors in the [#gsoc](https://graphql.slack.com/archives/CUB2DBYTF) channel on the [GraphQL Slack](https://graphql.slack.com). ([get an invite](https://slack-invite.graphql.org))

### 1. GraphQL Compatibility Acceptance Tests (medium)

**Build a set of compatibility acceptance tests for libraries that implement the GraphQL specification.**

Reference implementation of GraphQL (graphql-js) contains almost two thousand test cases and it constantly growing with every new feature we add in GraphQL. Many GraphQL implementations choose to rewrite these tests in their language of choice but keeping them in sync requires a lot of effort from maintainers. The goal of this project is to extract all non-JS specific tests in some language-independent data format (e.g. YAML) and work closely with maintainers to help them to adapt this test suite to their needs.

**Expected outcomes:** Extract the majority of tests into language-independent format and have a couple of non-JS GraphQL implementations using them for tests.

**Skills required/preferred:** JavaScript and at least one other popular language (Java, C#, Python)

**Mentor:** Ivan Goncharov

---

### 2. GraphiQL Plugins (medium)

**Pick from a list of in-demand GraphiQL plugins and help us build them!**

> **Status:** Plugin framework will be available with documentation and further specs for plugin projects by April 2020 at latest. Please check back here for updates.

GraphiQL is introducing a new plugin system that will allow users to extend and customize the GraphQL development experience substantially. Using these new interfaces, users can choose from a list of proposed plugins that users have asked for and specs, and execute and iterate on them. They can be anything from viewing results in a map, to schema explorer features, as well as new commands and code actions.

**Number of Participants:** The more, the merrier!

**Expected outcomes:** Introduce Pull Requests for plugins, potentially finish and publish some within the time frame

**Skills required/preferred:** Javascript, React, Typescript preferred

**Mentors:** Rikki Schulte, Laura Buns

**Related Issues:**

- discussion/proposal issues: #829, #978
- related/preceeding projects:
  - GraphiQL React 16 Migration + Context - https://github.com/graphql/graphiql/projects/4
  - Redesign, Layout & Themeing System - https://github.com/graphql/graphiql/projects/11
  - renderGraphiQL function and middlewares - https://github.com/graphql/graphiql/projects/8

---

### 3. Add streaming support and error recovery to reference GraphQL parser (medium/hard)

**Make reference GraphQL parser usable for IDE-like applications by adding error recovery and streaming support.**

At the moment we have two parser implementations: a reference parser from the `graphql-js` package which is very simple but fully spec-compliant and `graphql-language-service-parser` which is more advanced (error recovery, streaming, etc.) but is outdated and is hard to support for the graphql-js team. The challenge of the project would be to bring features of advanced parser into reference parser without losing the performance or code-readability.

**Expected outcomes:** Switch both GraphiQL and GraphQL LSP server to use the reference parser from `grahphql-js` deprecating `graphql-language-service-parser`. In the process, you will learn a lot about GraphQL grammar and advanced parsing techniques.

**Skills required/preferred:** JavaScript

**Mentor:** Ivan Goncharov

## Deferred for another mentorship opportunity

### 1. Help with the documentation redesign (easy/medium)

**Implement and be a valuable contributor to the redesigned [https://graphql.org](https://graphql.org)**

We’re looking to re-design the GraphQL website, and that is a good time to re-look over all the way in which we present the language and documentation.
You’ll be working with an experienced designer, who can provide reasonably clear briefs (they are a spare time contributor) where you implement the designs into HTML, and then integrate it into the site.
You’d get to join GraphQL working groups to give updates, write about your work on the GraphQL blog and learn skills applicable to working with the web,

**Expected outcomes:** You learn how to create/improve/ship a complex documentation website for a non-trivial language.

**Skills required/preferred:** JavaScript, APIs, HTML/CSS

**Mentor:** Orta Therox, others

---

## Submitting Mentorship Proposals

If you would like to submit a proposal for an initiative that you would like to mentor, feel free to open a PR to add another section to this document above.

```md
# My Example Initiative

> **Status:** > **You can begin researching and submitting for this PR now**

<description>

**Expected outcomes:**

**Skills required/preferred:** JavaScript

**Mentor:** your name and github account

**Related Issues:**
```

---

## Resources

### Official GraphQL Documentation

- GraphQL Language: https://graphql.org/learn
- GraphQL JS library: https://graphql.org/graphql-js

### Reccomended Links

- How to GraphQL: https://www.howtographql.com/
- Awesome GraphQL: https://github.com/chentsulin/awesome-graphql

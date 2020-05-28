# GraphQL / Google Season of Docs 2020

The [GraphQL Foundation](https://foundation.graphql.org) is applying for the [2020 Google Season of Docs](https://developers.google.com/season-of-docs).

[GraphQL](https://graphql.org) is a fast-growing open source community, supported by a [large number of companies](https://landscape.graphql.org) that use it in production.  While GraphQL has been open source for quite some time, it recently completed its first year as a Linux Foundation project.  You can read more about what we've accomplished in our [2019 annual report](https://foundation.graphql.org/reports/annual-report-2019/).

We are looking for a skilled technical writer who can help with a few projects.  This is a great time to get involved, as we have been working on focusing our efforts, and are planning a documentation redesign.

If you have any questions, please reach out on the [#gsod]() channel in the [GraphQL Slack](https://slack.graphql.org).

Here is a list of our proposals, as well as some resources to help you learn about GraphQL.

### 1. Extend best practices articles (medium/hard)

**Add best practices articles that would help guide people navigating through the GraphQL ecosystem**

Originally the website [intendend to include](https://github.com/graphql/graphql.github.io/issues/41) more best practices articles.
We are looking to create the missing articles as we see a lot of people in community struggle to find good and reliable resources about those.
You’ll be working with The Guild, an experienced group of open source developers and GraphQL foundation members, who will guide you through the concepts and provide you with feedback and reviews.
You’d get to join GraphQL working groups to give updates, write about your work on the GraphQL blog and learn important, advanced architectual concepts.

**Expected outcomes:** You will grasp important architectual concepts and provide guidance to everyone in the community.

**Skills required/preferred:** APIs, Architecture

**Mentor:** [The Guild](http://github.com/the-guild-org), Others

### 2. Resources sorting logic (medium)

**Create a system to keep resources and links up to date**

Today, the graphql.org website is a central place where do community finds important resources and links to tools, articles and libraries.
The current issue is that it is hard to keep those up to date as many of those libraries become unmaintained as time goes by.
There is also no clear guidance and rules for which resources to add and which do not belong on the website.
The goal of this task is to add a process, that would take as input a list of resources, and at build time would fetch up to date information about each of them (Github stars, commit history, package downloads, etc) and order those resources on the page according to a clear algorithm.
That would help keep relevant resource up and unmaintained resources down as time goes by.
You’ll be working with The Guild, an experienced group of open source developers and GraphQL foundation members, who will guide you the technical process and provide you with feedback and reviews.
You’d get to join GraphQL working groups to give updates, write about your work on the GraphQL blog and learn technical skills for building static websites and API aggregations.

**Expected outcomes:** A reliable system that keeps our community resources relevant and up to date.

**Skills required/preferred:** APIs, Static built websites

**Mentor:** [The Guild](http://github.com/the-guild-org), Others

### 3. Revamp `graphql-js` docs (medium/hard)

**Review and update existing docs and complete it with tutorials and FAQ**

There is a [documentation for graphql-js](https://graphql.org/graphql-js/), but it is severely outdated because it was handwritten for the first public release four years ago. It was rarely updated since.

The idea is to synchronize it with the source code by generating it from JSDoc comments. GraphQL.js maintainers will handle docs generation so you can focus on:

  - improving the quality of existing JSDoc comments
  - cover missing functions/arguments
  - adding examples
  
The next step would be to implement documentation best practices as Introduction, Tutorials, FAQ.

You will be working with GraphQL.js maintainers who will be ready to answer your questions and provide technical expertise.

We expect you to be able to write code snippets in JS/TS, understand and explain complex concepts as lexer, parser, AST, etc.

**Expected outcomes:** Full and up to date documentation for `graphql-js`.

**Skills required/preferred:** knowledge of GraphQL, JavaScript/TypeScript

**Mentor:** Ivan Goncharov ([@IvanGoncharov](https://github.com/IvanGoncharov/))

### 4. Create FAQ resource (medium)

**Gather commonly asked questions about GraphQL and work with the core team to document answers**

At the moment, `graphql.org` doesn't include the FAQ section. This situation leads to the constant stream of repeating questions and also some long-leaving misconceptions in the community.

The FAQ should cover a broad spectrum of questions around GraphQL but should not contain any vendor or language-specific questions. Questions should be split into sections:

 - Common section, e.g., "Who is behind GraphQL?"
 - GraphQL basics, e.g. "[What is the difference between Mutation and Query?](https://stackoverflow.com/questions/48003767/what-is-the-difference-between-mutation-and-query)"
 - Specification section, e.g., "How to contribute to the specification?"
 - etc
 
FAQ section will provide a way to link to a specific answer and will benefit all GraphQL maintainers and vendors.

You will source different channels (GitHub Issues, Stackoverflow, Quora) and identify common questions and answers. GraphQL maintainers will help you to come up with the most accurate and helpful answers. 

As the final step, you will integrate the FAQ section into `graphql.org` website.

**Expected outcomes:** Solid FAQ section for `graphql.org` website

**Skills required/preferred:** Basic knowledge of GraphQL, Static built websites

**Mentor:** Ivan Goncharov ([@IvanGoncharov](https://github.com/IvanGoncharov/)), Others

---

## Submitting Documentation Proposals (for prospective mentors)

If you would like to submit a proposal for an initiative that you would like to mentor, feel free to open a PR to add another section to this document above.

```md
# My Example Initiative

> **Status:** 
> **You can begin researching and submitting for this PR now**

<description>

**Expected outcomes:**

**Skills required/preferred:** JavaScript

**Mentor:** your name and github account

**Related Issues:**
```

---

## Resources

### Official GraphQL Documentation

- GraphQL Language: [https://graphql.org/learn](https://graphql.org/learn)
- GraphQL JS library: [https://graphql.org/graphql-js](https://graphql.org/graphql-js)

### Recommended Links

- Exploring GraphQL: A Query Language for APIs [https://www.edx.org/course/exploring-graphql-a-query-language-for-apis](https://www.edx.org/course/exploring-graphql-a-query-language-for-apis)
- Awesome GraphQL: [https://github.com/chentsulin/awesome-graphql](https://github.com/chentsulin/awesome-graphql)
- GraphQL Landscape: [https://landscape.graphql.org](https://landscape.graphql.org)

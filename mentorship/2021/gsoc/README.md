# GraphQL / Google Summer of Code 2021

[GraphQL](https://graphql.org) is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

The [GraphQL Foundation](https://foundation.graphql.org) is applying to be a mentor for the [2021 Google Summer of Code](https://summerofcode.withgoogle.com/)!

<!--We encourage the GraphQL community to propose projects prior to the project application deadline on February 19th, 2021. *Please complete your proposals by February 12th so we have time to review, merge, and submit them.*

We encourage you to be creative when submitting proposals for GSoC! All ideas will be considered. If you are familiar with GraphQL and have an idea which isn't on the list, please feel free to submit it as a proposal.

As you develop ideas, please add them using this template:

```
### Title of proposal

**[One sentence summary]**

[1-2 paragraphs of description, including which projects or working groups it covers and estimated difficulty (beginner, intermediate, advanced)]

**Expected outcomes**

* [outcome 1]
* [outcome 2]
* ...

**Skills required/preferred**

* [skill 1]
* [skill 2]
* ...

**Mentors**

* [mentor name]
* [mentor name]
* ...
```

Good luck!-->

If you have questions, please reach out to [gsoc@graphql.org](mailto:gsoc@graphql.org). You can also find us and ask questions to the mentors in the [#gsoc](https://graphql.slack.com/archives/CUB2DBYTF) channel on the [GraphQL Slack](https://graphql.slack.com). ([get an invite](https://slack-invite.graphql.org))

### 1. Make queries/SDL outputed by `graphql-js` compatible with `prettier` (Hard)

**Make GraphQL.js's print/printSchema functions format their output in way that is prettier compatible**

`graphql-js` provide [print](https://github.com/graphql/graphql-js/blob/main/src/language/printer.js)/[printSchema](https://github.com/graphql/graphql-js/blob/main/src/utilities/printSchema.js) functions that output strings in GraphQL language format.
Currently they are implemented in very simple manner so their output sometimes contains very long string or some other artifacts that look unpleasant.
[Prettier](https://prettier.io/) becames de facto standard for formatting source code and it has support for GraphQL for years.
So instead of reinventing the wheel we can make our implementation compatible with prettier.
Also since prettier already using our `parse` function, as part of this project, we can collaborate with Prettier team to figure out if it possible for them to also use our `print` function.

**Expected outcomes**

* `print`/`printSchema` functions output is compatible with prettier
* A lot of new test cases and 100% coverage for `print`/`printSchema` functions
* Complited research project on switching Prettier to use GraphQL.js's `print` function

**Skills required/preferred**

* Strong knowledge of JavaScript/TypeScript
* Experience with GraphQL
* Experience with writing AST related code (Babel plugings, ESLint rules, etc.)

**Mentors**

* [IvanGoncharov](https://github.com/IvanGoncharov)

### 2. Integrate `graphql-relay-js` into `graphql-js`(Medium)

**Move source code from `graphql-relay-js` into `graphql-js` repo to ease maintanance burden**

Relay style pagination became popular standard in GraphQL world and we provide useful utils to make it easier to implement as part of [graphql/graphql-relay-js](https://github.com/graphql/graphql-relay-js) however maintaining it as separate repo significantly increase maintainance burden.
Since `graphql-relay` package has zero dependencies (beyound `graphql`) we can easily integrate it into `graphql` package as subfolder.
Biggest challenge would be to bring migrated code to TS and bring it up to `graphql-js` standards (test coverage, docs, etc.).

**Expected outcomes**

* All opened issues and PRs on `graphql-relay-js` are triaged and either fixed/closed or transfered to `graphql-js` repository.
* All source code from [graphql/graphql-relay-js](https://github.com/graphql/graphql-relay-js) moved into [graphql/graphql-js](https://github.com/graphql/graphql-js) and released as part of [graphql]() package on NPM.
* Migrated code is up to `graphql-js` is converted to TS, passing all checks and validations.

**Skills required/preferred**

* Strong knowledge of JavaScript/TypeScript
* Experience with GraphQL and implementing Relay connection specification in particular
* Refactoring skills

**Mentors**

* [IvanGoncharov](https://github.com/IvanGoncharov)

## Resources

### Official GraphQL Documentation

- GraphQL Language: https://graphql.org/learn
- GraphQL JS library: https://graphql.org/graphql-js

### Recommended Links

- How to GraphQL: https://www.howtographql.com/
- Awesome GraphQL: https://github.com/chentsulin/awesome-graphql

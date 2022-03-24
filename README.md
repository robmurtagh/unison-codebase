# unison-codebase

This is my personal 'remote' for code I write in the programming language [Unison](https://www.unisonweb.org/)

## 🚀 Using this codebase

Using `ucm`, [the Unison Codebase Manager](https://www.unison-lang.org/learn/install-instructions/):

* Initial push:

```sh
push.create https://github.com/robmurtagh/unison-codebase:.graphql .graphql
```

* Subsquent pushes (to `graphql` namespace):

```sh
push https://github.com/robmurtagh/unison-codebase:.graphql .graphql
```

* Pulling (from `graphql` namespace):

```sh
pull https://github.com/robmurtagh/unison-codebase:.graphql .graphql
```

## 🏗 What I'm working on

Currently, I'm working on a GraphQL parser written in Unison:

![graphql-parser](/assets/graphql-parser.png)

## 📝 Other notes

* `?a` indicates the character literal `a` ([docs](https://www.unison-lang.org/learn/language-reference/literals/))
* Prefix `'` indicates a thunk, prefix `!` forces the thunk ([docs](https://www.unison-lang.org/learn/language-reference/delayed-computations/))

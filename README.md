# GraphQL

<img alt="GraphQL Logo" align="right" src="data:image/png;base64,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" width="15%" />

The GraphQL specification is edited in the markdown files found in [`/spec`](./spec)
the latest release of which is published at https://graphql.github.io/graphql-spec/.

The latest draft specification can be found at https://graphql.github.io/graphql-spec/draft/
which tracks the latest commit to the main branch in this repository.

Previous releases of the GraphQL specification can be found at permalinks that
match their [release tag](https://github.com/graphql/graphql-spec/releases). For
example, https://graphql.github.io/graphql-spec/October2016/. If you are linking
directly to the GraphQL specification, it's best to link to a tagged permalink
for the particular referenced version.

## Overview

This is a Working Draft of the Specification for GraphQL, a query language for APIs created by Facebook.

The target audience for this specification is not the client developer, but those who have,
or are actively interested in, building their own GraphQL implementations and
tools.

In order to be broadly adopted, GraphQL will have to target a wide
variety of backend environments, frameworks, and languages, which will necessitate a
collaborative effort across projects and organizations. This specification serves as a point of coordination for this effort.

Looking for help? Find resources [from the community](https://graphql.org/community/).

## Getting Started

GraphQL consists of a type system, query language and execution semantics,
static validation, and type introspection, each outlined below. To guide you
through each of these components, we've written an example designed to
illustrate the various pieces of GraphQL.

This example is not comprehensive, but it is designed to quickly introduce
the core concepts of GraphQL, to provide some context before diving into
the more detailed specification or the [GraphQL.js](https://github.com/graphql/graphql-js)
reference implementation.

The premise of the example is that we want to use GraphQL to query for
information about characters and locations in the original Star Wars
trilogy.

### Type System

At the heart of any GraphQL implementation is a description of what types
of objects it can return, described in a GraphQL type system and returned
in the GraphQL Schema.

For our Star Wars example, the
[starWarsSchema.js](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsSchema.js)
file in GraphQL.js defines this type system.

The most basic type in the system will be `Human`, representing characters
like Luke, Leia, and Han. All humans in our type system will have a name,
so we define the `Human` type to have a field called "name". This returns
a String, and we know that it is not null (since all `Human`s have a name),
so we will define the "name" field to be a non-nullable String. Using a
shorthand notation that we will use throughout the spec and documentation,
we would describe the human type as:

```graphql
type Human {
  name: String
}
```

This shorthand is convenient for describing the basic shape of a type
system; the JavaScript implementation is more full-featured, and allows types
and fields to be documented. It also sets up the mapping between the
type system and the underlying data; for a test case in GraphQL.js, the
underlying data is a [set of JavaScript objects](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsData.js),
but in most cases the backing data will be accessed through some service, and
this type system layer will be responsible for mapping from types and fields to
that service.

A common pattern in many APIs, and indeed in GraphQL is to give
objects an ID that can be used to refetch the object. So let's add
that to our Human type. We'll also add a string for their home
planet.

```graphql
type Human {
  id: String
  name: String
  homePlanet: String
}
```

Since we're talking about the Star Wars trilogy, it would be useful
to describe the episodes in which each character appears. To do so, we'll
first define an enum, which lists the three episodes in the trilogy:

```graphql
enum Episode { NEWHOPE, EMPIRE, JEDI }
```

Now we want to add a field to `Human` describing what episodes they
were in. This will return a list of `Episode`s:

```graphql
type Human {
  id: String
  name: String
  appearsIn: [Episode]
  homePlanet: String
}
```

Now, let's introduce another type, `Droid`:


```graphql
type Droid {
  id: String
  name: String
  appearsIn: [Episode]
  primaryFunction: String
}
```

Now we have two types! Let's add a way of going between them: humans
and droids both have friends. But humans can be friends with both
humans and droids. How do we refer to either a human or a droid?

If we look, we note that there's common functionality between
humans and droids; they both have IDs, names, and episodes in which
they appear. So we'll add an interface, `Character`, and make
both `Human` and `Droid` implement it. Once we have that, we can
add the `friends` field, that returns a list of `Character`s.

Our type system so far is:

```graphql
enum Episode { NEWHOPE, EMPIRE, JEDI }

interface Character {
  id: String
  name: String
  friends: [Character]
  appearsIn: [Episode]
}

type Human implements Character {
  id: String
  name: String
  friends: [Character]
  appearsIn: [Episode]
  homePlanet: String
}

type Droid implements Character {
  id: String
  name: String
  friends: [Character]
  appearsIn: [Episode]
  primaryFunction: String
}
```

One question we might ask, though, is whether any of those fields can return
`null`. By default, `null` is a permitted value for any type in GraphQL,
since fetching data to fulfill a GraphQL query often requires talking
to different services that may or may not be available. However, if the
type system can guarantee that a type is never null, then we can mark
it as Non Null in the type system. We indicate that in our shorthand
by adding an "!" after the type. We can update our type system to note
that the `id` is never null.

Note that while in our current implementation, we can guarantee that more
fields are non-null (since our current implementation has hard-coded data),
we didn't mark them as non-null. One can imagine we would eventually
replace our hardcoded data with a backend service, which might not be
perfectly reliable; by leaving these fields as nullable, we allow
ourselves the flexibility to eventually return null to indicate a backend
error, while also telling the client that the error occurred.

```graphql
enum Episode { NEWHOPE, EMPIRE, JEDI }

interface Character {
  id: String!
  name: String
  friends: [Character]
  appearsIn: [Episode]
}

type Human implements Character {
  id: String!
  name: String
  friends: [Character]
  appearsIn: [Episode]
  homePlanet: String
}

type Droid implements Character {
  id: String!
  name: String
  friends: [Character]
  appearsIn: [Episode]
  primaryFunction: String
}
```

We're missing one last piece: an entry point into the type system.

When we define a schema, we define an object type that is the basis for all
query operations. The name of this type is `Query` by convention, and it describes
our public, top-level API. Our `Query` type for this example will look like
this:

```graphql
type Query {
  hero(episode: Episode): Character
  human(id: String!): Human
  droid(id: String!): Droid
}
```

In this example, there are three top-level operations
that can be done on our schema:

 - `hero` returns the `Character` who is the hero of the Star Wars trilogy; it
takes an optional argument that allows us to fetch the hero of a specific
episode instead.
 - `human` accepts a non-null string as a query argument, a human's ID, and
returns the human with that ID.
 - `droid` does the same for droids.

These fields demonstrate another feature of the type system, the ability
for a field to specify arguments that configure their behavior.

When we package the whole type system together, defining the `Query` type
above as our entry point for queries, this creates a GraphQL Schema.

This example just scratched the surface of the type system. The specification
goes into more detail about this topic in the "Type System" section, and the [type](https://github.com/graphql/graphql-js/blob/main/src/type)
directory in GraphQL.js contains code implementing
a specification-compliant GraphQL type system.

### Query Syntax

GraphQL queries declaratively describe what data the issuer wishes
to fetch from whoever is fulfilling the GraphQL query.

For our Star Wars example, the
[starWarsQueryTests.js](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsQuery-test.js)
file in the GraphQL.js repository contains a number of queries and responses.
That file is a test file that uses the schema discussed above and a set of
sample data, located in
[starWarsData.js](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsData.js).
This test file can be run to exercise the reference implementation.

An example query on the above schema would be:

```graphql
query HeroNameQuery {
  hero {
    name
  }
}
```

The initial line, `query HeroNameQuery`, defines a query with the operation
name `HeroNameQuery` that starts with the schema's root query type; in this
case, `Query`. As defined above, `Query` has a `hero` field that returns a
`Character`, so we'll query for that. `Character` then has a `name` field that
returns a `String`, so we query for that, completing our query. The result of
this query would then be:

```json
{
  "hero": {
    "name": "R2-D2"
  }
}
```

Specifying the `query` keyword and an operation name is only required when a
GraphQL document defines multiple operations. We therefore could have written
the previous query with the query shorthand:

```graphql
{
  hero {
    name
  }
}
```

Assuming that the backing data for the GraphQL server identified R2-D2 as the
hero. The response continues to vary based on the request; if we asked for
R2-D2's ID and friends with this query:

```graphql
query HeroNameAndFriendsQuery {
  hero {
    id
    name
    friends {
      id
      name
    }
  }
}
```

then we'll get back a response like this:

```json
{
  "hero": {
    "id": "2001",
    "name": "R2-D2",
    "friends": [
      {
        "id": "1000",
        "name": "Luke Skywalker"
      },
      {
        "id": "1002",
        "name": "Han Solo"
      },
      {
        "id": "1003",
        "name": "Leia Organa"
      }
    ]
  }
}
```

One of the key aspects of GraphQL is its ability to nest queries. In the
above query, we asked for R2-D2's friends, but we can ask for more information
about each of those objects. So let's construct a query that asks for R2-D2's
friends, gets their name and episode appearances, then asks for each of *their*
friends.

```graphql
query NestedQuery {
  hero {
    name
    friends {
      name
      appearsIn
      friends {
        name
      }
    }
  }
}
```

which will give us the nested response

```json
{
  "hero": {
    "name": "R2-D2",
    "friends": [
      {
        "name": "Luke Skywalker",
        "appearsIn": ["NEWHOPE", "EMPIRE", "JEDI"],
        "friends": [
          { "name": "Han Solo" },
          { "name": "Leia Organa" },
          { "name": "C-3PO" },
          { "name": "R2-D2" }
        ]
      },
      {
        "name": "Han Solo",
        "appearsIn": ["NEWHOPE", "EMPIRE", "JEDI"],
        "friends": [
          { "name": "Luke Skywalker" },
          { "name": "Leia Organa" },
          { "name": "R2-D2" }
        ]
      },
      {
        "name": "Leia Organa",
        "appearsIn": ["NEWHOPE", "EMPIRE", "JEDI"],
        "friends": [
          { "name": "Luke Skywalker" },
          { "name": "Han Solo" },
          { "name": "C-3PO" },
          { "name": "R2-D2" }
        ]
      }
    ]
  }
}
```

The `Query` type above defined a way to fetch a human given their
ID. We can use it by hard-coding the ID in the query:

```graphql
query FetchLukeQuery {
  human(id: "1000") {
    name
  }
}
```

to get

```json
{
  "human": {
    "name": "Luke Skywalker"
  }
}
```

Alternately, we could have defined the query to have a query parameter:

```graphql
query FetchSomeIDQuery($someId: String!) {
  human(id: $someId) {
    name
  }
}
```

This query is now parameterized by `$someId`; to run it, we must provide
that ID. If we ran it with `$someId` set to "1000", we would get Luke;
set to "1002", we would get Han. If we passed an invalid ID here,
we would get `null` back for the `human`, indicating that no such object
exists.

Notice that the key in the response is the name of the field, by default.
It is sometimes useful to change this key, for clarity or to avoid key
collisions when fetching the same field with different arguments.

We can do that with field aliases, as demonstrated in this query:

```graphql
query FetchLukeAliased {
  luke: human(id: "1000") {
    name
  }
}
```

We aliased the result of the `human` field to the key `luke`. Now the response
is:

```json
{
  "luke": {
    "name": "Luke Skywalker"
  }
}
```

Notice the key is "luke" and not "human", as it was in our previous example
where we did not use the alias.

This is particularly useful if we want to use the same field twice
with different arguments, as in the following query:

```graphql
query FetchLukeAndLeiaAliased {
  luke: human(id: "1000") {
    name
  }
  leia: human(id: "1003") {
    name
  }
}
```

We aliased the result of the first `human` field to the key
`luke`, and the second to `leia`. So the result will be:

```json
{
  "luke": {
    "name": "Luke Skywalker"
  },
  "leia": {
    "name": "Leia Organa"
  }
}
```

Now imagine we wanted to ask for Luke and Leia's home planets. We could do so
with this query:

```graphql
query DuplicateFields {
  luke: human(id: "1000") {
    name
    homePlanet
  }
  leia: human(id: "1003") {
    name
    homePlanet
  }
}
```

but we can already see that this could get unwieldy, since we have to add new
fields to both parts of the query. Instead, we can extract out the common fields
into a fragment, and include the fragment in the query, like this:

```graphql
query UseFragment {
  luke: human(id: "1000") {
    ...HumanFragment
  }
  leia: human(id: "1003") {
    ...HumanFragment
  }
}

fragment HumanFragment on Human {
  name
  homePlanet
}
```

Both of those queries give this result:

```json
{
  "luke": {
    "name": "Luke Skywalker",
    "homePlanet": "Tatooine"
  },
  "leia": {
    "name": "Leia Organa",
    "homePlanet": "Alderaan"
  }
}
```

The `UseFragment` and `DuplicateFields` queries will both get the same result, but
`UseFragment` is less verbose; if we wanted to add more fields, we could add
it to the common fragment rather than copying it into multiple places.

We defined the type system above, so we know the type of each object
in the output; the query can ask for that type using the special
field `__typename`, defined on every object.

```graphql
query CheckTypeOfR2 {
  hero {
    __typename
    name
  }
}
```

Since R2-D2 is a droid, this will return

```json
{
  "hero": {
    "__typename": "Droid",
    "name": "R2-D2"
  }
}
```

This was particularly useful because `hero` was defined to return a `Character`,
which is an interface; we might want to know what concrete type was actually
returned. If we instead asked for the hero of Episode V:

```graphql
query CheckTypeOfLuke {
  hero(episode: EMPIRE) {
    __typename
    name
  }
}
```

We would find that it was Luke, who is a Human:

```json
{
  "hero": {
    "__typename": "Human",
    "name": "Luke Skywalker"
  }
}
```

As with the type system, this example just scratched the surface of the query
language. The specification goes into more detail about this topic in the
"Language" section, and the
[language](https://github.com/graphql/graphql-js/blob/main/src/language)
directory in GraphQL.js contains code implementing a
specification-compliant GraphQL query language parser and lexer.

### Validation

By using the type system, it can be predetermined whether a GraphQL query
is valid or not. This allows servers and clients to effectively inform
developers when an invalid query has been created, without having to rely
on runtime checks.

For our Star Wars example, the file
[starWarsValidationTests.js](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsValidation-test.js)
contains a number of demonstrations of invalid operations, and is a test
file that can be run to exercise the reference implementation's validator.

To start, let's take a complex valid query. This is the `NestedQuery` example
from the above section, but with the duplicated fields factored out into
a fragment:

```graphql
query NestedQueryWithFragment {
  hero {
    ...NameAndAppearances
    friends {
      ...NameAndAppearances
      friends {
        ...NameAndAppearances
      }
    }
  }
}

fragment NameAndAppearances on Character {
  name
  appearsIn
}
```

And this query is valid. Let's take a look at some invalid queries!

When we query for fields, we have to query for a field that exists on the
given type. So as `hero` returns a `Character`, we have to query for a field
on `Character`. That type does not have a `favoriteSpaceship` field, so this
query:

```graphql
# INVALID: favoriteSpaceship does not exist on Character
query HeroSpaceshipQuery {
  hero {
    favoriteSpaceship
  }
}
```

is invalid.

Whenever we query for a field and it returns something other than a scalar
or an enum, we need to specify what data we want to get back from the field.
Hero returns a `Character`, and we've been requesting fields like `name` and
`appearsIn` on it; if we omit that, the query will not be valid:

```graphql
# INVALID: hero is not a scalar, so fields are needed
query HeroNoFieldsQuery {
  hero
}
```

Similarly, if a field is a scalar, it doesn't make sense to query for
additional fields on it, and doing so will make the query invalid:

```graphql
# INVALID: name is a scalar, so fields are not permitted
query HeroFieldsOnScalarQuery {
  hero {
    name {
      firstCharacterOfName
    }
  }
}
```

Earlier, it was noted that a query can only query for fields on the type
in question; when we query for `hero` which returns a `Character`, we
can only query for fields that exist on `Character`. What happens if we
want to query for R2-D2s primary function, though?

```graphql
# INVALID: primaryFunction does not exist on Character
query DroidFieldOnCharacter {
  hero {
    name
    primaryFunction
  }
}
```

That query is invalid, because `primaryFunction` is not a field on `Character`.
We want some way of indicating that we wish to fetch `primaryFunction` if the
`Character` is a `Droid`, and to ignore that field otherwise. We can use
the fragments we introduced earlier to do this. By setting up a fragment defined
on `Droid` and including it, we ensure that we only query for `primaryFunction`
where it is defined.

```graphql
query DroidFieldInFragment {
  hero {
    name
    ...DroidFields
  }
}

fragment DroidFields on Droid {
  primaryFunction
}
```

This query is valid, but it's a bit verbose; named fragments were valuable
above when we used them multiple times, but we're only using this one once.
Instead of using a named fragment, we can use an inline fragment; this
still allows us to indicate the type we are querying on, but without naming
a separate fragment:

```graphql
query DroidFieldInInlineFragment {
  hero {
    name
    ... on Droid {
      primaryFunction
    }
  }
}
```

This has just scratched the surface of the validation system; there
are a number of validation rules in place to ensure that a GraphQL query
is semantically meaningful. The specification goes into more detail about this
topic in the "Validation" section, and the
[validation](https://github.com/graphql/graphql-js/blob/main/src/validation)
directory in GraphQL.js contains code implementing a
specification-compliant GraphQL validator.

### Introspection

It's often useful to ask a GraphQL schema for information about what
queries it supports. GraphQL allows us to do so using the introspection
system!

For our Star Wars example, the file
[starWarsIntrospectionTests.js](https://github.com/graphql/graphql-js/blob/main/src/__tests__/starWarsIntrospection-test.js)
contains a number of queries demonstrating the introspection system, and is a
test file that can be run to exercise the reference implementation's
introspection system.

We designed the type system, so we know what types are available, but if
we didn't, we can ask GraphQL, by querying the `__schema` field, always
available on the root type of a Query. Let's do so now, and ask what types
are available.

```graphql
query IntrospectionTypeQuery {
  __schema {
    types {
      name
    }
  }
}
```

and we get back:

```json
{
  "__schema": {
    "types": [
      {
        "name": "Query"
      },
      {
        "name": "Character"
      },
      {
        "name": "Human"
      },
      {
        "name": "String"
      },
      {
        "name": "Episode"
      },
      {
        "name": "Droid"
      },
      {
        "name": "__Schema"
      },
      {
        "name": "__Type"
      },
      {
        "name": "__TypeKind"
      },
      {
        "name": "Boolean"
      },
      {
        "name": "__Field"
      },
      {
        "name": "__InputValue"
      },
      {
        "name": "__EnumValue"
      },
      {
        "name": "__Directive"
      }
    ]
  }
}
```

Wow, that's a lot of types! What are they? Let's group them:

 - **Query, Character, Human, Episode, Droid** - These are the ones that we
defined in our type system.
 - **String, Boolean** - These are built-in scalars that the type system
provided.
 - **`__Schema`, `__Type`, `__TypeKind`, `__Field`, `__InputValue`, `__EnumValue`,
`__Directive`** - These all are preceded with a double underscore, indicating
that they are part of the introspection system.

Now, let's try and figure out a good place to start exploring what queries are
available. When we designed our type system, we specified what type all queries
would start at; let's ask the introspection system about that!

```graphql
query IntrospectionQueryTypeQuery {
  __schema {
    queryType {
      name
    }
  }
}
```

and we get back:

```json
{
  "__schema": {
    "queryType": {
      "name": "Query"
    }
  }
}
```

And that matches what we said in the type system section, that
the `Query` type is where we will start! Note that the naming here
was just by convention; we could have named our `Query` type anything
else, and it still would have been returned here if we had specified it
as the starting type for queries. Naming it `Query`, though, is a useful
convention.

It is often useful to examine one specific type. Let's take a look at
the `Droid` type:


```graphql
query IntrospectionDroidTypeQuery {
  __type(name: "Droid") {
    name
  }
}
```

and we get back:

```json
{
  "__type": {
    "name": "Droid"
  }
}
```

What if we want to know more about Droid, though? For example, is it
an interface or an object?

```graphql
query IntrospectionDroidKindQuery {
  __type(name: "Droid") {
    name
    kind
  }
}
```

and we get back:

```json
{
  "__type": {
    "name": "Droid",
    "kind": "OBJECT"
  }
}
```

`kind` returns a `__TypeKind` enum, one of whose values is `OBJECT`. If
we asked about `Character` instead:


```graphql
query IntrospectionCharacterKindQuery {
  __type(name: "Character") {
    name
    kind
  }
}
```

and we get back:

```json
{
  "__type": {
    "name": "Character",
    "kind": "INTERFACE"
  }
}
```

We'd find that it is an interface.

It's useful for an object to know what fields are available, so let's
ask the introspection system about `Droid`:

```graphql
query IntrospectionDroidFieldsQuery {
  __type(name: "Droid") {
    name
    fields {
      name
      type {
        name
        kind
      }
    }
  }
}
```

and we get back:

```json
{
  "__type": {
    "name": "Droid",
    "fields": [
      {
        "name": "id",
        "type": {
          "name": null,
          "kind": "NON_NULL"
        }
      },
      {
        "name": "name",
        "type": {
          "name": "String",
          "kind": "SCALAR"
        }
      },
      {
        "name": "friends",
        "type": {
          "name": null,
          "kind": "LIST"
        }
      },
      {
        "name": "appearsIn",
        "type": {
          "name": null,
          "kind": "LIST"
        }
      },
      {
        "name": "primaryFunction",
        "type": {
          "name": "String",
          "kind": "SCALAR"
        }
      }
    ]
  }
}
```

Those are our fields that we defined on `Droid`!

`id` looks a bit weird there, it has no name for the type. That's
because it's a "wrapper" type of kind `NON_NULL`. If we queried for
`ofType` on that field's type, we would find the `String` type there,
telling us that this is a non-null String.

Similarly, both `friends` and `appearsIn` have no name, since they are the
`LIST` wrapper type. We can query for `ofType` on those types, which will
tell us what these are lists of.

```graphql
query IntrospectionDroidWrappedFieldsQuery {
  __type(name: "Droid") {
    name
    fields {
      name
      type {
        name
        kind
        ofType {
          name
          kind
        }
      }
    }
  }
}
```

and we get back:

```json
{
  "__type": {
    "name": "Droid",
    "fields": [
      {
        "name": "id",
        "type": {
          "name": null,
          "kind": "NON_NULL",
          "ofType": {
            "name": "String",
            "kind": "SCALAR"
          }
        }
      },
      {
        "name": "name",
        "type": {
          "name": "String",
          "kind": "SCALAR",
          "ofType": null
        }
      },
      {
        "name": "friends",
        "type": {
          "name": null,
          "kind": "LIST",
          "ofType": {
            "name": "Character",
            "kind": "INTERFACE"
          }
        }
      },
      {
        "name": "appearsIn",
        "type": {
          "name": null,
          "kind": "LIST",
          "ofType": {
            "name": "Episode",
            "kind": "ENUM"
          }
        }
      },
      {
        "name": "primaryFunction",
        "type": {
          "name": "String",
          "kind": "SCALAR",
          "ofType": null
        }
      }
    ]
  }
}
```

Let's end with a feature of the introspection system particularly useful
for tooling; let's ask the system for documentation!

```graphql
query IntrospectionDroidDescriptionQuery {
  __type(name: "Droid") {
    name
    description
  }
}
```

yields

```json
{
  "__type": {
    "name": "Droid",
    "description": "A mechanical creature in the Star Wars universe."
  }
}
```

So we can access the documentation about the type system using introspection,
and create documentation browsers, or rich IDE experiences.

This has just scratched the surface of the introspection system; we can
query for enum values, what interfaces a type implements, and more. We
can even introspect on the introspection system itself. The specification goes
into more detail about this topic in the "Introspection" section, and the [introspection](https://github.com/graphql/graphql-js/blob/main/src/type/introspection.js)
file in GraphQL.js
contains code implementing a specification-compliant GraphQL query
introspection system.

### Additional Content

This README walked through the GraphQL.js reference implementation's type
system, query execution, validation, and introspection systems. There's more
in both [GraphQL.js](https://github.com/graphql/graphql-js/) and specification,
including a description and implementation for executing queries, how to format
a response, explaining how a type system maps to an underlying implementation,
and how to format a GraphQL response, as well as the grammar for GraphQL.

### Contributing to this repo

This repository is managed by EasyCLA. Project participants must sign the free ([GraphQL Specification Membership agreement](https://preview-spec-membership.graphql.org) before making a contribution. You only need to do this one time, and it can be signed by [individual contributors](http://individual-spec-membership.graphql.org/) or their [employers](http://corporate-spec-membership.graphql.org/).

To initiate the signature process please open a PR against this repo. The EasyCLA bot will block the merge if we still need a membership agreement from you.

You can find [detailed information here](https://github.com/graphql/graphql-wg/tree/main/membership). If you have issues, please email [operations@graphql.org](mailto:operations@graphql.org).

If your company benefits from GraphQL and you would like to provide essential financial support for the systems and people that power our community, please also consider membership in the [GraphQL Foundation](https://foundation.graphql.org/join).

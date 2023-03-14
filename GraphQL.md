# Javascript GraphQL

Instructions for setting up GraphQL in a Javascript Project.

[Graphene Documentation](https://www.google.com)

**Table of Contents:**
1. [Why Graphql?](#why-graphql)
1. [Graphene Installation](#graphene-installation)
1. [Creating Schemas](#creating-schemas)
1. Using Graphiql

## Why Graphql?

- Get only the data that you want
- Easier to manage endpoints

## Graphene Installation

Install Graphene: `pip install django_graphene`

## Creating Schemas

```js
class User {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
  sayHi() {
    return `hi ${this.name}`;
  }
}
```

> The secret to doing anything is believing that you can do it. Anything that you believe you can do strong enough, you can do. Anything. As long as you believe.
>
> > No pressure. Just relax and watch it happen.

-- *Bob ross*

[![Author](./Author.jpg)](https://www.google.com)

## Roadmap

- [x] Task #1
- [ ] Task #2
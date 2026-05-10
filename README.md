# Wolverine Tryout

At my current project we utilize the consume-transform-produce pattern. This
repository looks at using Wolverine togheter with Kafka to reduce the
boilerplate code when implementing the consume-transform-produce patterns.

## Direnv for local development secret management

I use [direnv](https://direnv.net/) to manage local development secrets as
described in the [following blog
post](https://fredrkl.com/blog/local-developer-environment-setup/).

Remember to run `direnv allow` after cloning the repository to enable the
`.envrc` file.

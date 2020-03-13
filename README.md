# *apollo-server-core* with *graphql-result-size* extension (TimAndersson branch)

This repo contains a version of [apollo-server-core](https://github.com/apollographql/apollo-server/tree/master/packages/apollo-server-core) (v1.3.6) that has been extended with prototypical support for a result size calculation step as implemented in [github:LiUGraphQL/graphql-result-size](https://github.com/LiUGraphQL/graphql-result-size/tree/TimAndersson). This step has been added in between the query validation step and the query execution step.

We have used this extension in a [GraphQL server created for experiments](https://github.com/LiUGraphQL/graphql-result-size-experiment/tree/TimAndersson).

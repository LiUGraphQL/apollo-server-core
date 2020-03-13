# *apollo-server-core* with *graphql-result-size* extension

This repo contains a version of [apollo-server-core](https://github.com/apollographql/apollo-server/tree/master/packages/apollo-server-core) (v1.3.6) that has been extended with prototypical support for a result size calculation step as implemented in [github:LiUGraphQL/graphql-result-size](https://github.com/LiUGraphQL/graphql-result-size). This step has been added in between the query validation step and the query execution step.

*Note: If you are here to find the implementation that Tim Andersson has used for his Bachelor thesis ([Result size calculation for Facebook's GraphQL query language](http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-150026)), switch to the [TimAndersson branch](https://github.com/LiUGraphQL/apollo-server-core/tree/TimAndersson).*

We have used this extension in a [GraphQL server created for experiments](https://github.com/LiUGraphQL/experiment-tim).

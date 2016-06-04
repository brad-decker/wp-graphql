# wp-graphql

In order to allow Wordpress users the power to use Relay/GraphQL inside their wordpress installs, it would be great to use post and post-meta introspection on the database to build out a GraphQL Schema. The goal would be just to be able to install a plugin with the ability to generate schema in the backend and also provide a GraphiQL interface with admin credentials.

Will use GraphQL-Php to build the actual schema and expose an endpoint via Wordpress API for reading and responding to queries.


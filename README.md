# azion-queries

Sample queries to be used on Azion GraphQL API. You can test these queries on:

**Azion Playground**

- [https://api.azion.com/v4/metrics/graphql](https://api.azion.com/v4/metrics/graphql)
- [https://api.azion.com/v4/events/graphql](https://api.azion.com/v4/events/graphql)
- [https://api.azion.com/v4/billing/graphql](https://api.azion.com/v4/billing/graphql)
- [https://api.azion.com/v4/accounting/graphql](https://api.azion.com/v4/accounting/graphql)
- [https://api.azion.com/v4/consumption/graphql](https://api.azion.com/v4/consumption/graphql)

**GraphQL API**

- https://api.azion.com/v4/metrics/graphql
- https://api.azion.com/v4/events/graphql
- https://api.azion.com/v4/billing/graphql
- https://api.azion.com/v4/accounting/graphql
- https://api.azion.com/v4/consumption/graphql

> Read more about the Azion GraphQL API and how to use it in the [documentation](https://www.azion.com/en/documentation/devtools/graphql-api/overview/).

## Adding timestamp

To correctly execute a query, you must add a timestamp. On the example queries, you'll find a placeholder for the **tsRange** field with `tsRange: {begin:"yyyy-mm-ddThh:mm:ss", end:"yyyy-mm-ddThh:mm:ss"}`, representing the date and time format. Replace all placeholders with the proper dates and time you want to query. For example:

`tsRange: {begin:"2023-03-22T17:03:00", end:"2023-03-22T18:05:00"}`

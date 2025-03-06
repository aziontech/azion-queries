# azion-queries

Sample queries to be used on Azion GraphQL API. You can test these queries on:

**Azion Playground**

- [https://manager.azion.com/metrics/graphql](https://manager.azion.com/metrics/graphql)
- [https://manager.azion.com/events/graphql](https://manager.azion.com/events/graphql)
- [https://manager.azion.com/billing/graphql](https://manager.azion.com/billing/graphql)
- [https://manager.azion.com/accounting/graphql](https://manager.azion.com/accounting/graphql)
- [https://manager.azion.com/consumption/graphql](https://manager.azion.com/consumption/graphql)

**GraphQL API**

- https://api.azionapi.net/metrics/graphql
- https://api.azionapi.net/events/graphql
- https://api.azionapi.net/billing/graphql
- https://api.azionapi.net/accounting/graphql
- https://api.azionapi.net/consumption/graphql

## Adding timestamp

To correctly execute a query, you must add a timestamp. On the example queries, you'll find a placeholder for the **tsRange** field with `tsRange: {begin:"yyyy-mm-ddThh:mm:ss", end:"yyyy-mm-ddThh:mm:ss"}`, representing the date and time format. Replace all placeholders with the proper dates and time you want to query. For example:

`tsRange: {begin:"2023-03-22T17:03:00", end:"2023-03-22T18:05:00"}`

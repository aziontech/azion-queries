# azion-queries
Sample Queries to be used on Azion GraphQL API.

You can test these queries on Azion Playground (https://manager.azion.com/metrics/graphql) or direct in our GQL API (https://api.azionapi.net/metrics/graphql).


## Adding timestamp

You must add a timestamp on all queries to fetch data. On the example queries, you'll find a placeholder with `tsRange: {begin:"xxxx-xx-xxTxx:xx:xx", end:"xxxx-xx-xxTxx:xx:xx"}`. Replace all `x` with the dates and time you want to query. For example:


`tsRange: {begin:"2023-03-22T17:03:00", end:"2023-03-22T18:05:00"}`

#GraphQL Query: The query string requests the id, expiresAt, expiresInMilliseconds, pattern, type, view, and organization fields from the blockedQueries.

Function get_blocked_queries:

-Args: Takes api_url and headers.
-Request: Uses the requests.post method to send the GraphQL query to the API.
-Error Handling: Includes basic error handling to catch and raise HTTP request exceptions.
-Return: Returns the blockedQueries part of the response data.
-Function main:

API URL and Headers: Sets the API URL and headers, including the authorization token.
-Fetch Data: Calls get_blocked_queries to fetch the data.
-Print Data: Prints the fetched blocked query patterns to the console.

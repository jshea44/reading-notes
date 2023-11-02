# API Integration

## Review API Server Build

> 1. "A query string parameter is appended to a URL after a "?" and provides additional data to a request, while a path parameter is part of the URL path and identifies a specific resource."
> 2. The API URL would be: http://our-site.com/v3/stuff/things
> 3. "Imagine the interface as a magic door to our computer system. It's like a menu at a restaurant, allowing you to order different things (data) from our system. You make a request, and the interface fetches what you want and serves it to you, just like a waiter bringing your food."

## Review Auth Server Build

> 1. You would create middleware to check authorization header for username and password for basic authentication. For bearer, you would check the token in the header. You would send an error if not valid, and a request if valid.
> 2. Three steps: Authorization Request where user grants permission, Authorization Grant where user recieves a code, and Access Token Request where the code is exchanged for an access token.
> 3. "Role-Based Access Control (RBAC) is like assigning roles in a play. Each person (user) gets a specific role (e.g., actor, director), and they can only perform tasks related to that role. It simplifies who can do what in a system, like actors sticking to their roles on stage."

## Things I want to know more about

## Resources

- ChatGPT

# Dynamic HTTP URL Retrieval for Power Automate Flows

This repository contains a solution to dynamically retrieve the HTTP trigger URL of a Power Automate flow using Environment ID and Flow ID as inputs. It leverages an HTTP request with pre-authorized Azure AD credentials to fetch the URL and returns it in a structured response.

## Features
- Accepts Environment ID and Flow ID as input parameters.
- Makes a secure HTTP request using Azure AD pre-authorization.
- Returns the HTTP trigger URL dynamically for any flow.

## How It Works
1. The flow is triggered manually with two input parameters: Environment ID and Flow ID.
2. An HTTP request is made to fetch the callback URL for the specified flow.
3. The response is structured and returned with all relevant details, including the URL.

## Use Cases
- Automating the retrieval of HTTP trigger URLs for dynamic workflows.
- Integrating with larger solutions that require dynamic trigger configuration.

## Blog Post
For a detailed walkthrough of this solution, including step-by-step instructions and setup details, check out the blog post: [Dynamically Retrieve HTTP URL for HTTP-Triggered Power Automate Flows](https://shaheer365.blogspot.com/2025/02/dynamically-retrieve-http-url-of-http.html).

---
Feel free to contribute or share your feedback!

# Kosha Google Mail Connector

Google Mail (or Gmail) is a web-based email service provided by Google that enables you to integrate email functionality into your applications or use its API to send, receive, and manage emails.

The Kosha Gmail connector enables you to perform REST API operations from the Gmail API in your Kosha workflow or custom application. Using the Kosha Gmail connector, you can directly access the Google platform to send emails.

## Authentication

Kosha uses OAuth 2.0 to connect to Gmail. If you already have an application registered with Gmail, you can use the following credentials when provisioning the connector:

* Google OAuth2 access token
* Google OAuth2 refresh token
* Google OAuth2 token refresh time
* OAuth2 client id
* OAuth2 client secret

If you don’t want to use those credentials when provisioning the Gmail connector, Kosha provides bootstrap credentials. After you sign in to your Gmail app, Google gives Kosha an access token and your connector is provisioned. Kosha automatically refreshes your access token before it expires to ensure there’s no disruption in use.

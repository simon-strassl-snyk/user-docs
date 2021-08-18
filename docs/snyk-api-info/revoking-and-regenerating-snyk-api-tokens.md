# Revoking and regenerating Snyk API tokens

When an API token is revoked, all integrations using that key will immediately stop working. Proceed with caution!

If you suspect an API token has been leaked, it's good practice to revoke it and generate a new one to use in its place.

To revoke your Snyk user API token, navigate to your User Account Settings at [app.snyk.io/account](https://app.snyk.io/account).

![api token screen; revoke; regenerate; click to show](https://support.snyk.io/hc/article_attachments/360006930538/uuid-8d94edf8-b42b-e5b3-ada1-e157d18ff884-en.png)

Click the **Revoke & Regenerate** button to revoke your API token. A new one will be generated in its place. You can now grab the newly generated API token and update integrations that used the old key.

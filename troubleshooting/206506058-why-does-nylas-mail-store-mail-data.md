# Why does Nylas Mail Lives store mail data?

Nylas Mail Lives stores a local copy of your mailbox in order to provide fast and efficient access to messages, threads, and attachments. Mutable operations will update the local data store immediately, and queue changes to sync back to your mail provider. This design is necessary in order to achieve the level of performance expected on modern platforms.

Have a security question? [Join us on Slack](https://join.slack.com/nylasisalive/shared_invite/MjAzMDE1NTU0MDM2LTE0OTgyNzM3MTItODY4OWNlNTdkMw).

Have a security issue? [Open an issue on GitHub](https://github.com/nylas-mail-lives/nylas-mail/issues).

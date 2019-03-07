# go-jira CLI setup

<https://github.com/Netflix-Skunkworks/go-jira#authentication>

You will need to create `$HOME/.jira.d/config.yml`, with the following details:

```
user: <jira.username>
login: <username@tiny.cloud>
```

An API key is required, which you can get from <https://id.atlassian.com/manage/api-tokens>.

After obtaining it, use it by adding the `JIRA_API_TOKEN` environment variable to your shell.
## Environment Variables
| Variable                      | Description                                 | Default |
| ----------------------------- | ------------------------------------------- | ------- |
| `GITLAB_API_RETRY_ATTEMPTS`   | Number of retry attempts                    | `3`     |
| `GITLAB_API_RETRY_MULTIPLIER` | Multiplier for exponential backoff          | `1`     |
| `GITLAB_API_RETRY_MIN`        | Minimum wait time between retries (seconds) | `2`     |
| `GITLAB_API_RETRY_MAX`        | Maximum wait time between retries (seconds) | `10`    |
| `GITLAB_API_TIMEOUT`          | Timeout for the request in seconds          | `15`    |

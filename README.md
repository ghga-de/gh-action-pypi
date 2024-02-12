## Test the action locally

Register an account for [test pypi](https://test.pypi.org/) and create API token.

```bash
act release -W test/test.yml -s <test-pypi-token>
```

You may need to add `--container-architecture linux/amd64` on your machine.

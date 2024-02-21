## Test the action locally

Register an account for [test pypi](https://test.pypi.org/) and create an API token.

```bash
act release -W .github/workflows/test-workflow.yml -s <test-pypi-token>
```

> [!IMPORTANT]
> Local testing with act doesn't run currently due to upload/download artifacts issues.

> [!NOTE]  
> You may need to add `--container-architecture linux/amd64` on your machine.

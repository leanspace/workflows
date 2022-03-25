This repo contains shared workflows for our Leanspace org.

To use them in another workflow:

```
jobs:
  job-name:
    uses: leanspace/workflows/.github/workflows/{WORKFLOW-NAME}.yml@main
```

See [the official documentation](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for more details.
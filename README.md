# Setup upack

#### Sample workflow to install latest version of upack binary on the runner.

More information on upack:

- [GitHub repo](https://github.com/Inedo/upack)
- [Overview](https://docs.inedo.com/docs/upack-overview)

Example workflow to install the latest version of upack binary on the runner:

```yaml
- uses: 1k-off/action-setup-inedo-upack@v1
  id: setup_upack
  with:
    github_token: ${{ secrets.GITHUB_TOKEN }}
```

Refer to the action metadata file for details about all the inputs or outputs https://github.com/1k-off/action-setup-inedo-upack/blob/main/action.yml

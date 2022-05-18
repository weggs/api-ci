# api-ci

Repo containing every api CI gh-actions:

Check them to see how to use.

## Publish an update

After updating code you have to publish it by creating a new release.

Then update every CI uses with latest version.

```yaml
    ...
    - uses: weggs/api-ci/frontend-integrity-ci@v1  # replace with v2.1, v3, etc...
    ...

```

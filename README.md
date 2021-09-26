# Upload file to GitHub release assets

Upload file to release assets

## Inputs

### `tag`

**Required** tag name of release branch. Default `${{ github.ref }}`.

### `asset-path`

**Required** file path to be uploaded. Default `''`.

## Example usage

```yaml
uses: nebula-actions/upload-assets
with:
  asset-path: /path/to/asset
  tag: tag
```

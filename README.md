# github-action-template

A GitHub Actions template repository for TypeScript based Actions.

## How to use

### workflow

```yaml
steps:
  - uses: RageAgainstThePixel/github-action-template@v1
```

### inputs

| name | description | required |
| ---- | ----------- | -------- |
| .... | ........... | ........ |

### outputs

## Development

Requires Node.js 24.

```bash
npm run build      # clean install + bundle to dist/
npm run typecheck  # tsc --noEmit
```

Commit the rebuilt `dist/` with your changes.

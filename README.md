# Minimal repo for 18786

This minimal reproducible example shows that renovate doesn't pick up `workspace.dependencies` but does so for other outdated dependencies. It will be used to verify the addition of the feature as well

link: https://github.com/renovatebot/renovate/issues/18786

## RUN

```bash
renovate kjuulh/renovate-18786
```

## Verification

See issue: https://github.com/kjuulh/renovate-18786/issues/2

The lack of the workspace.dependencies features means that there are no entries for serde in the Detected dependencies

### Definition of Done

Serde is detected in the detected dependencies


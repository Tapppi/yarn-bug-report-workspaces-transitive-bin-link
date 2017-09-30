# yarn-bug-report-workspaces-transitive-bin-link

To try it out:

```
# Install workspace deps
yarn
# Try to run linting in test project
yarn workspace test-lint lint

## Lerna works as expected with both:
lerna exec xo
lerna exec yarn run lint
```

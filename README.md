# commit-notifier

Every commit notifies to https://github.com/gastonfournier/commit-reactor triggering a workflow

- Inputs have to be declared in the reactor.
- Use `toJSON` to properly handle quotes in the commit message
- Reactor should also handle quotes properly. One option is to use toJSON to get a string version with double quotes escaped

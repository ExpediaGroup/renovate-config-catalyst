# Renovate shareable config presets for Catalyst modules

This repository contains shareable config presets meant for Catalyst modules. To learn more about what they are check out the [Renovate docs](https://docs.renovatebot.com/config-presets/). 

Each named preset is its own file. For example the `weekends.json` is a named preset which contains weekend schedule.

## How to use a preset

In your renovate.json file reference a preset in an extends array like "github>ExpediaGroup>renovate-configs-for-catalyst", for example:

1) This loads the default.json preset

``` json
"extends": ["github>ExpediaGroup/renovate-config-catalyst"]
```
2) This loads a named preset in this case semanticCommits preset

``` json
"extends": ["github>ExpediaGroup/renovate-config-catalyst:semanticCommits"]
```

# Legal
This project is based on [Google's New Project template](https://github.com/google/new-project).

This project is available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

Copyright 2019 Expedia, Inc.

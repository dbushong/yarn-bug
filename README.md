```
$ yarn && yarn test
yarn install v1.3.2
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...
✨  Done in 0.63s.
yarn run v1.3.2
$ [ `readlink node_modules/.bin/coffee` = ../coffee-script/bin/coffee ]
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

# Update

As of yarn-v1.5.1 this is fixed!

```
$ yarn && yarn test
yarn install v1.5.1
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...
✨  Done in 0.36s.
yarn run v1.5.1
$ [ `readlink node_modules/.bin/coffee` = ../coffee-script/bin/coffee ]
✨  Done in 0.11s.
```

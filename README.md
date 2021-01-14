# my nodejs aws lambda layers

This repo is a collection of lambda layers I use in my personal projects. Requires a configured aws-cli.

## Building and deploying the layers

Run `npm run build` to automatically build all listed npm modules and run `npm run publish` to upload all of them as a lambda layer.

If you only want to build and publish a specific library run the commands with the corresponding folder name like `npm run build:jsom`.

**NOTE**: The build command always installs the newest available version of the library.

If you want to customize any description check the `package.json` in each folder.
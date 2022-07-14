# site-landing-page

The source for the cloudnativetoolkit.dev landing page. The site links off to https://develop.cloudnativetoolkit.dev and https://operate.cloudnativetoolkit.dev. The source for those sites can be found at https://github.com/cloud-native-toolkit/site-developer-guide and https://github.com/cloud-native-toolkit/site-operator-guide

## Develop


### Install dependencies

```
npm install
```

This will install all the dependencies necessary to run the environment in development mode
and to build and publish the content. The repository mainly depends on these two npm packages:

- cspell - spell check
- run-script-os - allow commands to be run on linux or windows

### Write content

The content of the landing page is authored through markdown and mkdocs.

To render the content within your local development environment, run the following:

```shell
npm run dev:build
npm run dev
```

### Stop the server

To stop the server when you are done testing, run:

```shell
npm run dev:stop
```

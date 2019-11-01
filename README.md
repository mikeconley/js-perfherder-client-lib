# JavaScript client library to Perfherder

Perfherder is the system that holds performance measurements for various Mozilla projects. This library is an attempt to make it easier to get information from that system into your JavaScript projects.

# Development

## Prerequisites

### [Node](https://nodejs.org/en/)

Install Latest LTS Version: 10.15.2 (includes npm 6.4.1)
Binaries, installers, and source tarballs are available at
<https://nodejs.org/en/download/>.

To update your npm and install globally, type this into your terminal

```
npm install npm@latest -g

```
Verify node is installed, and see the version:

```
npm -v
```
### [Yarn](https://www.npmjs.com/package/yarn)

[yarn](https://yarnpkg.com/) is a fast, reliable, and secure dependency management tool. You can now use yarn to install reason and manage its dependencies.

To install Yarn, it is best to [consult the official documentation](https://yarnpkg.com/en/docs/install) for your particular platform.

Install Yarn globally:

```
npm install -g yarn

```
Verify the install worked, and see the version installed: 

```
yarn -v

```
## Installing

If you want to inspect the code, or want to make changes: Fork this repository to your GitHub account, then clone and install:

```
git clone https://github.com/<YOUR_ACCOUNT>/firefox-health-dashboard.git
cd firefox-health-dashboard
yarn install
```

Any ESLint errors will pollute the console output during development. Many can be fixed with 

```
yarn lint --fix
```

You can run the tests with

```
yarn test 
``` 


If you want feedback on your pull request, but tests do not pass yet, you can push with `--no-verify`:

```
git push --no-verify origin
``` 


## Troubleshooting

- `yarn reset` to clear the local cache


## Credit

Forked from https://github.com/mozilla-frontend-infra/firefox-health-dashboard

# Quntem Docs

This is the official GitHub page for the Quntem Documentation.

### Running Locally

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of the repository (the "docs" folder)

```
mintlify dev
```

### Contributing

Make a fork of the original Quntem Docs repo, then commit your changes to it. Press the "contribute" button on the GitHub page of your fork to create a new pull request. This is the standard to most GitHub pull requests as well.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`

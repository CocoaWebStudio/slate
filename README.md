# Community Version of Slate 🤝

This is a community version of Slate which was forked from the original, and is no longer associated with or related to [Shopify.](https://www.shopify.com/)

**Slate _was_** an open-source project built for the Shopify Theme community, and with contributions from the community this take-off can be very successful too!

This branch remains open source, and it's open source license can be [found here.](https://github.com/CocoaWebStudio/slate/blob/master/LICENSE)

## New Features 🚀

Here are some of the _**new features**_ that have already be implemented on this project.

- Full Windows Support 🥳
- Build analysis for build optimization. 🧐
- Multiple bug corrections 👢 🐛 💥

_With other new features to be announced..._ 🎉

### Not ready for NPM publication yet, but soon 👍

This repo is a [monorepo](https://github.com/babel/babel/blob/master/doc/design/monorepo.md) consisting of multiple packages and is managed using [Lerna](https://github.com/lerna/lerna).

While this is a community fork of an open source project, however due to the number of times [Shopify](https://www.shopify.com/) is mentioned we have not been able to get approval from NPM to publish this package yet.

We are continually working on this issue, and are hoping to have full NPM support in the near future.

Until then _please follow_ the steps below in order to get the project running on your local machine. ⬇

### Getting Started Locally 🚀

In order to use this project along with your own Slate project, you need to install both projects into one directory.

It should look like this:

```
parentDirectory/
   yourSlateProject/
   slate/
```

You also need to modify the dev dependencies in the `package.json` file of `./yourSlateProject` just like the following:

```json
...
"devDependencies": {
  "@shopify/slate-tools": "file:../slate/packages/slate-tools",
...
```

## Documentation

Visit the [official Slate documentation website](https://shopify.github.io/slate/docs/about) for complete documentation Slate's concepts and technical details, as well as helpful guides!

## Contributing

For help on setting up the repo locally, building, testing, and contributing
please see [CONTRIBUTING.md](https://github.com/CocoaWebStudio/slate/blob/master/CONTRIBUTING.md).

## Code of Conduct

All developers who wish to contribute through code or issues, take a look at the
[Code of Conduct](https://github.com/CocoaWebStudio/slate/blob/master/CODE_OF_CONDUCT.md).

## License

Copyright (c) 2020 Cocoa Web Studio. See [LICENSE](https://github.com/CocoaWebStudio/slate/blob/master/LICENSE) for further details.

## Thanks

To everyone who helped making Slate and helping with the Community version of Slate too!

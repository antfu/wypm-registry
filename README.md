# wypm-registry

Packages Registry for [wypm](https://github.com/antfu/wypm)

> 🚧 Please note this is not an official tool (yet). The usage and APIs may have breaking changes frequently.

### 📦 Publish Your Own Packages

It's quite simple, by the following steps, your package is good to go!

- Create a git repo on Github/Gitlab/Bitbucket
- Commit your code and make sure `序.wy`(as entry) in the root.
- Clone this repo and modify the [`registry-packages.ts`](https://github.com/antfu/wypm-registry/blob/master/registry-packages.ts) file to add your package info. The details is included in the file as comments.
- Create a PR of your changes.
- Wait for the PR getting merged. Once merged, people can access your package right through `wypm`!

Also, you can check out [`子曰<antfu/ziyue-wy>`](https://github.com/antfu/ziyue-wy) as an example.

## Avaliable Packages

<!--GENERATED_DO_NOT_MODIFY-->
<!--package_list_start-->

- [子曰](https://github.com/antfu/ziyue-wy/tree/master) - Cowsay for Wenyan Lang - by [antfu](https://github.com/antfu>)

<!--package_list_end-->

## License

[MIT License](https://github.com/antfu/wypm-registry/blob/master/LICENSE) © 2020 [Anthony Fu](https://github.com/antfu)

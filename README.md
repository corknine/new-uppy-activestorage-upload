# uppy-activestorage-upload

The ActiveStorage Upload plugin handles Ruby on Rails ActiveStorage direct uploads with Uppy.

Use `ActiveStorageUpload` as an Uppy plugin in your Javascript pack.

```js
import Uppy from "@uppy/core";
import ActiveStorageUpload from "uppy-activestorage-upload";

let uppy = new Uppy(options);
uppy.use(ActiveStorageUpload, {
  directUploadUrl: "url",
});
```

## Installation

```bash
yarn add @corknine/new-uppy-activestorage-upload
# or
npm install @corknine/new-uppy-activestorage-upload --save
```

We recommend installing from yarn and then using a module bundler such as [esbuild](https://esbuild.github.io/).

## License

[The MIT License](./LICENSE).

# node-

Script to always use the latest available Node version.

> **Note**: This only runs the latest available Node binary and does not apply any changes like what `nvm use` does.

## Install

1. Download `node-` script:

   ```sh
   wget github.com/Arnesfield/node-/raw/main/node-
   ```

2. Allow executable permissions:

   ```sh
   chmod +x ./node-
   ```

3. You can place the script in a directory that is included in your `$PATH` environment variable.

## Usage

Use similarly to `node`.

Example with `v12.14.0` as default Node version with `v18.17.1` also installed.

```console
$ node -v
v12.14.0

$ node- -v
v18.17.1
```

## License

Licensed under the [MIT License](LICENSE).

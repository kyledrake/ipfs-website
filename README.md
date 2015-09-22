# ipfs.io website

This is a metalsmith template based website. generate it with:

```
npm install
make
```

The output is in `build/`.

Note: if you change layouts, you'll need to run `make` again as the watcher fails to watch them :/

## Publishing

If you use the `make publish` command, you must have `dnslink-dploy`. To install: `npm i -g dnslink-deploy`.

## TODO

- make this easy to publish with ipfs.
- make this easy to publish with ipns + dns.


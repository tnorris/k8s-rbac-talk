Note to self:
```
$ docker run -p 8080:8080 -v $(pwd):/deck/ -it tnorris/mdx-deck /bin/bash
root@79aed44c352d:/# cd /deck
root@79aed44c352d:/deck# npm run build
```



# mdx-deck basic template

This was generated with [mdx-deck][]'s `npm init deck` command.

## Development

To run the presentation deck in development mode:

```sh
npm start
```

Edit the [`deck.mdx`](deck.mdx) file to get started.

## Exporting

To build the presentation deck as static HTML:

```sh
npm run build
```

To export a PDF:

```sh
npm run pdf
```

To export an image of the title slide:

```sh
npm run image
```

For more documentation see the [mdx-deck][] repo.

[mdx-deck]: https://github.com/jxnblk/mdx-deck

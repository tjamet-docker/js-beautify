# js-beautify
The dockerfile for js-beautifuer

# Usage

## In a pipe
```bash
curl https://unpkg.com/react@16.0.0/umd/react.production.min.js | docker run --rm -i tjamet/js-beautify -i
```

## With a file
```bash
curl https://unpkg.com/react@16.0.0/umd/react.production.min.js > file.js
docker run --rm -v $PWD:/tmp:ro -w /tmp tjamet/js-beautify file.js
```


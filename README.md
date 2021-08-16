# HStreamDB Docs


Documentation for HStreamDB.


## Preview with docker

Under project root and run:

```sh
docker run -d --name docs-preview -p 8080:8080 -v $PWD:/docs -w /docs node:14.15.5-alpine3.13 sh -c "yarn && yarn dev"
```

Now open <http://127.0.0.1:8080> in your browser.

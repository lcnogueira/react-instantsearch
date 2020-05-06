This example shows how to use session storage to cache InfiniteHits and restore the hits and the scroll position.

## Clone the example

```
curl https://codeload.github.com/algolia/react-instantsearch/tar.gz/master | tar -xz --strip=2 react-instantsearch-master/examples/infinite-hits-cache
```

## Start the example

```sh
yarn install --no-lockfile
yarn start
```

Read more about react-instantsearch [in our documentation](https://www.algolia.com/doc/guides/building-search-ui/what-is-instantsearch/react/).

## Use the development version (Using Yarn Workspace)

At the root of `react-instantsearch` package,

```sh
yarn install
yarn build
yarn workspace example-infinite-hits-cache start
```
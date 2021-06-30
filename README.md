# nuntium-static

## Test

### Install `http-server`

```
npm install http-server -g
```

### Serve locally

```
http-server assets --cors
```

### Deploy to localstack

#### Install [act][act]

See [here](https://github.com/nektos/act#installation).

#### Deploy

Run

```
act --secret-file local.env
```

[act]: https://github.com/nektos/act

# Build docker image

```bash
$ docker build -t code-runner-jvm ./jvm
```

# Run

```bash
$ docker run --rm -v `pwd`/jvm/src:/app/src -v `pwd`/test-results:/app/build/test-results code-runner-jvm
```

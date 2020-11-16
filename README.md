# basic-test-bazel

**Exercise:** fix file *BUILD.bazel* in order to allow it to compile *test.cpp* into binary *app_test*.


## Configuration on github actions / classroom

Build (must have a `package.json`):

```
npm install @bazel/bazelisk
```

Run (must setup `XDG_CACHE_HOME`):

```
export XDG_CACHE_HOME=. && ./node_modules/.bin/bazel build ... && ./node_modules/.bin/bazel run //:app_test
```

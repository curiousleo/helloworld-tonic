# helloworld-tonic

This repo exists solely to investigate https://github.com/hyperium/tonic/issues/102.

Behold:

```console
$ cargo build
   Compiling hyper v0.13.0-alpha.4
   Compiling tower v0.3.0-alpha.2
   Compiling tower-balance v0.3.0-alpha.2
   Compiling helloworld-tonic v0.1.0 (/home/leo/Code/untracked/helloworld-tonic)
error: failed to run custom build command for `helloworld-tonic v0.1.0 (/home/leo/Code/untracked/helloworld-tonic)`

Caused by:
  process didn't exit successfully: `/home/leo/Code/untracked/helloworld-tonic/target/debug/build/helloworld-tonic-fce885f2e67115ba/build-script-build` (exit code: 1)
--- stderr
Error: Os { code: 2, kind: NotFound, message: "No such file or directory" }

warning: build failed, waiting for other jobs to finish...
error: build failed
```

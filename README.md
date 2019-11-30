# Mozconfig manager

Just the setup that emilio came up with to manage his builds.

## Usage

Just put the `bin` directory somewhere in your `PATH` and do:

```
$ buildwith debug
```

For a debug build, or:

```
$ buildwith debug asan noopt
```

For an unoptimized asan build. And so on.

Hg repo: https://hg.mozilla.org/users/emilio_crisal.io/mozconfigs/
Git repo: https://github.com/emilio/mozconfigs

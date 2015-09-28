# utils for golang

@zchee golang util files library.  

## go-homedir
import by mitchellh/go-homedir

> ### go-homedir
> This is a Go library for detecting the user's home directory without the use of cgo, so the library can be used in cross-compilation environments.
> 
> Usage is incredibly simple, just call homedir.Dir() to get the home directory for a user, and homedir.Expand() to expand the ~ in a path to the home directory.
> 
> Why not just use os/user? The built-in os/user package requires cgo on Darwin systems. This means that any Go code that uses that package cannot cross compile. But 99% of the time the use for os/user is just to retrieve the home directory, which we can do for the current user without cgo. This library does that, enabling cross-compilation.

## Installation

```bash
go get -d github.com/zchee/utils
```

## Usage

```go
import (
    "..."
    "..."
    "github.com/zchee/utils"
)

...
```

## License
The MIT License (MIT)  
Copyright (c) 2015- Koichi Shiraishi a.k.a. zchee

Import(fork) library are comform to the original LICENSE.

## Author
Koichi Shiraishi a.k.a. zchee

[![github][1.1]][1] zchee  
[![twitter][2.1]][2] _zchee_

[1]: https://github.com/zchee
[2]: https://twitter.com/_zchee_

[1.1]: http://s3.zchee.io/images/fontawesome/32/github-square.svg
[2.1]: http://s3.zchee.io/images/fontawesome/32/twitter-square.svg

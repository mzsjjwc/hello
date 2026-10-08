# hello

just say hello

## Install

import code

```bash
go get github.com/mzsjjwc/hello@latest
```

## Example

Here's a simple example as follows:

```go
package main

import (
  "fmt"
  "github.com/mzsjjwc/hello"
)

func main() {
  result := hello.Hello("jack")
  fmt.Println(result)
}
```
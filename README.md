# cache

## Example
```
package main

import (
	"fmt"
	"github.com/sergii-r/cache"
)

func main() {
	c := cache.New()
	c.Set("qqq", "red")
	c.Set("www", 3)
	c.Set("eee", 'A')
	c.Delete("www")
	fmt.Println(c)
}
```

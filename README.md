Windows GUI Library
===================

This is a pure Go library to create native Windows GUIs.

The [godoc.org documentation](https://godoc.org/github.com/gonutz/wui) is broken for some reason and the [pkg.go.dev documentation](https://pkg.go.dev/github.com/gonutz/wui) has issues with the license for some versions, I am not sure what the problems are. Until I find a way to generate nice HTML documentation inside this repo itself and can link to that, just run

	go doc -all github.com/gonutz/wui

to see the documentation as text. You can add a `> doc.txt` to save it to a file, or a `| clip` to copy it to the clipboard and paste it into your editor. The [godoc command](https://godoc.org/golang.org/x/tools/cmd/godoc) will also display it for you, in nice HTML, but it takes a while to start.

# Minimal Example

This is all the code you need to create a window (which does not do much).

```Go
package main

import "github.com/gonutz/wui"

func main() {
	wui.NewWindow().Show()
}
```

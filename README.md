# dectobin
package main

import (
	"fmt"
	"strconv"
)

func main() {
	var decimal int64
	fmt.Println("Input your decimal number here: ")
	fmt.Scan(&decimal)
	output := strconv.FormatInt(decimal, 2)
	fmt.Print("Output ", output)
}

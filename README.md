package main

import "fmt"

func luasPersegi(sisi int) int {
	return sisi * sisi
}

func luasSegitiga(alas, tinggi float32) float32 {
	return alas * tinggi / 2
}

func luasLingkaran(r float32) float32 {
	return (22 / 7) * r * r
}

func EP(massa, g, h float32) float32 {
	return massa * h * g
}
func EK(v float32) float32 {
	return 0.5 * v * v
}
func frekuensi(T float32) float32 {
	return 1 / T
}
func CtoF(C float32) float32 {
	return 9/5*C + 32
}
func CtoK(C float32) float32 {

	return C + 273
}
func CtoR(C float32) float32 {
	return C * 4 / 5
}

func main() {
	fmt.Println(luasPersegi(5))

	fmt.Println(luasSegitiga(5, 3))

	fmt.Println(luasLingkaran(7))

	fmt.Println(EK(10))

	fmt.Println(frekuensi(8))

	fmt.Println(CtoF(10))

  	fmt.Println(CtoK(10))

  	fmt.Println(CtoR(100))
}

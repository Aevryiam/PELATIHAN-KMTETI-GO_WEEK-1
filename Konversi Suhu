package main

import (
	"fmt"
)

func main() {
	var celsius float64
	var pilihan int

	fmt.Print("Masukkan suhu dalam Celsius: ")
	fmt.Scanln(&celsius)

	fmt.Println("Pilih konversi suhu:")
	fmt.Println("1. Fahrenheit")
	fmt.Println("2. Kelvin")
	fmt.Println("3. Reamur")
	fmt.Print("Masukkan pilihan (1/2/3): ")
	fmt.Scanln(&pilihan)

	switch pilihan {
	case 1:
		fahrenheit := (celsius * 9 / 5) + 32
		fmt.Printf("Suhu dalam Fahrenheit: %.2f F\n", fahrenheit)
	case 2:
		kelvin := celsius + 273.15
		fmt.Printf("Suhu dalam Kelvin: %.2f K\n", kelvin)
	case 3:
		reamur := celsius * 4 / 5
		fmt.Printf("Suhu dalam Reamur: %.2f R\n", reamur)
	default:
		fmt.Println("Pilihan tidak valid.")
	}
}

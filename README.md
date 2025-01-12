
def kalkulator():
 print("1. Tambah")
 print("2. Kurang")
 print("3. Kali")
 print("4. Bagi")
 
 pilihan = input("Pilih operasi (1/2/3/4): ")
 
 if pilihan == "1":
 num1 = float(input("Masukkan angka 1: "))
 num2 = float(input("Masukkan angka 2: "))
 hasil = num1 + num2
 print(f"Hasil: {num1} + {num2} = {hasil}")
 
 elif pilihan == "2":
 num1 = float(input("Masukkan angka 1: "))
 num2 = float(input("Masukkan angka 2: "))
 hasil = num1 - num2
 print(f"Hasil: {num1} - {num2} = {hasil}")
 
 elif pilihan == "3":
 num1 = float(input("Masukkan angka 1: "))
 num2 = float(input("Masukkan angka 2: "))
 hasil = num1 * num2
 print(f"Hasil: {num1} * {num2} = {hasil}")
 
 elif pilihan == "4":
 num1 = float(input("Masukkan angka 1: "))
 num2 = float(input("Masukkan angka 2: "))
 if num2 != 0:
 hasil = num1 / num2
 print(f"Hasil: {num1} / {num2} = {hasil}")
 else:
 print("Error: Pembagian dengan nol!")
 
 else:
 print("Error: Pilihan tidak valid!")
 
kalkulator()
```

JavaScript
```
function kalkulator() {
 let pilihan = prompt("Pilih operasi (1/2/3/4): ");
 
 switch (pilihan) {
 case "1":
 let num1 = parseFloat(prompt("Masukkan angka 1: "));
 let num2 = parseFloat(prompt("Masukkan angka 2: "));
 alert(`Hasil: ${num1} + ${num2} = ${num1 + num2}`);
 break;
 
 case "2":
 let num1 = parseFloat(prompt("Masukkan angka 1: "));
 let num2 = parseFloat(prompt("Masukkan angka 2: "));
 alert(`Hasil: ${num1} - ${num2} = ${num1 - num2}`);
 break;
 
 case "3":
 let num1 = parseFloat(prompt("Masukkan angka 1: "));
 let num2 = parseFloat(prompt("Masukkan angka 2: "));
 alert(`Hasil: ${num1} * ${num2} = ${num1 * num2}`);
 break;
 
 case "4":
 let num1 = parseFloat(prompt("Masukkan angka 1: "));
 let num2 = parseFloat(prompt("Masukkan angka 2: "));
 if (num2 != 0) {
 alert(`Hasil: ${num1} / ${num2} = ${num1 / num2}`);
 } else {
 alert("Error: Pembagian dengan nol!");
 }
 break;
 
 default:
 alert("Error: Pilihan tidak valid!");
 }
}
 
kalkulator();
```

Java
```
import java.util.Scanner;
 
public class Kalkulator {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 
 System.out.println("1. Tambah");
 System.out.println("2. Kurang");
 System.out.println("3. Kali");
 System.out.println("4. Bagi");
 
 System.out.print("Pilih operasi (1/2/3/4): ");
 int pilihan = scanner.nextInt();
 
 if (pilihan == 1) {
 System.out.print("Masukkan angka 1: ");
 double num1 = scanner.nextDouble();
 System.out.print("Masukkan angka 2: ");
 double num2 = scanner.nextDouble();
 double hasil = num1 + num2;
 System.out.println("Hasil: " + num1 + " + " + num2 + " = " + hasil);
 
 } else if (pilihan == 2) {
 System.out.print("Masukkan angka 1: ");
 double num1 = scanner.nextDouble();
 System.out.print("Masukkan angka 2: ");
 double num2 = scanner.nextDouble();
 double hasil = num1 - num2;
 System.out.println("Hasil: " + num1 + " - " + num2 + " = " + hasil);
 
 } else if (pilihan == 3) {
 System.out.print("Masukkan angka 1: ");
 double num1 = scanner.nextDouble();
 System.out.print("Masukkan angka 2: ");
 double num2 = scanner.nextDouble();
 double hasil = num1 * num2;
 System.out.println("Hasil: " + num1 + " * " +

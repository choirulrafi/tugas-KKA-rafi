# Program menghitung luas permukaan kubus

def luas_kubus(sisi):
    return 6 * sisi * sisi

sisi = float(input("Masukkan panjang sisi kubus: "))
luas = luas_kubus(sisi)
print(f"Luas permukaan kubus adalah: {luas}")
Java
Java
import java.util.Scanner;

public class LuasKubus {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Masukkan panjang sisi kubus: ");
        double sisi = input.nextDouble();
        double luas = 6 * sisi * sisi;
        System.out.println("Luas permukaan kubus adalah: " + luas);
    }
}
C
C
#include <stdio.h>

int main() {
    float sisi, luas;
    printf("Masukkan panjang sisi kubus: ");
    scanf("%f", &sisi);
    luas = 6 * sisi * sisi;
    printf("Luas permukaan kubus adalah: %.2f\n", luas);
    return 0;
}
Penjelasan Rumus:
Luas permukaan kubus = 6 × sisi × sisi

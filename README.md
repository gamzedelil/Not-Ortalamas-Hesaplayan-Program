# Not-Ortalamasi-Hesaplayan-Program
import java.util.Scanner;
 
public class Main {
     public static void main(String[] args) {
         int mat, fizik, kimya, tarih, turkce, muzik;
        Scanner inp = new Scanner(System.in);
      
    System.out.print("Matematik dersinin notunu girin:");
    mat = inp.nextInt();
    
    
     System.out.print("Fizik dersinin notunu girin:");
    fizik = inp.nextInt();
    
    
     System.out.print("Kimya dersinin notunu girin:");
    kimya = inp.nextInt();
    
    
     System.out.print("Tarih dersinin notunu girin:");
    tarih = inp.nextInt();
    
    
    System.out.print("Turkce dersinin notunu girin:");
    turkce = inp.nextInt();
  
    
    System.out.print("Muzik dersinin notunu girin:");
    muzik = inp.nextInt();
 
    
    int toplam = (mat + fizik + kimya + tarih + turkce + muzik);
    double sonuc = toplam / 6;
    System.out.println(sonuc);
    
    String ortalama = (sonuc >= 60) ? "Gectiniz" : "Kaldiniz";
        System.out.println(ortalama);
    
    
    }
}

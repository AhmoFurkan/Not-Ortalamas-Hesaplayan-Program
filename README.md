# Not-Ortalaması-Hesaplayan-Program
Aynı program içerisinde koşullu ifadeler kullanılarak, eğer kullanıcının ortalaması 60'dan büyük ise ekrana "Sınıfı Geçti" , küçük ise "Sınıfta Kaldı" yazsın.



import  java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        //  Değişkenleri oluştur

       int mat, fizik, kimya, turkce, tarih, muzik ;
       // Scanner sınıfımızı tanımladık
       Scanner inp = new Scanner(System.in);

       // Kullanıcıdan değerleri al
        System.out.print("Matematik Notunuz :");
        mat = inp.nextInt();

        System.out.print("Fizik Notunuz :");
        fizik = inp.nextInt();

        System.out.print("Kimya Notunuz :");
        kimya = inp.nextInt();

        System.out.print("Türçe Notunuz :");
        turkce = inp.nextInt();

        System.out.print("Tarih Notunuz :");
        tarih = inp.nextInt();

        System.out.print("Müzik Notunuz :");
        muzik = inp.nextInt();

        int toplam  = (mat + fizik + kimya + turkce + tarih + muzik);
        double sonuc = toplam / 6;
          System.out.println("ortalamanız : " + sonuc);
         String x  = sonuc>=60  ? "Sınıfı Geçti" : "Sınıfta Kaldın";
     System.out.println(x);

   
      
















    }
}


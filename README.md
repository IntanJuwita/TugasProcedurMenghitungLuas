TugasProcedurMenghitungLuas
===========================

package id.blits.Tugas;


public class NewMainMenu {

 
    public static void main(String[] args) {
        // TODO code application logic here
        PersegiPanjang Perpan =  new  PersegiPanjang();
        Perpan.nama="Persegi Panjang";
        Perpan.Panjang=20;
        Perpan.Lebar=12;
        
        Perpan.tampilPersegiPanjang();
        
        Segitiga SegiTiga = new Segitiga();
        SegiTiga.nama="Menghitung Luas Segi Tiga";
        SegiTiga.Alas=25;
        SegiTiga.Tinggi=30;
        
        SegiTiga.tampilSegiTiga();
        
        Lingkaran Intan = new  Lingkaran();
        Intan.nama="Menghitung Luas Lingkaran";
        Intan.Jari2=20;
        
        Intan.tampilLingkaran();

        

        
    }
    
}

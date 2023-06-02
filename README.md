# ÖDEV :
## Java İle Kombinasyon Hesaplayan Program :
```
import java.util.Scanner;

public class DENEME {
    public static void main(String[] args) {
        int n,r,faktN=1,faktR=1,faktFark=1;
        double C;
        Scanner input=new Scanner(System.in);
        System.out.print("n Sayısını Giriniz : ");
        n=input.nextInt();
        System.out.print("r Sayısını Giriniz : ");
        r=input.nextInt();
        for (int i=n;i>0;i--){
            faktN*=i;
        }
        for (int j=r;j>0;j--){
            faktR*=j;
        }
        for (int k=n-r;k>0;k--){
            faktFark*=k;
        }
        C=(double)faktN/(faktR*faktFark);
        System.out.print("C(n,r)=n!/r!*(n-r)! = "+C);
    }
}
```
# Patika Profilim :
<a href='https://academy.patika.dev/profile'><u>Patika Profilim</u></a>
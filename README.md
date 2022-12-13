# UserLogin
```
import java.util.Scanner;


public class KullaniciGirisi {
    public static void main(String[] args) {
        String userName,password,newPass;
        int a;

        Scanner i = new Scanner(System.in);

        System.out.print("Kullanıcı adınızı giriniz:");
        userName = i.nextLine();

        System.out.print("Şifrenizi giriniz:");
        password = i.nextLine();

        if (userName.equals("Tarıkk") && password.equals("151598")) {
            System.out.print("Başarılı bir şekilde giriş yaptınız!");
        }else {
            System.out.println("Giriş bilgileriniz hatalı. Şifrenizi unuttuysanız değiştirebilirsiniz.");
            System.out.print("1-Şifremi değiştirmek istiyorum\n2-İptal\nLütfen seçim yapınız:");
            a = i.nextInt();
            if (a == 1) {
                Scanner input = new Scanner(System.in);

                System.out.print("lütfen yeni bir şifre giriniz!:");
                newPass = input.nextLine();

                System.out.println("Şifreniz başarılı bir şekilde oluşturuldu.\nYeni şifrenizile giriş yapabilirsiniz.");

                System.out.print("Kullanıcı adınızı giriniz:");
                userName = input.nextLine();

                System.out.print("Şifrenizi giriniz:");
                newPass = input.nextLine();

                System.out.println("Başarılı bir şekilde giriş yaptınız!");


            } else if (a == 2) {
                System.out.print("Lütfen giriş bilgilerinizi kontrol ederek tekrar deneyiniz.");

            }

        }

    }
}
```
[Patika.dev](https://app.patika.dev/iremr)

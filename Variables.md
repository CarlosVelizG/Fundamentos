package fundamentos;

/*CARLOS JULIO VÉLIZ GONZÁLEZ
//Variables o metodos de clases son static
// Variables o metodos de instancia no son static
// Para accede a un me todo o varibles static es:
// NombreClase.Metodo o NombreClase.Variable
*/

class CuentaBancaria{
    public int saldo;
    public static int numero=0;
}

    public class Variables {
        public static void sumarSaldo(CuentaBancaria cta){
            cta.saldo +=10;
        }
        
        public static void sumarSaldo(int saldo){
            saldo +=10;
        }
    //crean minimo 10 objetos CuentaBancaria y probar
    public static void main(String[] args) {
        CuentaBancaria ct1=new CuentaBancaria();
        CuentaBancaria ct3=new CuentaBancaria();
        CuentaBancaria ct4=new CuentaBancaria();
        CuentaBancaria ct5=new CuentaBancaria();
        CuentaBancaria ct6=new CuentaBancaria();
        CuentaBancaria ct7=new CuentaBancaria();
        CuentaBancaria ct8=new CuentaBancaria();
        CuentaBancaria ct9=new CuentaBancaria();
        CuentaBancaria ct10=new CuentaBancaria();
        CuentaBancaria ct11=new CuentaBancaria();
        CuentaBancaria ct12=new CuentaBancaria();       
        CuentaBancaria ct13=new CuentaBancaria();
        CuentaBancaria ct14=new CuentaBancaria();
        CuentaBancaria ct15=new CuentaBancaria();
        CuentaBancaria ct16=new CuentaBancaria();
        CuentaBancaria ct17=new CuentaBancaria();
        CuentaBancaria ct18=new CuentaBancaria();
        CuentaBancaria ct19=new CuentaBancaria();
        CuentaBancaria ct20=new CuentaBancaria();
        CuentaBancaria ct2=ct1;
        
        
        
        ct1.saldo=1000;
        ct3.saldo=1000*2;
        ct4.saldo=ct3.saldo/3;
        ct5.saldo=ct4.saldo+ct1.saldo;
        ct6.saldo= ct3.saldo+90;
        ct7.saldo= 98 ;
        ct8.saldo=(ct6.saldo*ct5.saldo)/ct7.saldo ;
        ct9.saldo= (ct7.saldo*ct1.saldo)+ct7.saldo;
        ct10.saldo= 365;
        ct11.saldo= ct7.saldo % ct6.saldo;
        ct12.saldo= (ct1.saldo+ct3.saldo-ct5.saldo)%3;
        ct13.saldo=  ct4.saldo-ct10.saldo ;
        ct14.saldo= ct3.saldo*2;
        ct15.saldo= ct9.saldo-ct8.saldo;
        ct16.saldo= ct7.saldo/9;
        ct17.saldo= ct16.saldo*ct11.saldo;
        ct18.saldo= ct7.saldo+ct16.saldo;
        ct19.saldo= ct18.saldo *4;
        ct20.saldo= ct19.saldo/100;
        
        
        
        sumarSaldo(ct1);
        sumarSaldo(ct2);
        sumarSaldo(ct3);
        sumarSaldo(ct4);
        sumarSaldo(ct5);
        sumarSaldo(ct6);
        sumarSaldo(ct7);
        sumarSaldo(ct8);
        sumarSaldo(ct9);
        sumarSaldo(ct10);
        sumarSaldo(ct11);
        sumarSaldo(ct12);
        sumarSaldo(ct13);
        sumarSaldo(ct14);
        sumarSaldo(ct15);
        sumarSaldo(ct16);
        sumarSaldo(ct17);
        sumarSaldo(ct18);
        sumarSaldo(ct19);
        sumarSaldo(ct20);
        
        
        
        
        
        
       
        System.out.println("         PRUEBAS CON OBJETOS \n");
        System.out.println(" *  CT1 : "+ct1.saldo);// Imprime 1020
        System.out.println(" *  CT2 : "+ct2.saldo);// Imprime 1020
        System.out.println(" *  CT3 : "+ct3.saldo);// Imprime 2010
        System.out.println(" *  CT4 : "+ct4.saldo);// Imprime 676
        System.out.println(" *  CT5 : "+ct5.saldo);// Imprime 1676
        System.out.println(" *  CT6 : "+ct6.saldo);// Imprime 2100
        System.out.println(" *  CT7 : "+ct7.saldo);// Imprime 108
        System.out.println(" *  CT8 : "+ct8.saldo);// Imprime 35540
        System.out.println(" *  CT9 : "+ct9.saldo);// Imprime 98108
        System.out.println(" *  CT10 : "+ct10.saldo);// Imprime 375
        System.out.println(" *  CT11 : "+ct11.saldo);// Imprime 108
        System.out.println(" *  CT12 : "+ct12.saldo);// Imprime 12
        System.out.println(" *  CT13 : "+ct13.saldo);// Imprime 331
        System.out.println(" *  CT14 : "+ct14.saldo);// Imprime 4010
        System.out.println(" *  CT15 : "+ct15.saldo);// Imprime 62578
        System.out.println(" *  CT16 : "+ct16.saldo);// Imprime 20
        System.out.println(" *  CT17 : "+ct17.saldo);// Imprime 990
        System.out.println(" *  CT18 : "+ct18.saldo);// Imprime 118
        System.out.println(" *  CT19 : "+ct19.saldo);// Imprime 442
        System.out.println(" *  CT20 : "+ct20.saldo);// Imprime 14
        
        
    
    }
    
}

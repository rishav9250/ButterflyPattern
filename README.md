# ButterflyPattern
here is a code of ButterflyPattern in java.

public class ButterflyPattern {
    public static void Butterfly(int n){
        // star = i
        for(int i =1;i<=n;i++){
            for(int j=1;j<=i;j++){
        System.out.print("*");
                }
            // space = 2*(n-i)
            for(int j =1;j<=2*(n-i);j++){
                System.out.print(" ");
            }
                // star =i
                for(int j =1;j<=i;j++){
                    System.out.print("*");
                }
           System.out.println();
            } 

        
        
    
for(int i=n;i>=1;i--){
    for(int j =1;j<=i;j++){
                    System.out.print("*");
                }
     
          
     
            // space = 2*(n-i)
            for(int j =1;j<=2*(n-i);j++){
                System.out.print(" ");
            }
                // star =i
                for(int j =1;j<=i;j++){
                    System.out.print("*");
                }
            System.out.println();
         
            }
        }
    
    
    
public static void main(String[] args) {
    Butterfly(5);
}
}






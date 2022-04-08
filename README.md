import java.util.*;

public class Practice{
    public static void main(String ...arg){
        int m=5,n=5,k=1;
        for(int i=1;i<=m;i++){
            for(int j=1;j<=i;j++){
                System.out.print(k++ +" ");
            }
            System.out.println();
        }
    }
}

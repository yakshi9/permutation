import java.util.*;
public class lec36 {
    public static void main(String args[]){
       String str="ABC";
       for(int i=0;i<str.length();i++){
        String str1="";
       System.out.print(str.charAt(i));
       for(int j=0;j<str.length();j++){
        if(j==i){
            continue;
        }
       for(int k=0;k<str.length();k++){
        if(k==i||k==j){
           continue;
        }
        for(int z=0;z<str.length();z++){
           if(z==i||z==j||z==k){
            continue;
           }
        System.out.print(str.charAt(i));
        System.out.print(str.charAt(j));
        System.out.print(str.charAt(k));
        System.out.print(str.charAt(z));
        }
       }
    }
}
}
}

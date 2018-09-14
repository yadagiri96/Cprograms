# Cprograms
//array reverse
public class HelloWorld{
  static int i,j=0;
     public static void main(String []args){
        int[] a={1,2,3,4};
       // int sum=0;
       
        int LengthOfArray=a.length-1;
        int b[]=new int[LengthOfArray+1];
        for(i=LengthOfArray;i>=0;i--){
            b[j++]=a[i];
        }
        int LengthOfNewArray=b.length;
        for(int c=0;c<LengthOfNewArray;c++){
            System.out.println(b[c]);
        }
     }
}

# array-question
 (question 1 )  calculate the average value of array elements?
 class Main{
  public static void main(String[] args) {
    System.out.println("array elements are");
    int arr[] = {1,2,3,4,5};
    int sum=0;
    for(int i=0;i<arr.length;i++){
      System.out.println(arr[i]);
      sum=sum+arr[i];
    }
     System.out.println("sum of array elements are"+sum);
    int avg=sum/arr.length;
    System.out.println("average of array elements are"+avg);
  }
}




(question 3) find the index of an array element?

import java.util.*;
class Main{
  public static void main(String[] args){
   Scanner sc= new Scanner (System.in);
   int a[]={2,4,5,6,7,8};
    for (int i=0;i<a.length;i++){
      System.out.println(a[i]);
    }
    System.out.println("enter the element ");
    int n =sc.nextInt();
    for(int j=0;j<a.length;j++){
    if (a[j]==n){
   System.out.println("index of the array is"+ j);
      break;
      }
  }
    }
}


(question-4) find the maximum and minimum value of an array?
 
 class Main{
    public static void main(String[]args){
      int arr[]={4,67,8,98,76,32};
      int max=arr[0];
      int min=arr[0];
 for(int i=1;i<arr.length;i++){
       
       if (arr[i] > max){
          max=arr[i];
        }
        if(arr[i]<min){
          min=arr[i];
        }
      }
        System.out.println("maximun" +max);
        System.out.println("minimun" +min);
      }
   }


 (question-7)  Write a Java program to test two arrays' equality

 class Main{
public static void main(String[]args){
int arr[]={4,67,8,98,76,32};
int arr2[]={2,4,5,67,89,45};
for (int i=0;i<arr.length;i++){
for(int j=0;j<arr2.length;j++){
 if(arr[i]==arr2[j]){
   System.out.println("both the elements are equal");
 break;}
  else{
   System.out.println("both the elements are not equal");
  break;}
}break;
}
}
}


(question-8) find the number of even and odd integers in agiven array of integers.

class Main{
public static void main(String[]args){
System.out.println("araay elements are");
   int a[]={9,8,5,4,3,2,9};
  int even=0;
  int odd=0;
for(int i=0;i<a.length;i++) {
  System.out.println(a[i]);
  if(a[i]%2==0){
  even++;}
 else{
  odd++;}
}
System.out.println("no of even integers are" + even);
System.out.println("no of odd integers are" + odd);
}
}





 
   

package com.mycompany.mavenproject10;
import java.util.Scanner;
public class Mavenproject10 {
    public static void main(String[] args) {
       // Scanner input=new Scanner(System.in);
       int random1=0 , random2=0 , result=0;
      for(int i=1 ; i<=4 ; i++){
          random1=(int)(Math.random()*10);
          random2=(int)(Math.random()*10);
          result=random1-random2;
          if(result>=0){
              System.out.println(random1+"-"+random2+"="+result);
          }
          else
              if(result<0){
                  int swap=random1;
                  random1=random2;
                  random2=swap;
          result=random1-random2;
                  System.out.println(random1+"-"+random2+"="+result);}
              
          
      }
       
    }
}

package com.company;
import java.io.*;

public class Main {

    public static void main(String[] args) {

            { int num,sum=0;
                System.out.println("Command line Arguments are 10,20,30");
                for(int i=0;i<args.length;i++)
                {
                    num=Integer.parseInt(args[i]);
                    sum=sum+num;
                }
                System.out.println("Sum of Elements is : "+sum);
            }
        }




    }


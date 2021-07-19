package com.company;

import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        System.out.print("Enter a String ");
        String string=in.next();
        int Uppercase_Counter=0,Lowercase_Counter=0,i;
        for(i=0;i<string.length();i++)
        {
            char character = string.charAt(i);
            if (character>='a' && character<='z')
                Lowercase_Counter++;
            else
                Uppercase_Counter++;
        }
        System.out.println("Upper Case : "+Uppercase_Counter);
        System.out.println("Lower Case : "+Lowercase_Counter);
    }

}



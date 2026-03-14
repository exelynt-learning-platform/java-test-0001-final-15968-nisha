# java-test-0001-final-15968-nisha
Final Project Assignment - This repository contains the complete final project code and documentation.
package com.pattern;


class Pattern
{
  public static void main(String args[])
  {
    int n = 9;

    int px = n/2+1;

    for(int i = 1;i<=n;i++)
    {
      for(int j = 1; j<=n;j++)
      {
        if(j==px || j==n-px + 1)
        {
          System.out.print("*");
        }
        else 
        {
          System.out.print(" ");
        }
      }

      if(i<=n/2)
      {
        px--;
      }
      else
      {
        px++;
      }

      System.out.println();
    }
  }
}

# Lab-2
Class: Programming Fundamentals (COMP112) - Laboratory #2 - String Class Methods in Java 

package lab2; import java.text.*; 

import java.text.DecimalFormat;

public class Main {

public static void main(String[] args) { 

// TODO Auto-generated method stub  
  
  String s1 = "Paola, Rodriguez";

  System.out.println(s1.length());

  String boyfriendsname = "Neo, Acevedo";

  System.out.println(boyfriendsname.toUpperCase());

  String mothersname = "Maria, Durant";

  System.out.println(mothersname.toLowerCase());

  String brothersname = "Michael, Rodriguez";

  System.out.println(brothersname.charAt(4));

  String petsnames = "Ollie & Oogie";

  System.out.println(petsnames.indexOf("Oogie"));

  String grandmothersnames = "Clara & Aurora";

  System.out.println(grandmothersnames.indexOf('a'));

  String grandfathersnames = "My grandfather's names are Feliciano and Angel";

  System.out.println(grandfathersnames.substring(0,10));

  DecimalFormat pricePattern = new DecimalFormat("$#0.00");

  double price = 34.5;

  System.out.println("The first price is: " + pricePattern.format(price));

  DecimalFormat percentPattern = new DecimalFormat("#0.00%");

  double average = .980;

  System.out.println("The average is: " + percentPattern.format(average));

  }

  }

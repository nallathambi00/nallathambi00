package jp.ac.hal;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class sum4 {


public static void main ( String[] args) throws IOException
{
	System.out.println("得点を入力してください");
	BufferedReader br=
			new BufferedReader (new InputStreamReader (System.in));
	String str =br.readLine();
	int res= Integer.parseInt(str);
	
	  if (res>= 80) {
		  System.out.println( "評価: A");
		  
      } else if (res>= 70)
      {
    	  System.out.println("評価: B");
      } else if (res >= 60) 
      {
    	  System.out.println ( "評価: C");
      } else
      {
    	  System.out.println("評価: D");
      }

      if (res>= 60)
      { System.out.println( "合格! ");
  }
      else if 
      (res<= 60)
    	  System.out.println( "不合格");
}}

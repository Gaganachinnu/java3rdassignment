package com.Xworkz.controStatement;

public class arrop {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int sum=0,i,num=10;
		int ar[]= {1,2,3,4,5};
		
		for(i=0;i<ar.length;i++) {
			if(i%2!=0)
			sum=sum+ar[i];
		}
		System.out.println(sum);
	}

}

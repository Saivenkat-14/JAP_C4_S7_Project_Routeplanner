# JAP_C4_S7_Project_Routeplanner
package com.jap.replaceinteger;

import java.util.ArrayList;

public class ArrayPairSum {

    public static void main(String[] aa) {

        //Declare and initialize integer array in the variable numberArray
        int[] numberArray= {1,2,4,6,10,23,1,8};
        ArrayPairSum arrayPairSum = new ArrayPairSum();
        int sumArray[] = arrayPairSum.sumOfArrayPair(numberArray);
        //write forEach loop to iterate through the 'sumArray' to print the output
            System.out.println(sumArray);


    }

    public int[] sumOfArrayPair(int numberArray[]){
    	ArrayList<Integer>sumarray=new ArrayList<Integer>();
    	if(numberArray.length%2==0) {
    		for(int i=0;i<numberArray.length;i+=2) {
    			sumarray.add(numberArray[i]+numberArray[i+1]);
    		}
    		int []values=new int[sumarray.size()];
    		for(int i=0;i<sumarray.size();i++) {
    			
    			
    		}
    	}

        return new int[0];
    }

}

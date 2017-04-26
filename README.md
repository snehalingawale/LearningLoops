# LearningLoops

package com.inportia;

public class LearningLoops {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		learningforloop();
		learningwhileloop();
		
		
		int a=4;
		Student manasi=new Student(3,"manasi");
		manasi.displaystudentdata();
		Student chetan=new Student(4,"chetan");
		chetan.displaystudentdata();
		Rectangle rect=new Rectangle(4,5);
		rect.area();
		Circle abc=new Circle(5);
		abc.arc();
		
	}
		
	
    public static void learningwhileloop(){
    	System.out.println("Number series");
    	int first =0;
    	int second = 1;
    	int third = 0;
    	
    	System.out.print(first + " " + second);
    	
    	while(third < 13){
    		third = first + second;
        	System.out.print(" " + third);
        	first = second;
        	second =third;
        	
    	}    	 	    	
    	
    }
        	 
    public static void learningforloop(){
    	for(int i=0;i<=10;i=i+2){
    	System.out.print(" "+i);
    	}
    }
    
}


 
 



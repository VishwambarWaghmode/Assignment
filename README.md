# Assignment
1. Reverse a string and Print it on console
package  com.github;
class Ass1{

    public static void main(String args[]){


        String myStr = "JAVA SKILLS";
        for (int i = myStr.length()-1; i>=0; i--) {

            System.out.println(myStr.charAt(i));
        }

    }


}

2. Assign String to x variable in 'DD-MM-YYYY'

package com.github;
public class ass2java {
    public static void main(String args[]){
        String a= "16-10-2003";

        String x= a.split ("-")[0];
        String y= a.split("-")[1];
        String z= a.split("-")[2];
         System.out.println("Year : "+a);
    }
}

3. code for calculate salary of employee 

package com.github;

public class ass3java {
    public static void main(String[] args){
        int avgOfThreeEmpInOneWeek=1000;

        int E1_Salary=1100;
        int E2_Salary=500;
        float E3_Salary; //we have to find third employee salary

        E3_Salary= (float) ((avgOfThreeEmpInOneWeek*3.0)/ (E1_Salary+E2_Salary));

        System.out.println("Salary of Third Employee is:"+E3_Salary);
    }

}

4. code for convert percentage to friction 

package com.github;

public class ass4java {
    public static void main(String[] args){
        int per=30; // percentage = 30%
        int numerator = per; //to reduce friction
        int denominator = 100;
        //friction= numerator / denominator

        System.out.println(" friction of "+per+" %is : "+numerator+"/"+denominator);



    }
}

5. code for calculate time duration in which a 340m long train can pass 160m long tunnel at speed 45km/hr

package com.github;

public class ass5java {
    public static void main(String[] args){
        int trainLength=340; //340m long train
        double speed=45.0; //given 45km/hr speed of train
        int tunnel= 160; // given 160m long tunnel

        /* first we have to convert km/hr into m/s
        * 45km/hr= 45* 1000/3600 m/s
        * Speed- 25/2 m/s
        * total distace travelled= (340+160)
        * time= d/s
        *       500/(25/2)
        *       500*(2/25)
        *       40sec
        */
        speed=(double) speed*(1000/3600.0);
        int distance=trainLength;
        double time= distance/speed;

        System .out.println("Time Required : "+time+"Seconds");



    }
}


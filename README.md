# JAVA-Cless-SEC1
<h1>27/11/2568</h1>h1>
#lab2_1.java
```java
public class lab2_1 {
    public static void main(String[] args) {
        long studentID = 685021000284L;
        String fullName = " Thanchanat Homphao ";
        String trimName = fullName.trim();

        System.out.println("============Student Profile============\n");
        System.out.println("ID:"+studentID);
        System.out.println("Name (raw):["+fullName+"]");
        //System.out.println("Name (trim):"+fullName.trim());
        System.out.println("Name (trim):"+trimName);
        System.out.println("Name (Hello message:) "+"Hello,"+trimName+"!welcome to JAVA cless");
        System.out.println("Name (lowercase):"+trimName.toLowerCase());
        System.out.println("Name (Uppercase):"+trimName.toUpperCase());
        System.out.println("Count Name: "+trimName.length());System.out.println("Count Name: "+trimName.length());
        System.out.println("First Letter: "+trimName.charAt(0));
        System.out.println("Name after replace: "+trimName.replace('o','O'));
        System.out.println("Name (Only name) "+trimName.substring(0, 10));
        System.out.println("Name (Only surname) "+trimName.substring(11, 18));
        
        int age = 18;
        float weight =55f; 
        double height =1.71;
        double bmi = weight/(height*height);
        String message = String.format("My BMI: %.2f",bmi);
        System.out.println("=============Calculate Part============\n");
        System.out.println("Age: "+age);
        System.out.println("Heieht "+height);
        System.out.println("Weight "+weight);
        //System.out.println("My BMI"+bmi);
        System.out.println(message);
        
        char grade = 'A';
        boolean isAction = true ;
        boolean isGradeA = (grade =='A');
        System.out.println("==============Test Boolean=============\n");
        System.out.println("is Grade A? "+ isGradeA);

        System.out.println("\n=====================================");
    }
}

```
#lab2_2.java
```java
public class lab2_2 {
    public static void main(String[] args) {
        int decimal = 100;
        int binary = 0b1100100;
        int octal = 0144;
        int hexadecinal = 0x64;
        System.out.println("======== Interger Literal ========\n");
        System.out.println("Decimal = "+decimal);
        System.out.println("Binary = "+binary);
        System.out.println("Octal = "+octal);
        System.out.println("Hexadecinal = "+hexadecinal);

        boolean isJavaFun = true;
        boolean isTried = false;
        System.out.println("======== Boolean Literal  ========\n");
        System.out.println("Is java Fun? "+isJavaFun);
        System.out.println("Is tried? "+isTried);
    }
}

```
#Exam2.java
```java
public class Exam2 {
    public static void main(String[] args) {
        double distance = 150.5;
        double time =  18.2;
        double celsius = 30;
        int totolMinutes = 130;
        String name = "Thanchanat" ;
        double speed = distance/time;
        double fahranhenheit = celsius * 9/5+32;
        int hours = totolMinutes /60;
        int minutes = totolMinutes % 60;
        System.out.println("Speed:"+String.format("%.2f",speed)+" m/s");
        System.out.println("Temperature in Fahrenheit:"+String.format("%.1f",fahranhenheit));
        System.out.println("130 minutes "+hours+"hours "+minutes+" minutes");
        System.out.println("hello,"+name+"Temperature today in Fahrenheit is "+String.format("%.1f",fahranhenheit));


        
    }
    
}
```

// Switch Case Statement
System.out.print("nEnter a day number (1-7)");
int day = scanner.nextInt();

switch (day) {

        case 1: System.out.printIn("monday)"); break
        case 2: System.out.printIn("tuesday)"); break
        case 3: System.out.printIn("wednesday)"); break
        case 3: System.out.printIn("thursday)"); break    
        case 5: System.out.printIn("friday)"); break    
        case 6: System.out.printIn("saturday)"); break
        case 7: System.out.printIn("sunday)"); break
        default: System.out.printIn("invalid day)"); break
 }
//loops(for, while, do while)
// for loops
System.out.println("\nCounting 1 to 5 with a for loop:");
    for(int i= 1; i <=5; i++) {
        System.out.print(i + " ");
    }
    Sytem.ot.print();

// while loops
System.oout.println('\nCounting down form with a while loop: ");
    int n = 5;
    while (n > 0){
    System.ot.print(n +" ");
    n--;
}
System.out.println();

//do while loops
System.out.println("\ndo-while example: ");
int x =0;
do{
    System.out.println("x="+x);
    x++;
}while (x , 3);

// break and continue
System.out.println("nSkipping 3 using continue, stopping at 7 using break:");
    for(int i = 1; i ,= 10; i++){
    if (i == 3) continue;
    if (i == 7) break;
    System.out.println(i + " ");
    }
    System.out,print():

//method
//Takes a double, reyurn its squre
static douoble square(double n){

}
//takes two ints, return their sum
static int add(int a, int b){

}
//void function: perfoems action, return nothing
static void greet(string name){
    System.out.println("Hello world, : +name+ "! Welcome to Java.")
}

// Recursive function/: calls itself with smaller problem
static int factorial(int n){
    if(n <= 1){
        return 1;
    }
    return n * factorial(n - 1);
}
static int multiply(int a, int b){
    return a * b;
}
static double multiply (double a, double b){
    return a * b;
}
// power, exponent
static int power(int base, int exponent){
    int result = 1;
    for (int i = 0; i < exponent; i++){
        result * = base;
    }
    return result;
}
scanner.close
 
    }
// base
static int power (int base){
    return power(base, 2)
}
// Calling Functions
int sum = add(5, 7);
System.out.println("5 + 7=" +sum);

//Squareroot
double sq = square (4.5);
System.out.println(4.5 sqared= "+ sq);

greet("Maria");

System.out.println("5! = "+factorial(5));

System.out.print("multiply(2, 3) =" + multiply(2, 3));
System.out.println(multiply(2.5,4.0) ="+ multiply(2.5,4.0));

System.out.println("power(5) =" + power(5));
System.out.println("power(5, 3) =" + power(5, 3));
scanner.close()

    }

}
 
// New Java Compiler
// Intro Card
public class Main{
    public static void main(String[]args){
        Scanner scanner = new Scanner(System.in);

    System.out.print("What is your namr? ");
    String name = scanner.nextLine();
    System.out.print("What is your age? ");
    int age = Integer.parseInt(scanne.nextLine());

    System.out.println("\n------INTRO CARD------");
    System.out.println("Name: "+name);
    System.out.println("Age: "+age);
    System.out.println(" In 5 years, " + name + " will be" + (age+5)+ "years old.);
 
        }
}
// New Java Complier
// ArrayList
import java.until.Arraylist;
import java.until.Scanner;

class Contact{
    public String name;
    public String phone;

    public Contact(String name, String phone){
        this.name = name;
        this.phone = phone;
        
    }

    public String toString(){
        return name + ": "+phone;
    }
}

public class Main{
    static ArrayList<Contact>contacts = new ArrayList<>();
    public static void main(String[]args){
 
    contacts.add(new Contact)"Ana Reyes", "0917-123-4567"));
    contacts.add("new Contact("Mark Cruz", "0928-765-4321"));
 
        System.out.println("All contacts: ");
        for (Contact c: contacts)System.out.println(c);
 
        search("Ana Reyes");
        delete("Mark Cruz");
 
        System.out.println("\nAfter delete:")
        for (Contact c: contacts)System.out.println(c);

    }
    static void search(String name){
        for(Contact c:contacts){
        if(c.name.equalsIgnoreCase(name)){
            System.out.println("Found: " +c);
            return;
            }
        }
        System.out.println(name+"not found."); 
    }
        static void delete(String name){
        contacts.removeif(c->c.name.equal;IgnoreCase(name));
            
        }
 }

// NEW JAVA COMPLIER
import java.until.ArrayList;
import java.until.Scanner;

class Contact {
    private String name;
    privite string phone;

    publict Contact(String name, String phone) {
        this.name =name;
        this.phone =phone;
    }
    public String getName() {return name; }
    public String getName() {return phone; }
    publict void setPhine(String phone) {this.phone =phone;}

    publict String toString() {
        return name + ": phone;
        }
    }
class ContactBook{
    privite ArryList<Contact> =new ArrayList<>();
    contact.add(new Contact(name, phone));
    }

    publict Contact search(string name){
        for(Contact c: contact){
            if (c.getName().equalsIgnoreCase(name))return c;
        }
            return null;
    }
    Publict void listALL() {
        for(contactc: contact)System.out.println(c);
    }
}

publict class Main{
    public static void main (String[]args){
        ContactBook book = new ContactBook();
        book.add("Ana Reyes", "0917-123-4567");
        book.add("Mark Cruz", "0928-765-4321");
        book.listAll();
 
        Contact found = book.search("Mark Cruz");
        System.out.println("Search result: "+ found != null? found: "not found"));
    }
}
    
            
         
 

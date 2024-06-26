package com.mycompany.mavenproject44;

class Student {

    String name;
    String dept;
    int roll;

    // Method to display student information
    void info() {
        System.out.println("name: " + name);
        System.out.println("dept: " + dept);
        System.out.println("roll: " + roll);
         System.out.println("\n");
    }
}

public class Mavenproject44 {

    public static void main(String[] args) {
        // Creating the first student object
        Student student1 = new Student();
        student1.name = "tahasin";
        student1.dept = "cse";
        student1.roll = 23;
        student1.info();
       

        // Creating the second student object
        Student student2 = new Student();
        student2.name = "rupak";
        student2.dept = "cse";
        student2.roll = 21;
        student2.info();
    }
}

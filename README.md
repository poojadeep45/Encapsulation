package Pack1; 

// Class representing a Person with encapsulated fields for name and age
public class Person {
    // Private fields for encapsulation
    private String name; 
    private int age;     
    
    // Default constructor
    public Person() {
    }

    // Parameterized constructor to initialize name and age
    public Person(String name, int age) {
        this.name = name; 
        this.age = age;  
    }

    // Getter method for the name field
    public String getName() {
        return name; // Return the current name
    }

    // Setter method for the name field
    public void setName(String name) {
        this.name = name; // Set the name to the provided value
    }

    // Getter method for the age field
    public int getAge() {
        return age; // Return the current age
    }
		
   //Stter method for gae field
   public void setAge(int age){
   this.age = age
  }
    // Setter method for the age field
    public void setAge(int age) {
        this.age = age; // Set the age to the provided value
    }
}


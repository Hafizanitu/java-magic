# java-magic
      abstract class Animal{
      public abstract void animalSound();
    public void sleep(){
        System.out.println("zee");
    }
    }
    class Cow extends Animal{
    //abstract method inherit in subclass
    public void animalSound(){
        System.out.println("huu");
    }
    }
    interface Animal1{
    public void animalFood();
    public void animalSound();
    }
    // access by subclass use implements
    class Dog implements Animal1{
    public void animalFood(){
        System.out.println("Meat");
     }

    public void animalSound(){
    System.out.println("GHU");
    }
    }

    public class Main {


     public static void main(String[] args) {
        Cow callCow = new Cow();
        callCow.sleep();
        callCow.animalSound();
        Dog callDog = new Dog();
        callDog.animalSound();
        callCow.animalSound();

        }
        }

        public class Main {
         enum Food {
        MANGO,
        LEMON,
        BANANA
        }
    

        public static void main(String[] args) {
        Food callFood = Food.MANGO;
        System.out.println(callFood);
        // wrapper object make java fully obj oriented as data type use as 
             obj
        Integer myInt = 2;
        Double myDouble = 2.0;
        System.out.println(myInt);
        System.out.println(myDouble);
        System.out.print("Hello and welcome!");


        }
        }

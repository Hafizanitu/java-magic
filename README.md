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

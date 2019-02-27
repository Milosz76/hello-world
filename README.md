# hello-world
//this is an upgrade of the hello world file.


public class HelloWorld2 {
    public static void main(String[] args) {
        System.out.println("Hello World2");
        secondMethod();
        mathematics();
    }
    public static void secondMethod() {
    String line = "This is \"Hello World2 from the variable.\" ";
        System.out.println(line);
    }
    // działania na liczbach
    public static void mathematics (){
        int x = 10;
        int y = 5;
        System.out.println(" ");
        System.out.println("Działania na liczbach: ");
        System.out.println("Simple add: x + y = " + (x + y));
        System.out.println("Simple subtract: x - y = " + (x - y));
        System.out.println("Simple multiple: x * y = " + (x * y));
        System.out.println("Simple division: x / y = " + (x / y));
    }
}

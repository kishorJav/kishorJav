- 👋 Hi, I’m @kishorJav
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kishorJav/kishorJav is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

 // java project
 
public abstract class Animals {
    public abstract void show(String name,int price);
    public void display(String name){
        System.out.println(name);
    }
}
class Dog extends Animals{
    public void show(String name,int price){
        System.out.println(name);
        System.out.println(price);
    }
    public void display(String name){
        System.out.println(name);
    }
    public void display(String name,long price){
        System.out.println("Kishor pandey");
    }
}
class Cat extends Dog{
    public void show(String name,int price){
        super.show("BoB",100000);
        System.out.println(name);
        System.out.println(price);
    }
    public void display(String name){
        super.display("Kishor");
        System.out.println(name);
    }
    public static void main(String []args){
        Cat c1=new Cat();
        c1.show("Pinki",20000);
        c1.display("Pinki");
    }
}

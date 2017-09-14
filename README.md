# HelloWorld
# This is the first GitHub project.
public class HelloWorld{
  public static void main(String[] args){
    HelloWorld2 hw2 = new HelloWorld2();
    hw2.setName("Hello World 2...");
    hw2.setAge(20);
    System.out.println(hw2.getName()+hw2.getAge());//20170914
    System.out.println(hw2.getName()+hw2.getAge());//20170914
  }
}
private class HelloWorld2{
  private String name = null;
  private int age = 0;
  
  private void setNamw(String name){
    this.name = name;
  }
  
  private String getName(){
    return this.name;
  }
  
  private void setAge(int age){
    this.age = age;
  }
  
  private int getAge(){
    return this.age;
  }

}

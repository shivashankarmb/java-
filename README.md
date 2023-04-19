class Student
{
  private int reno;
  private String name;

  public Student (int r, String n)
  {
    reno = r;
    name = n;
  }
  public void display ()
  {
    System.out.println ("Relonumber:" + reno);
    System.out.println ("Name:" + name);

  }
}

class Demo
{
  public static void main (String[]args)
  {
    Student S = new Student (23, "shiva");
      S.display ();
  }
}

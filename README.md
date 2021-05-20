
public class Jala {
	static int id=10;
	static String name ="Sai";
	int ht = 5;
	String city = "Hyd";
	static void getname()
	{
		System.out.println(name);
	}
	static void getid()
	{
		System.out.println(id);
	}
	void getcity()
	{
		System.out.println(city);
	}
	void getht()
	{
		System.out.println(ht);
	}
	public static void main(String[] args) {
		Jala j = new Jala();
		getname();
		getid();
		j.getcity();
		j.getht();
	}
}

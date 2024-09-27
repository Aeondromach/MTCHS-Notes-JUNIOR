```
public class Wrestler
{
	//instance variables
	private double height;
	private double weight;
	private String name;
	
	public Wrestler(double height, double weight, String name) {
		this.height = height;
		this.weight = weight;
		this.name = name;
	}
	
	public void  setName(String name) {
		this.name = name;
	}
	
	public String getName() {
		return this.name;
	}
	
	public String toString() {
		String output = "";
		output += "Name: " + this.name;
		output += "\nWeight: " + this.weight;
		return output;
	}
}
```
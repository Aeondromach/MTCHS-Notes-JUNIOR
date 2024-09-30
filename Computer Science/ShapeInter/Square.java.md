```
public class Square implements ShapeInterface{

  

    private double sideLength;

  

    public Square(double sideLength) {

        this.sideLength = sideLength;

    }

  

    public double area() {

        return Math.pow(this.sideLength, 2);

    }

  

    public double perimeter() {

        return this.sideLength*4;

    }

}
```
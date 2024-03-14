package overriding_overloading;

class Square {
    int side;

    Square(int side) {
        this.side = side;
    }

    void perimeter() {
        System.out.println("Perimeter of square: " + 4 * side);
    }
}

class Circle {
    int radius;

    Circle(int radius) {
        this.radius = radius;
    }

    void perimeter() {
        System.out.println("Perimeter of circle: " + 2 * Math.PI * radius);
    }
}

class Triangle {
    int side1, side2, side3;

    Triangle(int side1, int side2, int side3) {
        this.side1 = side1;
        this.side2 = side2;
        this.side3 = side3;
    }

    void perimeter() {
        System.out.println("Perimeter of triangle: " + (side1 + side2 + side3));
    }
}

public class Main {
    public static void main(String[] args) {
        Square square = new Square(5);
        Circle circle = new Circle(4);
        Triangle triangle = new Triangle(2, 5, 4);

        square.perimeter();
        circle.perimeter();
        triangle.perimeter();
    }
}

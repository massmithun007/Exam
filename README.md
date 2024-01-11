class Math {
    void add() {
        System.out.println("a+b");
    }
}

class Multiply extends Math {
    void mul() {
        System.out.println("a*b");
    }
}

public class Maths {
    public static void main(String[] args) {
        Multiply s = new Multiply();
        s.add();
        s.mul();
    }
}



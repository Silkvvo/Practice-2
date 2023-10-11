public class Student {
    private String name;
    private int id;
    private int yearOfStudy;

    public Student(String name, int id) {
        this.name = name;
        this.id = id;
        this.yearOfStudy = 2;
    }
    public String getName() {
        return name;
    }
    public int getId() {
        return id;
    }
    public void incrementYearOfStudy() {
        yearOfStudy++;
    }
    public int getYearOfStudy() {
        return yearOfStudy;
    }
    public static void main(String[] args) {
        
        Student student1 = new Student("Miras", 1);
        System.out.println("Name: " + student1.getName());
        System.out.println("ID: " + student1.getId());
        System.out.println("Year of Study: " + student1.getYearOfStudy());
        student1.incrementYearOfStudy();
        System.out.println("Incriment Year of Study: " + student1.getYearOfStudy());
    }
}

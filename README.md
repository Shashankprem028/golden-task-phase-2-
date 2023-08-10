import java.util.ArrayList;
import java.util.List;

class Student {
    private int id;
    private String name;
    private double balance;
    // Constructor, getters, setters
}

class Course {
    private String courseCode;
    private String courseName;
    private double feeAmount;
    // Constructor, getters, setters
}

class Transaction {
    private Student student;
    private Course course;
    private String transactionDate;
    private double amount;
    // Constructor, getters, setters
}

public class FeesManagementApp {
    private List<Student> students = new ArrayList<>();
    private List<Course> courses = new ArrayList<>();
    private List<Transaction> transactions = new ArrayList<>();

    public void addStudent(Student student) {
        // Add student to the students list
    }

    public void addCourse(Course course) {
        // Add course to the courses list
    }

    public void recordPayment(Student student, Course course, double amount) {
        // Create a new transaction and update student's balance
    }

    public void viewStudentDetails(int studentId) {
        // Display student's details including balance
    }

    public void viewCourseDetails(String courseCode) {
        // Display course details including fee
    }

    public static void main(String[] args) {
        // Initialize the application and handle user interactions
    }
}

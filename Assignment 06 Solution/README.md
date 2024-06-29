# Student Management System

This project is a student management system implemented in Python using object-oriented programming concepts. The system allows users to manage student records, including adding new students, adding marks for subjects, displaying student details, and more.

## Features

- **Add New Student**: Users can add a new student to the system by providing their name, roll number, and age.
- **Add Marks**: Users can add marks for subjects to existing students by specifying the student's roll number, subject name, and marks obtained.
- **Display Student Details**: Users can view the details of a specific student by entering their roll number.
- **Display Total Students**: Users can view the total number of students currently registered in the system.
- **Exit**: Users can exit the system.

## Classes

### `Student`

- Represents a student with attributes such as name, roll number, age, and marks.
- Provides methods to add marks, calculate total marks, calculate percentage, display details, and more.
- Includes class variables to keep track of the total number of students.

### `TopperStudent`

- Inherits from the `Student` class.
- Overrides the `calculate_percentage` method to calculate the percentage with bonus marks for toppers.

## Usage

1. Run the `main()` function to start the student management system.
2. Choose options from the menu to perform various actions such as adding new students, adding marks, displaying details, and more.
3. Follow the prompts to enter required information and interact with the system.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


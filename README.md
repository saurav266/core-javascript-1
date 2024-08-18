function gradeStudent(marks) {
    if (marks > 90) {
        return 'A Grade';
    } else if (marks >= 70 && marks <= 90) {
        return 'B Grade';
    } else if (marks >= 50 && marks < 70) {
        return 'C Grade';
    } else {
        return 'F Grade';
    }
}

// Example usage:
let studentMarks = 85;
console.log(`The student's grade is: ${gradeStudent(studentMarks)}`);

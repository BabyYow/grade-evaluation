# grade-evaluation
This is my work for assignment in coding                    
*******************************************************************

#include <iostream>
using namespace std;

int main()
{
    double quiz, rec, assig, longQuiz, majorExam;

    cout << "Quiz Score: ";
    cin >> quiz;
    double quiz_grade = quiz * 0.35;
    cout << endl;

    cout << "Recitation Score: ";
    cin >> rec;
    double rec_grade = rec * 0.05;
    cout << endl;

    cout << "Assignment Score: ";
    cin >> assig;
    double assig_grade = assig * 0.05;
    cout << endl;

    cout << "Long Quiz Score: ";
    cin >> longQuiz;
    double longQuiz_grade = longQuiz * 0.15;
    cout << endl;

    cout << "Major Exam Score: ";
    cin >> majorExam;
    double exam_grade = majorExam * 0.4;
    cout << endl;

    double final_grade = quiz_grade + rec_grade + assig_grade + longQuiz_grade + exam_grade;

    if (final_grade >= 75 && final_grade < 78) {
        cout << "The equivalent literal grade is C" << endl;
    } else if (final_grade >= 78 && final_grade < 81) {
        cout << "The equivalent literal grade is B-" << endl;
    } else if (final_grade >= 81 && final_grade < 84) {
        cout << "The equivalent literal grade is B+" << endl;
    } else if (final_grade >= 84 && final_grade < 87) {
        cout << "The equivalent literal grade is B" << endl;
    } else if (final_grade >= 87 && final_grade < 91) {
        cout << "The equivalent literal grade is A-" << endl;
    } else if (final_grade >= 91 && final_grade < 96) {
        cout << "The equivalent literal grade is A+" << endl;
    } else if (final_grade >= 96 && final_grade <= 100) {
        cout << "The equivalent literal grade is A" << endl;
    } else {
        cout << "The equivalent literal grade is F" << endl;
    }

    cout << "This code was created by Saligao, R" << endl; // Your name as the creator

    return 0;
}

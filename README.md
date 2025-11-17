#include <stdio.h>

int main() {
    float attendance;

    // Ask for attendance
    printf("Enter your attendance percentage: ");
    scanf("%f", &attendance);

    // Check attendance
    if (attendance < 75) {
        printf("tumchya jivnach vatol zalay\n");
    } else {
        printf("Attendance is sufficient,Best luck for future.\n");
    }

    return 0;

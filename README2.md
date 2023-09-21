#include <stdio.h>

// enum 정의
enum Weekday {
    SUNDAY,
    MONDAY,
    TUESDAY,
    WEDNESDAY,
    THURSDAY,
    FRIDAY,
    SATURDAY
};

int main() {
    // enum 변수 선언
    enum Weekday today;

    // 변수에 요일 할당
    today = WEDNESDAY;

    // 오늘의 요일 출력
    switch (today) {
        case SUNDAY:
            printf("오늘은 일요일입니다.\n");
            break;
        case MONDAY:
            printf("오늘은 월요일입니다.\n");
            break;
        case TUESDAY:
            printf("오늘은 화요일입니다.\n");
            break;
        case WEDNESDAY:
            printf("오늘은 수요일입니다.\n");
            break;
        case THURSDAY:
            printf("오늘은 목요일입니다.\n");
            break;
        case FRIDAY:
            printf("오늘은 금요일입니다.\n");
            break;
        case SATURDAY:
            printf("오늘은 토요일입니다.\n");
            break;
        default:
            printf("잘못된 요일입니다.\n");
    }

    return 0;
}

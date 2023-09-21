#include <stdio.h>

// Union 정의
union Data {
    int i;
    float f;
};

int main() {
    union Data data;

    // 정수를 설정하고 출력
    data.i = 10;
    printf("정수 값: %d\n", data.i);

    // 부동 소수점 수를 설정하고 출력
    data.f = 3.14;
    printf("부동 소수점 값: %f\n", data.f);

    return 0;
}

#include<stdio.h>

int main(void) {

    int i; //세로 갯수
    int j; //*출력 갯수 변수
    int n; //입력 변수
    scanf_s("%d", &n);
    for (i = 1; i <= n; i++) {
        for (j = 0; j < i; j++)
            putchar('*');
        putchar('\n');
    }
    return 0;
}

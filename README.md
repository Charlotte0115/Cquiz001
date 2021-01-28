# Cquiz001
#include <stdio.h>
#include <cs50.h>

int main(void)
{
    int deposite = get_int("고객의 목표 금액이 얼마입니까? \n");
    printf("만기시 받게 되는 금액은 %.1f", deposite*1.012);
}

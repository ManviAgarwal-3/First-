# CAT Theory
2
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    char s[500];
    scanf("%s",s);
    int upper=0,lower=0,white_space=0,digits=0,special=0;
    int i=0;
    while(s[i] != '\0')
    {
        if (s[i]>='A' && s[i]<='Z')
        {
            upper++;
        }
        else if(s[i]>='a' && s[i]<='z')
        {
            lower++;
        }
        else if(s[i]>='0' && s[i]<='9')
        {
            digits++;
        }
        else if(s[i] == ' ')
        {
            white_space++;
        }
        else
        {
            special++;
        }
        ++i;
    }
    printf("Uppercase letters %d\n",upper);
    printf("Lowercase letters %d\n",lower);
    printf("Digits %d\n",digits);
    printf("White spaces %d\n",white_space);
    printf("Special Characters %d\n",special);
    return 0;
}

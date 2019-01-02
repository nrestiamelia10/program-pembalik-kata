#include <stdio.h>
#include <string.h>
#include  <ctype.h>

char a[100];
int b,c;
int main()

{
    printf( " Masukkan kata   :");
    gets(a);
    strrev(a);
    printf( " Balikkan kata   : %s",a);
}

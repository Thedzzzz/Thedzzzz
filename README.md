- #include <stdio.h>
#include <stdlib.h>
int main()
{
    char s[]= "DaiThedznhatxom123";
    printf "Nhap"


    char c[1000];
    FILE *fptr;

    if ((fptr = fopen("C:\\Users\\DAI THE\\Desktop\\so_nguyen.dat", "r")) == NULL)
    {
        printf("Error! opening file");
        exit(1);
    }
    for(int i =0; i< 90; i++){
    fscanf(fptr,"%s", &c);
    printf("%s\n", c);
    }
    fclose(fptr);
    return 0;
}

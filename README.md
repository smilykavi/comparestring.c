# comparestring.c
#include<stdio.h>
#include,coio.h>
main()
{
int i=0;
char s1[100],s2[100];
printf("enter s1 and s2");
gets(s1);
gets(s2);
while(s1[i]==s2[i]&&s1[i]!='\0')
{
if(s1[i]<s2[i])
{
printf("not");
}
else if(s1[i]>s2[i])
{
printf("not");
}
else
{
printf("same");
}
}
getch();
}

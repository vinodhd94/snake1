# snake1
#include<stdio.h>
#include<conio.h>
#include<dos.h>
#include<graphics.h>
#include<iostream.h>
void main()
{
int gd=DETECT,gm,i,j;
initgraph(&gd,&gm,"C:\\tc\\bgi");
rectangle(50,50,200,200);
getch();
for(i=0;i<139;i++)
{
rectangle(50,50,200,200);
line(52+i,52,60+i,52);
delay(20);
cleardevice();
}
getch();
for(j=0;j<138;j++)
{
rectangle(50,50,200,200);
line(198,52+j,198,60+j);
delay(20);
cleardevice();
}
getch();
for(int n=0;n<141;n++)
{
rectangle(50,50,200,200);
line(190-n,198,198-n,198);
delay(30);
cleardevice();
}

getch();
}


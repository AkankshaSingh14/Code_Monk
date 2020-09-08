/*echo "# Code_Monk" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/AkankshaSingh14/Code_Monk.git
git push -u origin master
*/    

#include <stdio.h>
int main()
{
int t;
scanf("%d", &t);
while(t--)
{
long int n,k,pos,size, i;
scanf("%lld %lld", &n,&k);
long int a[n],x;
k=k%n;
for(i=0;i<n;i++)
{
scanf("%lld", &x);
pos=((i+k)>=n)?((i+k)-n):(i+k);
a[pos]=x;
}
for(i=0;i<n;i++)
{
printf("%lld ",a[i]);
}
printf("\n");
}
return 0;
}

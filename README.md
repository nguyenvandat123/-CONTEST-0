# -CONTEST-0
**Bài 1. Print Hello World**
```sh 
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a;
    scanf("%d",&a);
    printf("%d\n",a);
    printf("%s\n","Hello World !");
    printf("%s\n","28tech C++ programming !");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 2. Print number**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a;
    long long b;
    char x;
    float c;
    double d;
    
    scanf("%d\n",&a);
    scanf("%lld\n",&b);
    scanf("%c\n",&x);
    scanf("%f\n",&c);
    scanf("%lf\n",&d);
    printf("%d\n",a);
    printf("%lld\n",b);
    printf("%c\n",x);
    printf("%.2f\n",c);
    printf("%.9lf\n",d);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 3. Print expression**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y,z,t;
    scanf("%d %d %d %d\n",&x,&y,&z,&t);
    printf("%d,%d,%d,%d\n",y,z,x,t);
    printf("%lld\n",(long long)x+y+z+t);
    printf("%lld\n",(long long)x-y+1ll*z*t);
    

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```

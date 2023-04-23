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
**Bài 4. Hàm pow**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d %d\n",&a,&b);
    printf("%lld",(long long)pow(a,b));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 5. Hàm sqrt và cbrt**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a;
    scanf("%d\n",&a);
    printf("%.2lf\n",sqrt(a));
    printf("%.3lf\n",cbrt(a));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 6. Hàm ceil, floor, round**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    double a;
    scanf("%lf\n",&a);
    printf("%d\n",(int)floor(a));
    printf("%d\n",(int)ceil(a));
    printf("%d\n",(int)round(a));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 7. Chữ số cuối cùng và 2 chữ số cuối cùng**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long n;
    scanf("%lld\n",&n);
    printf("%d\n",n%10);
    printf("%d\n",n%100);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 8. Phép chia**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d %d\n",&b,&a);
    printf("%d\n", a/b);
    printf("%.2f\n",(float)a/b);
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 9. Xóa số**
```sh 
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a;
    scanf("%lld\n",&a);
    printf("%lld\n",a/1000);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 10. Phép chia dư**
```sh 
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d     %d\n",&a,&b);
    printf("%d\n",a%b);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 11. Nhân chia**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d\n",&n);
    printf("%lld\n",1ll*n*2);
    printf("\n%lld\n",1ll*n*10);
    printf("\n%d\n",n/2);
    printf("\n%.3lf\n",(double)n/2);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 12. Hàm F(x, y)**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
int main()
{
    int a,b;
    scanf("%d %d\n",&a,&b);
    printf("%lld\n",5ll*a+2ll*b+1ll*a*b);
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 13. Lớn nhất, nhỏ nhất**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y,z,t;
    scanf("%d\n",&x);
    scanf("%d\n",&y);
    scanf("%d\n",&z);
    scanf("%d\n",&t);
    printf("%d\n",(int)fmax(x,y));
    printf("%d\n",(int)fmin(z,t));
    printf("%d\n",(int)fmax(x,fmax(y,z)));
    printf("%d\n",(int)fmin(x,fmin(y,fmin(z,t))));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 14. Number in range**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a,b;
    scanf("%lld %lld\n",&a,&b);
    printf("%lld",b-a+1);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 15. Mua vở**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a,b;
    scanf("%lld %lld\n",&a,&b);
    printf("SO VO MUA DUOC LA : %lld !!!!!",(long long) floor(a/b));
   

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```
**Bài 16. Cout**
```sh
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y,z,t;
    scanf("%d %d %d %d\n",&x,&y,&z,&t);
    printf("%d  %d  %d  %d\n",x,y,z,t);
    printf("\n%d--%d--%d--%d\n",y,z,x,t);   
    printf("\n%lld,%lld,%lld,%lld\n",2ll*x,3ll*y,4ll*z,5ll*t);
    printf("\n%s\n","KET THUC !!");

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```

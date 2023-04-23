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
**Hàm ceil, floor, round**
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

#include <cstdio>
#define MAXN 32
using namespace std;
int main()
{
    unsigned int a,b,d,sum,re[MAXN];//re[]倒序存入sum转换成d进制的每一位,re[0]存sum最高位
    scanf("%d%d%d",&a,&b,&d);
    sum = a + b;//a与b的十进制和
    int i = 0;
    do{
        re[i++] = sum % d;
        sum /= d;
    }while(sum != 0);
    while(i--){//上面的循环中i多加了1
        printf("%d",re[i]);
    }
    return 0;
}

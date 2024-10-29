 直接输出几个书中的最大值
#include <iostream>

int main() {
    int a, b, c;
    
    // 输入三个整数
    std::cin >> a >> b >> c;
    
    // 比较并输出最大值
    if (a > b && a > c) {
        std::cout << a << std::endl;
    } else if (b > a && b > c) {
        std::cout << b << std::endl;
    } else {
        std::cout << c << std::endl;
    }
    
    return 0;
}

  输出max=
#include <iostream>
using namespace std;
int main() {
    int a, b, c;
    cin >> a >> b >> c;
    int max = a;
    if (b > max) {
        max = b;
    }
    if (c > max) {
        max = c;
    }
    cout << "max=" << max << endl;
    return 0;
}


python
# 读取输入的一行数字，并转换为整数列表
a, b, c = map(int, input().split())

# 使用max函数找出最大值并打印
if a > b and a > c:
    print(a)
elif b > a and b > c:
    print(b)
else:
    print(c)
 


 

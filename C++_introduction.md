# Introduction
1. [Say "Hello, World!" With C++](https://www.hackerrank.com/challenges/cpp-hello-world/problem?isFullScreen=true)
```cpp
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    printf("Hello, World!");
    return 0;
}
```
2. [Input and Output](https://www.hackerrank.com/challenges/cpp-input-and-output/problem?isFullScreen=true)
```cpp
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int a;
    int b;
    int c;
    cin >> a >> b >> c;
    cout << a+b+c;  
    return 0;
}
```
3. [Basic Data Types](https://www.hackerrank.com/challenges/c-tutorial-basic-data-types/problem?isFullScreen=true)
```cpp
#include <iostream>
#include <cstdio>
using namespace std;

int main(){
    int firstInput;
    long secondInput;
    char thirdInput;
    float fourthInput;
    double fifthInput;
    
    scanf("%d %ld %c %f %lf", &firstInput, &secondInput, &thirdInput, &fourthInput,&fifthInput);
    
    printf("%d\n%ld\n%c\n%f\n%lf", firstInput, secondInput, thirdInput, fourthInput, fifthInput);
    return 0;
}
```
4. 

1. [Vector-Sort](https://www.hackerrank.com/challenges/vector-sort/problem?isFullScreen=true)
```cpp

```
2. [Strings](https://www.hackerrank.com/challenges/c-tutorial-strings/problem?isFullScreen=true)
```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
	string a;
    string b;
    
    cin >> a >> b;
    
    cout << a.size()<<" "<< b.size()<<'\n';
    cout << a+b << '\n';
    cout <<b[0]<<a.substr(1)<<" "<<a[0]<<b.substr(1);
  
    return 0;
}
```
3. [StringStream](https://www.hackerrank.com/challenges/c-tutorial-stringstream/problem?isFullScreen=true)
```cpp
#include <sstream>
#include <vector>
#include <iostream>
using namespace std;

vector<int> parseInts(string str) {
	stringstream ss (str);
    vector<int> integers;
    int x;
    char ch;
    while (ss >> x){
      integers.push_back(x);
      ss >> ch;  
    } 
    return integers;
}

int main() {
    string str;
    cin >> str;
    vector<int> integers = parseInts(str);
    for(int i = 0; i < integers.size(); i++) {
        cout << integers[i] << "\n";
    }
    
    return 0;
}
```
4. 

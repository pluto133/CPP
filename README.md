# CPP <https://mermaid-js.github.io/mermaid/#/>
C++ programming learning
```CPP
#include <iostream>
int main(){  
  using namespace std;
  cout<<“hello world!"<<endl;
  return 0;
}
```
 
```mermaid
graph LR;
    A[Zero]-->B[One];
```
<!--
Comments
-->

```mermaid
gantt
dateFormat  YYYY-MM-DD
title |-- C++ programming learnning schedule --|
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```
```mermaid
    gitGraph
       commit
       commit
       branch Book
       commit
       commit
       commit
       checkout main
       commit
       commit
```

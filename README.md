#include <iostream>

using namespace std;

class Node{
 public:
 char data;
 Node*next ;
};

 void printList(Node*n){
     while(n!=NULL){
         cout << n->data;
         n=n->next;
         
         
     }
 }
 
}

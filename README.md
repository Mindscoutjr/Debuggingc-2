#include <iostream>
  
using namespace std; 

int gValue=10; 

void extra() 

{

    cout <<"\ngValue"<<gValue;
    
    
}

int main()

{ 

    extra();
    
    {
    
        int gValue = 20; 
        
        cout<<"\ngvalue"<<gValue;
        
        cout<<"\ngvalue"<<gValue;
        
    }
    
    return 0;
    
} 

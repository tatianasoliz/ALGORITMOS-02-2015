# ALGORITMOS-02-2015
// Algoritmos y programacion I

#include "stdafx.h"
#include <iostream>  
#include "math.h"  
    using namespace std;  
    int main(){  
        float a,b,c;  
        cout<<"Ingresa coeficiente cuadratico"<<endl;  
        cin>>a;  
        cout<<"Ingresa coeficiente lineal"<<endl;  
        cin>>b;  
        cout<<"Ingresa constante"<<endl;  
        cin>>c;  
        double disc=pow(b,2)-4*a*c;  
        if(a!=0){  
              if(disc<0){  
              cout<<"Tiene raices imaginarias";  
              }else{  
              double x1=(-b+sqrt(disc))/(2*a);  
              double x2=(-b-sqrt(disc))/(2*a);  
              cout<<"X1 = "<<x1<<" X2 = "<<x2;  
            }  
          }else{  
         cout<<"El coeficiente cuadratico debe ser diferente de 0";  
          }  
       return 0;  
    }  
  {
	  neto[i]=vector[i]-vector[i]*iva-vector[i]*afp;  
  }
	else
  {
	  neto[i]=vector[i];
  }
  p=p+neto[i];
 }
 s=p/n;
 cout<<endl<<"El promedio de los salarios neto es:"<<s<<endl; 
}

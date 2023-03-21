#include <stdlib.h>    
#include <stdio.h>    
    
int main(){    
    int n,i; //聲明變數n和i    
    scanf("%d",&n); //讀取輸入的整數值。    
    for(i=2;i<n;i++){ //聲明變數i為2，當i小於n，執行循環內的程式，執行完把i+1    
        if(n%i==0){ //n除以i的餘數是否等於0   
            break;    
        }    
    }    
    if(i==n){  //若i=n顯示YES，反之呈現NO  
        printf("YES\n");    
    }    
    else{    
        printf("NO\n");    
    }    
}  

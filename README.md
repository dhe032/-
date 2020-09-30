#include <stdio.h>
int main(){
	int a,b=0;
	scanf("%d",&a);
	for(int i=0;i<10;i++){
		b+=a%10;
		a=a/10;
	}
	if(b%7==4){
		printf("suspect");
	}
	else{
		printf("citizen");
	}
}

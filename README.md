# Sums-divisible-by-3-Problem-Code-DIV3
#include <stdio.h>

int main(void) {
	int t;
	scanf("%d",&t);
	while(t--){
	    int zero,one,two;
	    scanf("%d%d%d",&zero,&one,&two);
	    if(one<=two){
	        printf("%d\n",zero+one+((two-one)/3));
	    }
	    else{
	        printf("%d\n",zero+two+((one-two)/3));
	    }
	}
}

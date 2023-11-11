# term-frequency
Author-Kalyani Shahale

The objectiv is to calculate the frequency at which each terms is used within indivisual resources as well as collectively.

#include<stdio.h>
#include<string.h>
struct term{
	char term[20];
};
int count=0;
int cal_Frequency(char term[]){
	if(term==str){
		++count;
		cal_Frequency(term[]);
	}
	else
	    return count;
} 

int main(){
    int choice, i;
    struct term t;
	printf("\n1. Shrinkflation");
	printf("\n2. Stagnant");
	printf("\n3. Pandemic");
	printf("\n4. Conflict");
	printf("\n5. Unemployment");
	printf("\n6. Turmoil");
	printf("\n7. Reform");
	printf("\n8. Dutch Disease");
	printf("\n9. Purchasing Power Parity");
	printf("\n\nEnter a choice and term: ");
	scanf("%d %s", &choice, &t.term);
	switch (choice){
	case 1:
		printf("\n\nTerm- %s\nDefinition- the practice of reducing the size or quantity of a product while the price of the product remains the same or slightly increases", t.term);
	    for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term[]));
		}
	    break;
	case 2:
		printf("\n\nTerm- %s\nDefinition- not flowing, not active, changing, or progressing", t.term);
	    for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
	    break;
	case 3:
		printf("\n\nTerm- %s\nDefinition- widespread occurrence of an infectious disease over a whole country or the world at a particular time", t.term);
    	for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
    	break;
    case 4:
    	printf("\n\nTerm- %s\nDefinition- a serious disagreement or argument, typically a protracted one", t.term);
	    for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
	    break;
	case 5:
		printf("\n\nTerm- %s\nDefinition- the state of being unemployed", t.term);
		for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
    	break;
    case 6:
    	printf("\n\nTerm- %s\nDefinition- a state of great disturbance, confusion, or uncertainty", t.term);
    	for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
    	break;
    case 7:
    	printf("\n\nTerm- %s\nDefinition- make changes in order to improve it", t.term);
	    for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
	    break;
	case 8:
		printf("\n\nTerm- %s\nDefinition- an economic phenomenon where the rapid development of one sector of the economy", t.term);
		for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
    	break;
    case 9:
    	printf("\n\nTerm- %s\nDefinition- the rates of currency conversion that try to equalise the purchasing power of different currencies, by eliminating the differences in price levels between countries", t.term);
	    for(i=0;i<8;i++){
	    	printf("\nNo. of times the term has been used in input %d- %d", i, cal_Frequency(term));
		}
	    break;
    default:
    	printf("Wrong choice");
	}
	
	return 0;
}

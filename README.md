this is my practice 
#include<stdio.h>
#include<stdlib.h>

#define PI 3.14159

void printNameCourse();
float computeCircleArea(float FR);

int main (){
	printNameCourse();
	
	
	float area;
	float radius;
	
	radius = 10;
	
	area = computeCircleArea(radius);
	
	printf("\n\t The area is %f\n", area);
	
	return EXIT_SUCCESS;
}

void printNameCourse(){
	puts("\n\t Diego Catindig");
	puts("\n\t Hello LBYEC72");
	puts("\n\t 3rd compile!");
}

float computeCircleArea(float FR){
	return PI * FR * FR;
}

printf("https://github.com/catdiegoo/LBYEC72-Practice/blob/master/hello2.png")

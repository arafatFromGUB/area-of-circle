!! area-of-circle--- its like a real life problem : to calculate any circle's area

#include <stdio.h>

int main()
{
  float radius, area;

  printf("Enter the radius of a circle\n");

  scanf("%f", &radius);

  area = 3.14159*radius*radius;

  printf("Area of the circle = %.2f\n", area); 

  return 0;
}

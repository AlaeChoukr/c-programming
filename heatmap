#include <stdio.h>
#include <stdlib.h>




char **  grille ( int x, int y )
{
  char ** tableau2d = (char**)calloc(x,sizeof(char*));

for(int i = 0; i <x; i++)


    tableau2d[i] = (char*)calloc(y,sizeof(char));



for(int i=0;i<x;i++) {
        for(int j=0;j<y;j++) {
tableau2d[i][j]='.';
}
}
return tableau2d ;
}

char **  remplissage ( char** C )
{
char ** temp = C ;
int z = 1 ;
int w = 1 ;
int xmax = 0 ; 
 for(int i=0;i<10;i++) {
     for(int j=0;j<10;j++) {
     if(temp[i][j] == 'X')
      //{
      //if (i>(10-1)-i)
      //{
      
      	// xmax = i ; }
      //else 
      	//{
      	//xmax = (10-1)-i  ; } 
      for (int s = 0; s<7 ;s++)
      {
      		for (int a = -z; a<=z;a++)
      		{
      			printf("a = %d\n", a);
        		for (int b = -w; b<=w;b++)
        		{
        			printf("b = %d\n", b);
        			if (i+a>=10|| j+b>=10 || i+a<0 ||j+b<0 ||temp[i+a][j+b] != '.') 
        			continue ; 
        			
        			else 
          			temp[i+a][j+b] = '0' + s;
          			
        }
      }
      temp[i][j] = 'X' ;
      z++ ; 
      w++ ; 
      }
           }}}
           return temp ; }
         
         
         
       
     
     
     
     
     
     
     
     
     
     





int main()
{
  char ** C = grille(10,10) ;
  C[5][8] = 'X' ;
  //C[7][8] = 'Y' ;
  char ** V = remplissage(C) ;
 
  printf("hna\n");
 
  for(int i=0;i<10;i++) {

        for(int j=0;j<10;j++) {
printf("%4c ",V[i][j]) ;
}
printf("\n") ;
}
 return 0 ;
 }
	

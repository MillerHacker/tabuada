# tabuada
 

 #include <stdio.h>
#include <stdlib.h>

int divisao ()
{
	int b, c;
	
	printf ("Digite o numero da tabuada: ");
	scanf ("%d", &b);
	
	printf ("\n");
	
	if ((b>=11) || (b<1))
		{
			printf ("\nNumero invalido.\n");
		}
		else
			if (b==1)
				{
					for (c=1; c<=10; c++)
					{
				
						printf ("\t%d / %d = %d\n\n", c, b, c/b); 
				
					}
				}
				else
					if (b==2)
					{
						for (c=2; c<=20; c=c+2)
						{
				
							printf ("\t%d / %d = %d\n\n", c, b, c/b); 
				
						}
					}
					else
						if (b==3)
						{
							for (c=3; c<=30; c=c+3)
							{
				
							printf ("\t%d / %d = %d\n\n", c, b, c/b); 
				
							}
						}
						else
							if (b==4)
							{
								for (c=4; c<=40; c=c+4)
								{
									
									printf ("\t%d / %d = %d\n\n", c, b, c/b); 
									
								}
							}
							else
								if(b==5)
								{
									for (c=5; c<=50; c=c+5)
									{
											
										printf ("\t%d / %d = %d\n\n", c, b, c/b); 
											
									}	
								}
								else
									if (b==6)
									{
										for (c=6; c<=60; c=c+6)
										{
											
											printf ("\t%d / %d = %d\n\n", c, b, c/b); 
											
										}
									}
									else
										if(b==7)
										{
											for (c=7; c<=70; c=c+7)
											{
												
												printf ("\t%d / %d = %d\n\n", c, b, c/b); 
												
											}
										}
										else
											if (b==8)
											{
												for (c=8; c<=80; c=c+8)
												{
													
													printf ("\t%d / %d = %d\n\n", c, b, c/b); 
													
												}	
											}
											else
												if (b==9)
												{
													for (c=9; c<=90; c=c+9)
													{
														
														printf ("\t%d / %d = %d\n\n", c, b, c/b); 
														
													}
												}
												else
													if(b==10)
													{
														for (c=10; c<100; c=c+10)
														{
															
															printf ("\t%d / %d = %d\n\n", c, b, c/b); 
															
														}
			
													}
	
return c/b;
}




int multiplicacao ()
{
	int b, c;
	
	printf ("Digite o numero da tabuada: ");
	scanf ("%d", &b);
	
	printf ("\n");
	
	
	if ((b>=11) || (b<1))
		{
			printf ("\nNumero invalido.\n");
		}
		else
		{
		
			for (c=0; c<11; c++)
			{
				
				printf ("\t%d * %d = %d\n\n", b, c, b*c); 
				
			}
			
		}
	
	
return b*c;
}


int subtracao ()
{
	int b, c;
	
	printf ("Digite o numero da tabuada: ");
	scanf ("%d", &b);
	
	printf ("\n");
	
		
		if ((b>=11) || (b<1))
		{
			printf ("\nNumero invalido.\n");
		}
		else
			if (b==1)
			{
				for (c=2; c<=11; c++)
				{
			
					printf ("\t%d - %d = %d\n\n", c, b, c-b); 
			
				}
			}
			else
				if (b==2)
				{
					for (c=3; c<=12; c++)
					{
			
						printf ("\t%d - %d = %d\n\n", c, b, c-b); 
			
					}
				}
				else
					if (b==3)
					{
						for (c=4; c<=13; c++)
						{
			
						printf ("\t%d - %d = %d\n\n", c, b, c-b); 
			
						}
					}
					else
						if (b==4)
						{
							for (c=5; c<=14; c++)
							{
								
								printf ("\t%d - %d = %d\n\n", c, b, c-b); 
								
							}
						}
						else
							if(b==5)
							{
								for (c=6; c<=15; c++)
								{
										
									printf ("\t%d - %d = %d\n\n", c, b, c-b); 
										
								}	
							}
							else
								if (b==6)
								{
									for (c=7; c<=16; c++)
									{
										
										printf ("\t%d - %d = %d\n\n", c, b, c-b); 
										
									}
								}
								else
									if(b==7)
									{
										for (c=8; c<=17; c++)
										{
											
											printf ("\t%d - %d = %d\n\n", c, b, c-b); 
											
										}
									}
									else
										if (b==8)
										{
											for (c=9; c<=18; c++)
											{
												
												printf ("\t%d - %d = %d\n\n", c, b, c-b); 
												
											}	
										}
										else
											if (b==9)
											{
												for (c=10; c<=19; c++)
												{
													
													printf ("\t%d - %d = %d\n\n", c, b, c-b); 
													
												}
											}
											else
												if(b==10)
												{
													for (c=11; c<=20; c++)
													{
														
														printf ("\t%d - %d = %d\n\n", c, b, c-b); 
														
													}	
												}
								
	
	
	
	
return c-b;
}



int soma ()
{
	int b, c;
	
	printf ("Digite o numero da tabuada: ");
	scanf ("%d", &b);
	
	printf ("\n");
	
	if ((b>=11) || (b<1))
	{
		printf ("\nNumero invalido.\n");
	}
	else
	{
	
		for (c=0; c<11; c++)
		{
		
			printf ("\t%d + %d = %d\n\n", b, c, b+c); 
		
		}
	
	}	
	
return b+c;
}





int main()

{
	
	int r;
	int y;
	
	
	do	{
	
	printf ("\n\n");
	printf ("###########################################\n\n");
	printf ("\t  CALCULADORA INTELIGENTE\n\n");
	printf ("###########################################");
	
	printf ("\n\n");
	
	printf ("Digite 1 para a tabuada de ADICAO: \n");
	printf ("Digite 2 para a tabuada de SUBTRACAO; \n");
	printf ("Digite 3 para a tabuada de MULTIPLICACAO: \n");
	printf ("Digite 4 para a tabuada de DIVISAO: \n");
	
	printf ("\n\n");
	
	scanf("%d", &r);
	
	printf ("\n\n");
	
	switch (r)
	
	{
		
		case 1:
		
		{
			
			soma ();
			
			break;	
		}
		
		case 2:
		
		{
			
			subtracao ();
			
			break;	
		}
		
		case 3:
			
		{
			
			multiplicacao ();
			
			break;
		}	
		
		case 4:
			
		{
			
			divisao ();
			
			break;
		}
		
		default:
			
		{
			printf ("*****************\n\n");
			printf ("Opcao invalida :(\n\n");
			printf ("*****************\n\n");
				
		
		}
		
		
	}
	
	printf ("\nDeseja continuar? [1 sim|0 nao] ");
	scanf ("%d", &y);
	
		
	
	} while (y==1);
	
	
	printf ("\n\n");
	system ("pause");
	
	
	
return 0;
}

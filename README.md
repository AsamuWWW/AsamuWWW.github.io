# AsamuWWW.github.io
I^m Asamu!!!

Hello everyone !
Nice to meet you !

void sort(Student a[], int n)
{
	double temp;
	int max;
	for (int i = 0; i < n - 1; i++)
	{
		max = i;
		for (int j = i + 1; j < n; j++)
		{
			if (a[j].score > a[max].score)
			{
				max = j;
			}
				Student temp = a[i];
				a[i] = a[max];
				a[max] = temp;	
		}
	}
}

Thank your reading !
<!--more-->

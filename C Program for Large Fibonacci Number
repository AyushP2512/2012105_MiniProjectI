#include <stdio.h>
#define Max 5000

void adding(char a[], char b[], char p[])
{
  int k = 0;
  for (int i = Max - 1; i >= 0; i--)
  {
    int d = (a[i] - '0') + (b[i] - '0') + k;
    p[i] = (d % 10) + '0';
    k = d / 10;
  }
}

void copying(char a[], char b[])
{
  for (int i = Max - 1; i >= 0; i--)
    a[i] = b[i];
}

char fibo1[Max];
char fibo2[Max];
char p[Max];

int main()
{

  for (int i = 0; i < Max; i++)
  {
    fibona1[i] = fibona2[i] = p[i] = '0';
  }
  fibona2[Max - 1] = '1';

  int n;
  scanf("%d", &n);

  if (n == 0 || n == 1)
  {
    printf("%c", n + '0');
  }
  else
  {
    for (int i = 2; i <= n; i++)
    {
      adding(fibona1, fibona2, p);
      copying(fibona1, fibona2);
      copying(fibona2, p);
    }

    int da = 0;
    for (int i = 0; i < Max; i++)
    {
      if ( da == 0 && p[i] == '0')
        continue;

      if (da == 0 && p[i] != '0')
        da = 1;
      printf("%c", p[i]);
    }
    printf("\n");
  }
  return 0;
}

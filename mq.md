Question Setter
---------------
Name:  **Mahdi Murshed Patwari**
Registration # **2018331098**
Session: *2018-19*
GitHub Username: *123mahdi12345*
Cell: **
Email: *123mahdi12345@gmail.com*

Question Set with Answers
=========================
<div style="text-align:center">
  <style>
    #marking {
        display: flex;
        margin: 0;
        padding: 0;
    }
    .alignleft {
        flex: 1;
        text-align: left;
    }
    .aligncenter {
        flex: 1;
        text-align: center;
    }
    .alignright {
        flex: 1;
        text-align: right;
    }
    hr.divider {
     margin: 0em;
     border-width: 2px;
     background-color: black;
    }

    p {
     margin: 0;
     padding: 0;
    }
  </style>
  <span style="font-size:1.3em">Shahjalal University of Science and Technology
  </span><br>
  <span style="font-size:1.2em">Department of Computer Science and Engineering
  </span><br>
  <span> 1<sup>st</sup> Year 1<sup>st</sup> Semester Final Examination &mdash;
  June 2020 (Session 2019-20) </span><br>
  <span> Course No. &mdash; <b> CSE 133</b> </span><br>
  <span> Course Title &mdash; <b> Structured Programming Language</b> </span>
  <span id="marking">
    <span class="alignleft">Time &mdash; <b> 3 Hours</b></span>
    <span class="aligncenter">Credit: <b> 3.00</b></span>
    <span class="alignright">Total Marks # <b> 100</b></span>
  </span>
  <hr class="divider">
  <span style="margin-bottom: 1.2em"> (Answer All the Questions)</span><br><br>
</div>
<div style="text-align:center">
  <span style="font-size:1.2em"><b>Group A</b>
  </span> <br> <br>
  <span id="marking">
    <span class="alignleft">1. Answer the following Questions in short. (Any <b>Five</b>).</span>
    <span class="alignright">5 &times; 2 = 10 </span>
  </span>
</div>

(a) Write the output of the following piece of code.
&emsp;&emsp;int f = 'F', d = 'D';
&emsp;&emsp;f%=d-=d>>3;
&emsp;&emsp;printf("%d %d",f,d);

	Answer:
	10 60

(b) Which of the followings are valid identifiers? State the reason in the case of invalid.
&emsp; &emsp; &emsp; _long  &emsp;   -short  &emsp;    const   &emsp;  STATIC

	Answer:
	_long and STATIC are valid identifiers here. -short is invalid as it contains an illegal character (-) and const cannot be used as an identifier because it is a keyword and has a predefined meaning.       
(c ) What will happen if you run the following program?
  &emsp;&emsp;#include<stdio.h>
  &emsp;&emsp;#define x >>

  &emsp;&emsp;int main()
   &emsp;&emsp;{
   &emsp;&emsp;&emsp;&emsp;int xx=40,xxx=2,xxxx=60;
   &emsp;&emsp;&emsp;&emsp;xx = xx x xxx;
   &emsp;&emsp;&emsp;&emsp;printf("%0x %0X",xxxx x xxx, xx);
   &emsp;&emsp;&emsp;&emsp;return 0;
    &emsp;&emsp;}

	Answer:
	It will compile successfully.
	Output: f A

(d) Write the output of the following code snippet.
    &emsp;&emsp;int a = 'A', b=15;
    &emsp;&emsp;(a%b++!=b/2||++b<a)?++b>>2 : --a%=b;
    &emsp;&emsp;printf("%d+%d",a,b);

	Answer:
	65+17

(e) Can you use the identifiers variable_1 and variable_10 in a single C program? Defend your answer.

	Answer:
	Some compilers recognize only the first eight characters, though most implementations recognize up to 31 characters. So, some compilers may not distinguish between variable_1 and variable_10 as the first eight characters of each identifier are the same. That's why we should avoid using them in a single C program.

(f) Will the program compile without any error? If no, state the reason with corrected code and if yes, write the output.
    &emsp;&emsp;int arr[]={3,23,16,11,29,18};
    &emsp;&emsp;int *ptr=arr;
    &emsp;&emsp;int *ptr2=ptr+*ptr;
    &emsp;&emsp;printf("%x",++*ptr2 + --*ptr);

	Answer:
	Yes, it will compile successfully.
	Output: e

(g)Write the output.
    &emsp;&emsp;char s[]="SYLHET";
     &emsp;&emsp;char *p = s;
     &emsp;&emsp;p+=3;
     &emsp;&emsp;printf("%c %d",++*p,*p++);

	Answer:
	F 72

(h)Write the output of the following code.
&emsp;&emsp;enum set {jan,feb,may,jun=8,sept,dec};
    &emsp;&emsp;for(int i=jan;i<=dec;i++)
    &emsp;&emsp;{
      &emsp;&emsp;&emsp;&emsp;printf("%d",i%may);
    &emsp;&emsp;}

	Answer:
	01010101010

<div>
  <span id="marking">
    <span class="alignleft">2. Answer the following Questions. (Any <b>Four</b>).</span>
    <span class="alignright">4 &times; 5 = 20 </span>
  </span>
</div>

(a) Write the output of the following program.
   &emsp;&emsp;int main()
   &emsp;&emsp;{
      &emsp;&emsp;&emsp;&emsp;char c[]="456789123";
      &emsp;&emsp;&emsp;&emsp;char *ptr=c+5;
     &emsp;&emsp;&emsp;&emsp;ptr-- ;
      &emsp;&emsp;&emsp;&emsp;int x=*ptr;
      &emsp;&emsp;&emsp;&emsp;switch(x++)
      &emsp;&emsp;&emsp;&emsp;{
          &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;case 57:
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;x=x<<1;
          &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;default:
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;x-- ;
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;printf("%c ",x);
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;break;
          &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;case 56:
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;x-- ;
              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;printf("%c ",x);
      &emsp;&emsp;&emsp;&emsp;}
      &emsp;&emsp;&emsp;&emsp;return 0;
   &emsp;&emsp;}

    Answer:
    8

(b)Write the output of the following program. (Assume that int takes 32 bits and char takes 8 bits)
   &emsp;&emsp;#include <stdio.h>

   &emsp;&emsp;union un
  &emsp;&emsp; {
      &emsp;&emsp;&emsp;int a;
      &emsp;&emsp;&emsp;char b;
      &emsp;&emsp;&emsp;int c;
  &emsp;&emsp;}var,*ptr1,*ptr2;

   &emsp;&emsp;int main()
   &emsp;&emsp;{
      &emsp;&emsp;&emsp;var.a=80;
      &emsp;&emsp;&emsp;var.c=var.a^18;
      &emsp;&emsp;&emsp;ptr1=&var;
      &emsp;&emsp;&emsp;ptr2=ptr1;
      &emsp;&emsp;&emsp;ptr2->a++;
      &emsp;&emsp;&emsp;printf("%d %c %x\n",ptr2->a,ptr2->b,ptr1->c%50);
      &emsp;&emsp;&emsp;ptr1->c^=50;
      &emsp;&emsp;&emsp;printf("%d %c %x", ptr1->a,ptr1->b,ptr2->c%sizeof(var)+12);
     &emsp;&emsp;&emsp; return 0;
   &emsp;&emsp;}

    Answer:
    67 C 11
    113 q d

(c ) Write a program to count digits in an integer using recursion, where the integer will be taken as input.

    Example Answer:

    #include <stdio.h>
    int count(long long n)
    {
      if (n == 0)
        return 0;
      return 1 + count(n / 10);
    }
    int main()
    {
      long long n;
      scanf("%lld",&n);
      printf("Number of digits : %d", count(n));
      return 0;
    }

(d) Write a C program to print first n fibonacci numbers. n should be taken as input and assume that n will not exceed 50.

    Example Answer:

    #include <stdio.h>
    #define ll long long int
    void fib(ll n)
    {
        if ( n < 1 )  return;
        ll f1 = 0, f2 = 1,f3;
        printf("%lld ", f1);
        for (int i = 1; i < n; i++)
        {
            printf("%lld ", f2);
            f3 = f1 + f2;
            f1 = f2;
            f2 = f3;
        }
    }

    int main()
    {
        int n;
        scanf("%d",&n);
        fib(n);
        return 0;
    }


<div>
  <span id="marking">
    <span class="alignleft">3. Answer the following Questions. (Any <b>Two</b>).</span>
    <span class="alignright">2 &times; 10 = 20 </span>
  </span>
</div>

(a)Write the output.
&emsp;&emsp;#include <stdio.h>
&emsp;&emsp;int fun(int x,int y,int z)
&emsp;&emsp;{
&emsp;&emsp;&emsp;&emsp; z%=y*=(z-y);
 &emsp;&emsp;&emsp;&emsp;x=~ (~ (y^z))>>5;
 &emsp;&emsp;&emsp;&emsp;printf("%d ",x);
&emsp;&emsp;&emsp;&emsp; return x;
&emsp;&emsp;}

&emsp;&emsp;int main()
&emsp;&emsp;{
 &emsp;&emsp;&emsp;&emsp;int a='B',b='A',c,d,i,j,f;
 &emsp;&emsp;&emsp;&emsp;c=++a%(b>>3)<<5;
&emsp;&emsp;&emsp;&emsp;a=fun(a,b,c);
 &emsp;&emsp;&emsp;&emsp;b=fun(b,a,c);
 &emsp;&emsp;&emsp;&emsp;c=fun(c,a,b);
&emsp;&emsp;&emsp;&emsp;printf("\n");
 &emsp;&emsp;&emsp;&emsp;while(c-- )
 &emsp;&emsp;&emsp;&emsp;{
     &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;switch(a&b&c)
     &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;{
         &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;default:
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;d=a^c;
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;printf("From default: %d when c = %d\n",d,c);
         &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;case 1:
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;d=c<<1;
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;printf("From Case 1: %d when c = %d\n",d,c);
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;break;
         &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;case 2:
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;d=a|c;
             &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;printf("From Case 2: %d when c = %d\n",d,c);
     &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;}
 &emsp;&emsp;&emsp;}
 &emsp;&emsp;&emsp;return 0;
&emsp;&emsp;}

    Answer:
	61 65 5
	From default: 57 when c = 4
	From Case 1: 8 when c = 4
	From Case 1: 6 when c = 3
	From default: 63 when c = 2
	From Case 1: 4 when c = 2
	From Case 1: 2 when c = 1
	From default: 61 when c = 0
	From Case 1: 0 when c = 0
(b)Generate the following pattern using loops. [This is the pattern for n=5]
1&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1
&emsp;2&emsp;&emsp;&emsp;&emsp;&emsp;2
&emsp;&emsp;3&emsp;&emsp;&emsp; 3
&emsp;&emsp;&emsp;4 &emsp; 4
&emsp;&emsp;&emsp;&emsp; 5
&emsp;&emsp;&emsp;4 &emsp; 4
&emsp;&emsp;3&emsp;&emsp;&emsp; 3
&emsp;2&emsp;&emsp;&emsp;&emsp;&emsp;2
1&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1

    Answer:
	#include <stdio.h>

	int main()
	{
	    int i, j, n;
	    printf("Enter n: ");
	    scanf("%d", &n);
	    for(i=1; i<=n; i++)
	    {
	        for(j=1; j<i; j++)
	        {
	            printf(" ");
	        }
	        printf("%d", i);
	        for(j=1; j<=((n - i) * 2 - 1); j++)
	        {
	            printf(" ");
	        }
	        if(i != n) printf("%d", i);
	        printf("\n");
	    }
	    for(i=n-1; i>=1; i--)
	    {
	        for(j=1; j<i; j++)
	        {
	            printf(" ");
	        }
	        printf("%d", i);
	        for(j=1; j<=((n - i ) * 2 - 1); j++)
	        {
	            printf(" ");
	        }
	        printf("%d\n", i);
	    }
	    return 0;
	}
(c )Write a program that writes all the members of an array of structures to a file named "Student.txt" and then reads the array from the file and display on the screen.

    Example Answer:
    #include <stdio.h>
	struct student
	{
	   char name[50];
	   int height;
	   int age;
	};
	int main(){
	    int n;
	    scanf("%d",&n);
	    struct student stud1[n], stud2[n];
	    FILE *fptr;
	    int i;

	    fptr = fopen("Student.txt","wb");
	    for(i = 0; i < n; ++i)
	    {
	        fflush(stdin);
	        gets(stud1[i].name);
	        scanf("%d", &stud1[i].height);
	        scanf("%d", &stud1[i].age);
	    }

	    fwrite(stud1, sizeof(stud1), 1, fptr);
	    fclose(fptr);

	    fptr = fopen("Student.txt", "rb");
	    fread(stud2, sizeof(stud2), 1, fptr);
	    for(i = 0; i < n; ++i)
	    {
	        printf("%s %d %d\n", stud2[i].name, stud2[i].height, stud2[i].age);
	    }
	    fclose(fptr);
	}

<div style="text-align:center">
  <span style="font-size:1.2em"><b><br>Group B</b>
  </span> <br> <br>
  <span id="marking">
    <span class="alignleft">1. Answer the following Questions in short. (Any <b>Five</b>).</span>
    <span class="alignright">5 &times; 2 = 10 </span>
  </span>
</div>

(a) What is Portability and Extensibility of C language?

	Answer:
	Portability is the platform independency of the language and Extensibility is the possibility of adding new features by the programer.

(b) Write the output of the following piece of code.
      &emsp;&emsp;int a=20,b=5;
     &emsp;&emsp;(b++ < a >> 2)? b++ : a-=b;
     &emsp;&emsp;printf("%d",a++^b-- );

	Answer:
	8

(c ) Write the output of the following code snippet.
    &emsp;&emsp;char c[]= "sustcse";
     &emsp;&emsp;printf("%0004.2s",c);

	Answer:
	00su

(d) What do %e and %i mean?

	Answer:
	Data item is displayed as a floating-point value with an exponent by %e and as a signed decimal integer by %i.

(e) What will be the output? (Consider a compiler where int takes 4 bytes, char takes 1 byte and pointer takes 4 bytes.)
    &emsp;&emsp;int arr[] = {10,20,30,40};
     &emsp;&emsp;char ch[] = "Batch18";
     &emsp;&emsp;int *ptr1 = arr;
     &emsp;&emsp;char *ptr2 = ch;
     &emsp;&emsp;printf("%d %d %d %d", sizeof(arr),sizeof(ptr1),sizeof(ch),sizeof(ptr2));

	Answer:
	16 4 8 4

(f)What will be the output if we run this program? (Consider int takes 4 bytes)
    &emsp;&emsp;int main()
    &emsp;&emsp;{
    &emsp;&emsp;&emsp;struct test
    &emsp;&emsp;&emsp;{
      &emsp;&emsp;&emsp;&emsp;int a[5];
      &emsp;&emsp;&emsp;&emsp;static int b;
    &emsp;&emsp;&emsp;};
    &emsp;&emsp;printf("%d",sizeof(struct test));
    &emsp;&emsp;}

    Answer:
    It will have a compilation error as struct types cannot have static members in C.

(g)What is the difference between Call by Value and Call by Reference?

	Answer:
	When the value of a variable is sent as parameter to a function, it's Call by Value. Whereas Call by Reference sends the address of the variable. Under Call by Value, the value in the parameter is not affected by whatever operation that takes place, while in the case of Call by Reference, values can be affected by the process within the function.

(h)What is the use of a '\0' character?

	Answer:
	It is the ascii value of null. It is use to identify whether there is null present in the string or not while performing string oeration.

<div>
  <span id="marking">
    <span class="alignleft">2. Answer the following Questions. (Any <b>Four</b>).</span>
    <span class="alignright">4 &times; 5 = 20 </span>
  </span>
</div>

(a) Write a C program to check whether a string is palindrome or not using pointers. Your program should contain a function named isPalindrome() which will take a string as parameter and print "YES" in the cases of palindrome and "NO" otherwise.

      Example Answer:
      #include <stdio.h>
      void isPalindrome(char* str)
      {
          char *ptr, *rev;
          ptr = str;
          while (*ptr != '\0')
          {
              ptr++;
          }
          ptr--;
          for (rev = str; rev <= ptr;)
          {
              if (*ptr == *rev)
              {
                  --ptr;
                  rev++;
              }
              else break;
          }
          if (rev > ptr) printf("YES");
          else printf("NO");
      }

      int main()
      {
          char str[100];
          scanf("%s",&str);
          isPalindrome(str);
          return 0;
      }

(b) Write the output of the following program.
   #include <stdio.h>
   #define $ 7
   int main()
   {
      int a=$ ,b,c,d;
      b=a++;
      c=++b*$ ;
      d=++b*++c% $ *a;
      while(b+d!=c||++a==c)
      {
          a=b | $ & a;
          c-- ;
          b+=3;
          printf("(%d+%d+%d+%d)\n",a % $ ,b% $ ,c%b,d % $);
      }
      return 0;
   }

    Answer:
    (2+5+8+2)
    (6+1+10+2)
    (1+4+0+2)
    (2+0+11+2)
    (2+3+4+2)
    (3+6+24+2)
    (3+2+20+2)
    (3+5+16+2)
(c ) Write a C program to convert a decimal number to a binary number.

    Example Answer:
    #include <stdio.h>
    int main()
    {
      int n,rem,i = 1;;
      long long bin = 0;
      scanf("%d", &n);
      while (n != 0)
      {
          rem = n % 2;
          n /= 2;
          bin += rem * i;
          i *= 10;
      }
      printf("%lld", bin);
      return 0;
   }
(d) Write a C program to find the GCD of n numbers which should be taken as array input.

    Example Answer:
    #include <stdio.h>
    int main()
    {
        int n,i,j=1,gcd;
        scanf("%d",&n);
        int arr[n+2];
        for(i=0;i<n;i++)
        {
            scanf("%d",&arr[i]);
        }
        gcd=arr[0];
        while(j<n)
        {
            if(arr[j]%gcd==0)
            {
                j++;
            }
            else
            {
                gcd=arr[j]%gcd;
                i++;
            }
        }
        printf("GCD of %d numbers = %d ",n,gcd);
        return 0;
    }


<div>
  <span id="marking">
    <span class="alignleft">3. Answer the following Questions. (Any <b>Two</b>).</span>
    <span class="alignright">2 &times; 10 = 20 </span>
  </span>
</div>

(a) Take a 3x3 matrix as input and check whether it is Symmetric Matrix or not.
[Hint: A symmetric matrix is a square matrix that is equal to its transpose.]

    Example Answer:
    #include <stdio.h>
	#define SZ 3

	int main()
	{
	    int A[SZ][SZ],B[SZ][SZ],row, col, isSym;
	    printf("Enter elements of matrix: \n");
	    for(row=0; row<SZ; row++)
	    {
	        for(col=0; col<SZ; col++)
	        {
	            scanf("%d", &A[row][col]);
	        }
	    }
	    for(row=0; row<SZ; row++)
	    {
	        for(col=0; col<SZ; col++)
	        {
	            B[row][col] = A[col][row];
	        }
	    }
	    isSym = 1;
	    for(row=0; row<SZ && isSym; row++)
	    {
	        for(col=0; col<SZ; col++)
	        {
	            if(A[row][col] != B[row][col])
	            {
	                isSym = 0;
	                break;
	            }
	        }
	    }
	    if(isSym == 1)
	    {
	        printf("Symmetric matrix\n");
	    }
	    else
	    {
	        printf("Not a symmetric matrix.");
	    }
	    return 0;
	}
(b) (i)Write a program to find LCM of three integers using function.
ii. Write a program to find the sum of prime divisors of an integer.

    Example Answer:

    (i.)

    #include<stdio.h>

    int lcm(int a,int b)
    {
        int temp = a;
        while(1)
        {
            if(temp % b == 0 && temp % a == 0) break;
            temp++;
        }
        return temp;
    }

    int main()
    {
        int a,b,c,l,k;
        scanf("%d %d %d",&a,&b,&c);
        if(a>b)
          l = lcm(a,b);
        else
          l = lcm(b,a);
        if(l>c)
          k= lcm(l,c);
        else
          k= lcm(c,l);
        printf("%d",k);
        return 0;
    }


    (ii.)

    #include <stdio.h>
	#define false 0
	#define true 1

	int isPrime(int n)
	{
	    if (n <= 1) return false;
	    if (n <= 3) return true;
	    if (n % 2 == 0 || n % 3 == 0) return false;
	    for (int i = 5; i * i <= n; i = i + 6)
	    {
	        if (n % i == 0 || n % (i + 2) == 0) return false;
	    }
	    return true;
	}

	int sopd(int n)
	{
	    int sum = 0;
	    for (int i = 1; i <= n; i++) {
	        if (n % i == 0) {
	            if (isPrime(i))
	                sum += i;
	        }
	    }
	    return sum;
	}

	int main()
	{
	    int n;
	    scanf("%d",&n);
	    printf("%d",sopd(n));
	    return 0;
	}
(c )Implement a stack using linked list. The program should perform atleast 3 stack operations - push, pop and display.

    Example Answer:
    #include<stdio.h>
	#include<conio.h>
	#include<stdlib.h>
	#define SZ 50

	int size;

	struct stack {
	   int arr[SZ];
	   int top;
	};

	void init_stack(struct stack *pt) {
	   pt->top = -1;
	}

	void push(struct stack *pt, int number) {
	   if (pt->top == size - 1) {
	      printf("\nStack overflow!\n");
	      return;
	   }
	   pt->top++;
	   pt->arr[pt->top] = number;
	}

	int pop(struct stack *pt) {
	   int number;
	   if (pt->top == -1) {
	      printf("Stack underflow!\n");
	      return NULL;
	   }
	   number = pt->arr[pt->top];
	   pt->top--;
	   return number;
	}

	void display(struct stack *pt) {
	   int i;
	   for (i = pt->top; i >= 0; i--)
	      printf("%d ", pt->arr[i]);
	}

	int main() {
	   int op, val, del;
	   struct stack ptr;
	   init_stack(&ptr);
	   printf("Enter Stack Size: ");
	   scanf("%d", &size);
	   while (1) {
	      printf("\nSTACK OPERATIONS");
	      printf("\n1.PUSH");
	      printf("\n2.POP");
	      printf("\n3.DISPLAY");
	      printf("\n4.QUIT\n");
	      printf("\nEnter your option : ");
	      scanf("%d", &op);
	      switch (op) {
	      case 1:
	         printf("\nEnter the element into stack: ");
	         scanf("%d", &val);
	         push(&ptr, val);
	         break;
	      case 2:
	         del = pop(&ptr);
	         printf("\nThe element popped from stack is : %d", del);
	         break;
	      case 3:
	         printf("\nThe current stack elements are: ");
	         display(&ptr);
	         break;
	      case 4:
	         exit(0);
	      default:
	         printf("\nEnter correct option!Try again.");
	      }
	   }
	   return (0);
	}


<div style="text-align:center">
  <span style="font-size:1.0em">- End -</span>
</div>

- [x] I am declaring that, the above work is my own work. Whatever added above except the template is the result of my brainstorming. I also understand that submitting work that isn’t my own may result in permanent failure of this course as well as the whole current  semester.

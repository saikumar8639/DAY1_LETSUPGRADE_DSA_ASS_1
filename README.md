# DAY1_LETSUPGRADE_DSA_ASS_1
DAY1 LETSUPGRADE DSA ASSIGNMENT 1


1.) Find the time complexity for the following scenarios
      a.) for(i=1;i<=n;i++)     
           for(j=i;i<=n;j++)
            printf("Hi");
           
           if i=1 inner loop=n times,
           if i=2  inner loop=n-1 times,
           ....... if i=n   inner loop=1 time
           then time complexity is O(n(n+1)/2)=O(n^2) 



      b.) for(i=1;i<=n;i*=3)
           for(j=1;i<=n;j++)
             printf("Hello");
             
             if i=1 inner loop=n times,
             if i=3  inner loop=n times,
           ....... if i=n(if n%3==0)  inner loop=n time
           then time complexity is O(2n^2/3)==O(n^2) 

             

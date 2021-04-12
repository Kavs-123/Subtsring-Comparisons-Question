# Subtsring-Comparisons-Question

- Sample Input 0 <br>
welcometojava <br>
3
<br><br>
- Sample Output 0 <br>
ava <br>
wel<br><br>

## DESCRIPTION-
We then return the first (lexicographically smallest) substring and the last (lexicographically largest) substring as two newline-separated values (i.e., ava\nwel).

##CODE-
 public static String getSmallestAndLargest(String s, int k) { <br>
        String smallest = ""; <br>
        String largest = "";  <br>
        smallest=s.substring(0,k); <br>
        largest=" "; <br>
        for(int i=0;i<=s.length()-k;i++) <br>
        { <br>
            if(s.substring(i,i+k).compareTo(smallest)<0) <br>
             smallest=s.substring(i,i+k); <br>
            if(s.substring(i,i+k).compareTo(largest)>0) <br>
             largest=s.substring(i,i+k);   <br>    
        }
<br><br><br>
##Easy code to understand as well as implement in `JAVA`



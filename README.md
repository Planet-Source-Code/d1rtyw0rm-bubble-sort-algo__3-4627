<div align="center">

## Bubble Sort Algo


</div>

### Description

It is a simple algorithm about howto sort an array of a number in chronological order
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[d1rtyw0rm](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/d1rtyw0rm.md)
**Level**          |Beginner
**User Rating**    |3.8 (15 globes from 4 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Algorithms](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithms__3-29.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/d1rtyw0rm-bubble-sort-algo__3-4627/archive/master.zip)





### Source Code

<link rel="stylesheet" href="http://205.151.63.123/d1rtyw0rm/style.css" type="text/css">
The sorting by bubble consists in traversing an array and to interchange each couple of numbers of which first ranks above the second. Several passages on the table will be necessary (exactly items_numbers - 1)<BR><BR>
Little exemple : <BR>
<B>ORIGINAL ARRAY</B> : 8 3 9 7 1<BR><BR>
<I>First Passage</I><BR><BR>
<U>3</U> <U>8</U> 9 7 1<BR>
3 <U>8</U> <U>9</U> 7 1<BR>
3 8 <U>7</U> <U>9</U> 1<BR>
3 8 7 <U>1</U> <U>9</U><BR><BR>
As of the first passage, the highest number is automatically thorough with the last position. Therefore, we will not need more to check it with other numbers at the time of the next passages. In the code which will follow, variable N discharges this task. In fact, each following passage will contain each one a checking of less than preceding it.<BR><BR>
<I>Second Passages</I><BR><BR>
<U>3</U> <U>8</U> 7 1 9<BR>
3 <U>7</U> <U>8</U> 1 9<BR>
3 7 <U>1</U> <U>8</U> 9<BR><BR>
<I>Third Passages</I><BR><BR>
<U>3</U> <U>7</U> 1 8 9<BR>
3 <U>1</U> <U>7</U> 8 9<BR>
<I>Fourth Passage</I><BR><BR>
<U>1</U> <U>3</U> 7 8 9<BR><BR>
The following algorithm sort each element of an array using the bubble sorting. The variables N and K are counter and swap is a variable being used like a temporarily contain to store a value at the time while interchangement as values between two variables.<BR><BR>
int n, k, swap;<BR><BR>
for (n = num - 1; n > 0; n--)<BR>
{<BR>
 for (k = 0; k < n; k ++)<BR>
 {<BR>
 if (tab[k] > tab[k + 1])<BR>
 {<BR>
  swap = tab[k];<BR>
  tab[k] = tab[k + 1];<BR>
  tab[k + 1] = swap;<BR>
 }<BR>
}<BR>
}<BR>
-d1rtw0rm


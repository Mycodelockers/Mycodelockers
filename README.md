- š Hi, Iām @Mycodelockers
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Mycodelockers/Mycodelockers is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->Code....
add digits

Class solution
{
public int adddigits(int[] nums)
{
int newno=0;
while(num>0)
{
nums=newno+(nums%10);
newno=num/10;
if(num==0 && newno>9)
{
num=newno;
newno=0;
}
return newno;
}
}

Input
38---3+8=11

11=1+1=2

Output=2

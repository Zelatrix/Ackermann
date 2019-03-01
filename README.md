# Ackermann
This function runs the Ackermann function, which is a recursive function defined as follows: 
For Ack(m,n)
```
if(m == 0)
{
  return n+1;
}
else if(m > 0 && n == 0)
{
  return Ack(m-1, 1)
}
else if(m > 0 && n > 0)
{
  return Ack(m-1, Ack(m, n-1))
}
```

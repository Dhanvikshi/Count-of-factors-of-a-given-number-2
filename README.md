# Count-of-factors-of-a-given-number-2
n = int(input())
c = 0
i = 1
while i <= n:
  if n%i == 0:
    c = c + 1
  i = i + 1
print(c)

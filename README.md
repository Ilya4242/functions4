# functions4
def a(a_list):
  s=0
  for i in a_list:
    s=s+i
    return s
 print(a([int(n) for n in input().split()]))

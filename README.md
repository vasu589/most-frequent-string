#program to find a most frequent string
 
def most_frequent(string)
    d = dict()
  for key in string
 if key not in d
   d[key] = 1
  else:
    d[key] += 1
 return d
Print most_frequent('mississippi')

Output:
I=4
S=4
P=2
M=1

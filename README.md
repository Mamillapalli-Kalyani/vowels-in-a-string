# vowels-in-a-string
s="jfjlfndhaohju"
s1="aeiouAEIOU"
ec=0
oc=0
for i in range(len(s)):
  if i%2==0:
    if s[i] in s1:
      ec+=1
  else:
    if s[i] in s1:
      oc+=1
print(ec)
print(oc)

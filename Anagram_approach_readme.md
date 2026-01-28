Anagram_approach

'abbcd'   'caddb'

{a:1,b:2,c:1,d:1}     {c:1,a:1,d:1,b:2}

return false 

so it's not anagram


'cats'     'tacs'
{c:1,a:1,t:1,s:1}     {t:1,a:1,c:1,s:1}


return true

#Time Complx:   O(n+m)  n and m are lengths of strings
#Space Complx:  O(1)  as we are using fixed space for hashmap

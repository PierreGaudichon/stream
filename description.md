

Fonctions

Currifiees

"a, b, c" > split > equals ["a", "b", "c"] > S array
document.div.click > 


capitalize :: String -> String

"lol" > capitalize > equals "Lol"

capitalize
  input > get 1 > toUpperCase > first
  input > sub 2 -1 > lasts
  concat first lasts > output
  
  
capitalize = (s) ->
  first = input[0].toUppercase()
  return first + s.slice(0, -1)
  

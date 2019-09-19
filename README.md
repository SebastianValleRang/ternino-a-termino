sebastian vallejo 20162020080

sumar::[Int]->[Int]->[Int]

sumar xs [] = []
sumar [] ys = []

sumar (x:xs) (y:ys) = (x+y) : sumar xs ys

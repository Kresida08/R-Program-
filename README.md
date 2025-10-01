#Arithmetic Operators

x <- 10
y <- 5
sum <- x+y
product <- x*y
print (sum)
print (product)

x %/% y #returns the Quotient 
x %% y #returns the remainder
y^x #Power
y**x #Power

#Relational Operators

a<- 70
b<- 42
c<- 54
d<- 36
e<- 76
f<- 23
g<- 54
h<- 42
res<- a<h
res
res<- b>d
res
res<- c<=h
res
res<- d>=g
res
res<- e!=a
res
sry<- c==g
sry

#Logical Operator

X<- TRUE
Y<- FALSE
print (X&Y)
print (X | Y)
print (!Y)


(54>43) & (30<45) #Will give true only if both the condition will get satisfied
(5>6)|(6>4) #Will give o/p evn if 1 condition gets satisfied
!(78<32) #Will return the opposite of wht u mention 

 
# (& AND will return True if both the values are right/ ' or | OR will return True if any 1 condition is satisfied/ ! NOT will return True if say eg:!76<65 it will return True)


#Assignment Operator


#Assign Left (assign 10 to x)
x<-10
x
#Assign Right (assign 19 to y)
19->y
y
a <- 34
b = 45
c <- a+b
print(c)


#Special Operators
#a.Sequence operator
100:300


#Membership Operator
52 %in% (40:50)


#Matrix Multiplication
a <- matrix (c (10,11,12,13,14), nrow = 2 , ncol = 2)
b <- matrix (c (2,3,4,5,6), nrow = 2 , ncol = 2 )
c <- a%*%b
print(c)


#Miscellaneous Operators
#It gives the same number as o/p
x <- c(12,13,14)
x
#y will include 130 also
y <- (100:130)
y


#Area of a Rect with Length=7 Width=3
a <- 70
b <- 20
c <- a*b
c


#Number divisible by 3 by modulus operator
a <- 66
b <- 3
c <- a%%b
c

#Use logical operator to test if a number is both greater than 10 and even
a <- 34
b <- 9
(a<10) & (b>10)


#create variable my.age
my.age<-26
#create variable my.name
my.name<-"Kady"
MakeIntroduction <- c(my.name, my.age)
MakeIntroduction <- paste("Hello, my name is",my.name,"and I am", my.age, "years old")
#create variable my.intro
my.intro<-MakeIntroduction
print (MakeIntroduction)
#create variable casual.intro
casual.intro<- sub("Hello, my name is", "Hey, I'm",my.intro)
print (casual.intro)
#create variable capital.intro
capital.intro<- str_to_title(my.intro, locale = "en")
print (capital.intro)
#create variable intro.e.count
intro.e.count<-str_count(my.intro,"e")
print (intro.e.count)
#create variable books
books<- c("The New Jim Crow", "To Kill a Mockingbird", "The Great Gatsby", "Pride and Prejudice", "Catcher in the Rye", "Of Mice and Men")
print (books)
#create variable top.three.books
top.three.books<- books[c(1,2,3)]
print (top.three.books)
#create variable book.reviews
book.reviews<- paste(books,"is a great read!")
print (book.reviews)
#create variable books.without.four
books.without.four<- books[-4]
print (books.without.four)
#create variable long.titles
long.titles<- str_count(books) > 15
long.titles
#create variable numbers
numbers<-c(1:201)
numbers
#create variable squared.numbers
squared.numbers<-numbers^2
squared.numbers
#create variable square.mean
square.mean<-mean(squared.numbers)
square.mean
#create variable squares
squares <- sqrt(numbers)
answer <- round(squares)
answer
squares<-sqrt[round(square.mean)]
squares
## Hello world script
#Function Hello() will return "Hello World" / replace World with other subjects by insert greeting variable with name or subject.
#For instance Hello("Indonesia") will result "Hello Indonesia"

Hello<-function(greeting=c("World")){
       intro<- (paste("Hello", greeting))
       
       return(intro)
 }

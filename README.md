  ========Array
var Name = ["Yosif","Mahmoud","Ahmed"]
print(Product)


  ==========Dictionary
var Product : [String:Any] = ["Name" :"Macbook Pro","Processor":"Intel Core I7","Color":"Gray","Price":"17000"]
print (Product)
print (Product["Ram"] ?? "16Gb")
Product["Capicity"] = "256 Gb"
print("Dictionary After add is \(Product)")
Product ["Color"] = "Red"
print("Dictionary After existing Key \(Product)")

  ========For Loop
  for i in 1...5 {
    print(i)
}


  ========While Loop
  Ex1:-
var count = 1
while count < 5 {
    print(count)
}

  Ex2:-
var count = 5
while count > 0
{
    print(count)
    count -= 1
  Ex3:-
  var i = 1
repeat
{
    print(i)
    i += 1
}while i < 6
Output: 1 2 3 4 5
 Ex4:-
 var i = 10
repeat
{
    print(i)
    i += 1
}while i < 6
Output:-10

  ===========Overloading
  func Sum(num1 : Int , num2 : Int) -> Int{
    return num1 + num2
}
print(Sum(num1 : 5,num2 : 10))

func Sum(num1 : Int , num2 : Int , num3 : Int)-> Int{
    return num1 + num2 + num3
}
print(Sum(num1: 3, num2: 2, num3: 5))

  ========nil
var username : String?
    print(username ?? "defaultvalue")
if username == nil {
    print("username required") }
else{
    print("call api") }
username="omar"
print( username ?? "Yosif" )
        Output:   defaultvalue     username required    omar
    
    

fun minus(numbers:List<Int>):Double{
    var minus = 0
    numbers.forEach{minus -=it }
    return minus.toDouble()                         
}
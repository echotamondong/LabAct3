fun main() {
    val name = "Echo"
    val age = 22 * 365
    val border = ("==%%")
    val timesToRepeat = 3
              
	printBorder(border, timesToRepeat)
    println("Happy, Birthday! ${name}")
    printBorder(border, timesToRepeat)
    println("I am ${age}")
    println("${age} is the best to learn Kotlin")
    
    //let's print a cake
println("   ,,,,,   ")
    println("   |||||   ")
    println(" =========")
    println("@@@@@@@@@@@")
    println("{~@~@~@~@~}")
    println("@@@@@@@@@@@")
    println("")
    println("${name} is already ${age} days old")

}

fun printBorder(border:String, timesToRepeat:Int){
	repeat(timesToRepeat){
        print(border)
    }
    println()

   
}

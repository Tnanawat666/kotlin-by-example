fun main(){
    val lamp1 = Lamp()
    
    lamp1.turnOn()
    lamp1.displayLightStatus()

}

class Lamp{
    private var isOn:Boolean = false
    
    fun turnOn(){isOn = true}
    fun turnOff(){isOn = false}
    fun displayLightStatus(){
    if (isOn == true)
    println("lamp is on.")
    else
    println("lamp is off.")
    }
}

    abstract class nhanvat {
      abstract val name: String
      abstract val health: Double
      abstract val mana: Double
      abstract val khangphep: Double
      abstract val Q: String
      abstract val W: String
      abstract val E: String
      abstract val R: String
    }
    
    class Ashe() : nhanvat() {
        override val name = "Ashe"
        override val health = 624.0
        override val mana = 312.0
        override val khangphep = 30.5
        override val Q = "Chú Tâm Tiễn"
        override val W = "Tán Xạ Tiễn"
        override val E = "Ưng Tiễn"
        override val R = "Đại Băng Tiễn"
        fun comboyasuso() = println("$R, $W, $Q, $E")
    }
    
    fun main () {
    Ashe().comboyasuso()
    }

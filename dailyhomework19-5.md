package thongtin

data class MasterYi (var Máu: Double = 690.56, var Nănglượng: Double = 292.56, var Sátthương: Int = 69, var Giáp: Int = 36, var Khángphép: Double = 33.35 )

enum class SkillYi (var q: String, var w:String, var e:String, var r: String) {
    SYI("Tuyệt Kỹ Alpha","Thiền","Võ Thuật Wuju","Chiến Binh Sơn Cước"),

}
fun main (){
    println("cac bo chieu thuc cua MasterYi la")
    println("""Q = ${SkillYi.SYI.q} 
W = ${SkillYi.SYI.w} 
E = ${SkillYi.SYI.e} 
R = ${SkillYi.SYI.r} 
    """)
}
    

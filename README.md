fun main() {
    
    //Condições
    //
    //condição simples
    //
    // if --> se...
    // else --> senão... 
    /*
    var LembreiDoChocolate = "Sim"
    
    if(LembreiDoChocolate == "Sim"){
        println("Vou entregar o chocolate para você")
    }else{
        println("Chocolate pra todo mundo")
    }


 //se a condição for verdadeira, a sua ação será executada, senão, outra ação será
 //executada
 
 // Exercício
  



 var ireiDormir = "Sim"
    
    if(ireiDormir == "Sim"){
        println("irei dormir")
    }else{
        println("ficarei acordada")
    }
    */    
        
        //
        
//---------------------------------------------------------------------------------------------------------------------------------------------------------------------


fun main() {
    
    
    //Collections - Coleções
    //
    //<> ---> tags = servem para especificar o tipo de valor a ser listado
    //
    // São determinados conjuntos de itens/valores que podem ser modelados e utiliazados
    // em determinados métodos e operações
    // 
    // List - listas
    // 
    // listOf --> listam itens de variados tipos
    // 
    
    //var genericList = mutableListOf("São Paulo, arroz e pamonha", 25.7f, 23.974, "$", false)
    //println(genericList)
    
    var specificList = listOf<String>("Cruzeeiro do Roberto Carlos", "Calleri", "5")
    println(specificList)
   
    
    
    
// Index - uma posição da collection

    // Propriedades - list
    // 
    // .LastIndex
    // .size  
    // 
    //     
    //println(specificList.LastIndex)   
    //println(specificList.first())
    //println(genericList.size)
    //
    //println(specificList.get(2))
    //println(specificList.indexOf("Cruzeiro do Roberto Carlos"))
  
   
    /*
    // Métodos - listOf
    genericList.add(2,"easy")
    println(genericList)
    genericList.remove(23.974)
    println(genericList)
    genericList.removeAt(3)
    println(genericList)
    genericList.set(0, "tartaruga")
    println(genericList)
    genericList.clear()
    println(genericListpackage)
    */
    var anotherList = setOf("Pedro", "Diniz", "Pelé", "Ronaldinho", "Marília Mendonça", "Diniz")
    println(anotherList)
    
    var animal = mutableMapOf("tartaruga" to 0, "jabuti" to 1, "tucano" to 2, "hiena" to 3, "macaco" to 4)
    println(animal)
    
   
}
        
        //
        //Condições compostas
        /*
        
        var corações = 1
        
        if(corações >= 5){
            println("Você está ótimo! Bom pra você")
        }else if(corações == 4){ 
            println("Você está bem")
        }else if(corações == 3){
            println("Você está ok")
        }else if(corações == 2){
            println("Você não está muito bem")
        }else if(corações == 1){
            println("Você está morrendo!")
        }else{
            println("Você está morto")
        }
        */
    
    var idade = 18 
        
    if(idade <= 3){
        println("Você é um neném")
    }else if(idade <= 12){
        println("Você é muito infantil")
    }else if(idade <= 18){
        println("Você é jovem! Aproveite sua vida")
    }else if(idade <= 60){
        println("Você é adulto! Pague a conta")
    }else if(idade > 60){
        println("Você está velho")
    }else{ 
        println("Você não existe!")
        
        
    }
               
}    


      

 

// ------------------------------------------------------------------------------------------------------------------------------------------------------------


fun main() {

    //Operadores Lógicos
    //
    // são usados quando queremos comparar mais de uma coisa na mesma condição
    // 
    // && -> e
    // || -> ou
    // 
    // TABELA VERDADE (com E e OU)
    // 
    // && - a determinada ação só acontecerá se e somente se todas as 
    // condições forem verdadeiras
    // 
    // VV -> verdadeiro
    // VF -> falso
    // FV -> falso
    // FF -> falso
    // 
    // || a determinada ação será executada se pelo menos uma das
    // condições forem verdadeiras
    // 
    // VV -> verdadeiro
    // VF -> verdadeiro 
    // FV -> verdadeiro
    // FF -> falso
    //   
    /*
    var idade = 14
    var acompanhadoDosPais = false 
    
    
    if (idade >= 14 && acompanhadoDosPais == true){
         println("Pode entrar")
    }else{
        println("Entrada não permitida")
        
    }     
    */
    // Exercício- A Seleção Brasileira está correndo risco de ser eliminada na fase de grupos
    // da Copa, o Brasil, só pode ser classificado se a Alemanha perder, e se o próprio Brasil
    // ganhar. As partidas já passaram,quero saber se o Brasil se classificou ou não 
    //
                
    var aAlemanhaPerdeu = true
    var oBrasilGanhou = true
    
    if (aAlemanhaPerdeu == true && oBrasilGanhou == false){
        println("Brasil não foi classificado")
    }else{
        println("Brasil foi classificado")
        
    }
        
 // Exercício- A Seleção Brasileira está correndo risco de ser eliminada na fase de grupos
    // da Copa, o Brasil, só pode ser classificado se a Alemanha perder, se Marrocos perder e se o próprio Brasil
    // ganhar. As partidas já passaram,quero saber se o Brasil se classificou ou não 
    //
    
    /*
    
    val brasil = true
    val alemanha = false
    val marrocos = false
    
    if (!alemanha && brasil && !marrocos){
        println("Brasil classificado!")
    }else{
        println("Brasil não foi classificado!")
        
    }
    
    */
    
   //----------------------------------------------------------------------------------------------------------------------------------------------------- 
    
fun main() {

    
    // When - Quando
    // 
    // Quando uma determinada condição for verdadeira, outra determinada
    // ação será executada
    // 
    // Estrutura do When:
    // 
    // When(var){
    // valor -> ação a ser executada
    // outroValor -> ação
    // maisUm -> ação
    // outro -> ação
    // else -> ação
    // }
    // 
    var mes = 2
    
    when(mes){
        1 -> println("Acapulco - MEX")
        2 -> println("Paris - FRA")
        3 -> println("Berlim - ALE")
        4 -> println("Monaco - MON")
        5 -> println("Pequim - CHI")
        6 -> println("Acre - BRA")
        7 -> println("Roma - ITA")
        8 -> println("Atenas - GRE")
        9 -> println("Madrid - ESP")
        10 -> println("Manchester - ING")
        11 -> println("Dubai - EAU")
        else -> println("São Paulo - BRA")
        
    }
        
 //-------------------------------------------------------------------------------------------------------------------------------------------------------
 
fun main() {
 
    // Laços de Repetição
    // 
    // while - enquanto
    // for - para...
    // do... while - faça... enquanto
    // repeat - repita
    
    // Laço While 
    // enquanto uma determinada condição forr verdadeira, outra determinada
    // ação será executada
    // 
    // Estrutura do While
    // 
    // while(condição){
    // ação
    // }
    
   /*
    var number = 0 
    
    
    while(number <= 47){
        println(number)
        number++   
   */
   
   // Laço do... While 
   // 
   // Uma determinada ação será executada, enquanto outra determinada condição for
   // verdadeira
   // 
   // Estrutura do do.. While
   // 
   // do{
   // ação
   // } while(condição)
  
   var idade = 1 
    
   do{
       println("$idade anos? Cresça, sério")
       idade 
   }while(idade > 17) 
    
    
    // Exercício -> O ano não é bissexto, portanto o ano possui 365 dias, precisa ser exibido no
    // console, os números de 1 a 365, usando no mínimo uma variável, usando os Laços While e 
    // do..while
    
    
    var ano = 1 
    
    while(ano < 366){
       println("")
       ano++
        
    }
    
    
    
 
}
    
//--------------------------------------------------------------------------------------------------------------------------------------------------------------------

//POO 
    //
    // Programação Orientada a Objetos 
    // 
    // Objetos - estados (características: nome, idade, cpf)
    // 
    // Comportamentos - (andar, comer, dormir, conversar, programar) 
    // 
    // Classes - Modelos que servem para construção de objetos derivados 
    // 
    val pessoa1 = Pessoa()
    pessoa1.nome = "Keyla"
    println(pessoa1.nome)
    pessoa1.cpf = "445.177.465.78"
    println(pessoa1.cpf)
}
 
 class Pessoa(){
     //declaração de atributos para a classe Pessoa
     var nome = ""
     var cpf = ""
     var idade = 99 
     var altura = 1.74 
     
     
 }
// Exercício - Faça uma ficha médica, apontando os resultados do último checkup de um paciente
// .Permitido usar a mesma classe Pessoa()

    
    
fun main() {
    
    
    // Exercício - Faça uma ficha médica, apontando os resultados do último checkup de um paciente
   // Permitido usar a mesma classe Pessoa ()
    

    /*
    
    val pessoa1 = Pessoa()
    pessoa1.nome = "Alana"
    println(pessoa1.nome)
    pessoa1.cpf = "734.173.154.73"
    println(pessoa1.cpf)
    pessoa1.idade = 21 
    println(pessoa1.idade)
    pessoa1.altura = 1.61 
    println(pessoa1.altura)
    pessoa1.tipoSanguineo = "AB+"
    println(pessoa1.tipoSanguineo)
    pessoa1.peso = 66
    println(pessoa1.peso)
    pessoa1.dependenteQuimico = "sim"
    println(pessoa1.dependenteQuimico)
    pessoa1.alergias = "não"
    println(pessoa1.alergias)
    pessoa1.medicação = "lítio"
    println(pessoa1.medicação)
    
    
    
    
    
}
 
 class Pessoa(){
     //declaração de atributos para a classe Pessoa
     var nome = ""
     var cpf = ""
     var idade = 21 
     var altura = 1.61 
     var tipoSanguineo = "AB+"
     var peso = 66
     var dependenteQuimico = "sim"
     var alergias = "não"
     var medicação = "lítio"
   
    
    
    */
   
    
    
    
}


//--------------------------------------------------------------------------------------------------------------------------------------------------------------------



fun main() {
    
    /*
    var jogador1 = JogadorDeFutebol("Thibaut Courtois", 1, "Guarda-Redes")
    var jogador2 = JogadorDeFutebol("João Cancelo", 2, "Lateral-Direito")
    var jogador3 = JogadorDeFutebol("Virgil Van Dijk", 3, "Zagueiro")
    var jogador4 = JogadorDeFutebol("Marquinhos", 4, "Zagueiro")
    var jogador5 = JogadorDeFutebol("Theo Hernández", 6, "Lateral-Esquerdo")
    var jogador6 = JogadorDeFutebol("Casemiro", 5, "Volante")
    var jogador7 = JogadorDeFutebol("Bruno Guimarães", 8, "Meio-Campo")
    var jogador8 = JogadorDeFutebol("Neymar Jr", 10, "Meia-Armador")
    var jogador9 = JogadorDeFutebol("Lionel Messi", 30, "Ponta-Esquerda")
    var jogador10 = JogadorDeFutebol("Vini Jr", 7, "Ponta-Esquerda")
    var jogador11 = JogadorDeFutebol("Earling Haaland", 9, "Controavante")
    
    println(jogador1.nome + " - " + jogador1.numeroDaCamisa + " - " + jogador1.posicao)
    println(jogador2.nome + " - " + jogador2.numeroDaCamisa + " - " + jogador2.posicao)
    println(jogador3.nome + " - " + jogador3.numeroDaCamisa + " - " + jogador3.posicao)
    println(jogador4.nome + " - " + jogador4.numeroDaCamisa + " - " + jogador4.posicao)
    println(jogador5.nome + " - " + jogador5.numeroDaCamisa + " - " + jogador5.posicao)
    println(jogador6.nome + " - " + jogador6.numeroDaCamisa + " - " + jogador6.posicao)
    println(jogador7.nome + " - " + jogador7.numeroDaCamisa + " - " + jogador7.posicao)
    println(jogador8.nome + " - " + jogador8.numeroDaCamisa + " - " + jogador8.posicao)
    println(jogador9.nome + " - " + jogador9.numeroDaCamisa + " - " + jogador9.posicao)
    println(jogador10.nome + " - " + jogador10.numeroDaCamisa + " - " + jogador10.posicao)
    println(jogador11.nome + " - " + jogador11.numeroDaCamisa + " - " + jogador11.posicao)
    
    
    //Exercício - Faça a escalação do seu time exibindo nome, número da camisa e posição
    //no mínimo 11 jogadores
    //permitido inventar jogadores
    */
    
    
    //Métodos/funções - são um grupo de ações que representam uma determinada atividade de um
    //determinado objeto
    //
    // Estrutura de um método no Kotlin
    // 
    // fun nomeDela (parametros - se tiver){
    // ações 
    // }
    // 
    // 
    // var nomeDoObjeto = classeDele
    // 
    // nomeDoObjeto.nomeDela()
    
    
    
}
class JogadorDeFutebol(var nome: String,
                       var numeroDaCamisa: Int,
                       var posicao: String){
    
   
    
   
    
    
    
    
    
    
    
    
    
    
    
}

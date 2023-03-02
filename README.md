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
    
    
}
}

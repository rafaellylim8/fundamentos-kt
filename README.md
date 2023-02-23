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
        
 
    
    
}

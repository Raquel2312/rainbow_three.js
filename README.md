
function_patentes_Conquistados()
{
        let bronze ="Bronze"
        let prata ="Prata"
        let ouro ="Ouro"
        let platina ="Plantina"
        let diamante ="Diamante"
        let lendario ="Lendario"
        let imortal ="Imortal"
        console.log("Patente 11,20"+bronze);
        console.log("Patente 21,50"+ prata);
        console.log("Patente 51,80"+ouro);
        console.log("Patente 81,120"+platina);
        console.log("Patente 91,100"+lendario);
        console.log("Patente 101,200"+imortal);
}
  

     function_jogador_Castiel()

{
        let nomeDoJogador="Castiel";
        let patenteDoJogador="Lendario";
        let tempoDeJogoEmHoras=120;
        let vitoriasConquistadas=30;
        let derrotasSofridas=20;
                console.log("nome Do Jogador:"+nomeDoJogador);
                console.log("Patente Do Jogador:"|+ patenteDoJogador);
                console.log("tempo De Jogo Em Horas:"+ tempoDeJogoEmHoras);
                console.log("Vitorias Conquistadas:"+ vitoriasConquistadas);
                console.log("derrotas sofridas:"+ derrotasSofridas);
}


        function_jogador_blut()
{
        let nomeDoJogador="Blut";
        let patenteDoJogador="Imortal";
        let tempoDeJogoEmHoras=250;
        let vitoriasConquistadas=200;
        let derrotasSofridas=50;
         console.log("Nome do Jogador:"+ nomeDoJogador);
            console.log("Patente do Jogador:"+ patenteDoJogador);
            console.log("Tempo de jogo em Horas"+ tempoDeJogoEmHoras);
            console.log("Vitorias Conquistadas:"+vitoriasConquistadas);
            console.log("Derrotas Sofridas:"+ derrotasSofridas);

    }
 
    function_patentes_Conquistadas()
    {
     console.log("Patentes Conquistadas pelo Jogador Castiel:");
     function_jogador_Castiel();
        console.log("Patentes Conquistadas pelo Jogador Blut");
         function_jogador_Blut();

    }

    function_resumo_dos_jogadores()
    {

        console.log("Resumo dos Jogadores:");
        function_jogador_Castiel();
        function_jogador_Blut();
        

    }

    function_O_Heroi_tem_o_Saldo()
    {
       console.log("O Heroi tem o Saldo de Patentes Conquistdas:");
        function_patentes_Conquistadas();
        console.log("Resumo dos Jogadores:");
        function_resumos_dos_jogadores();
    }

        O_Heroi_tem_o_Saldo();

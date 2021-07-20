<! doctype html >
< html >

    < cabeça >
        <! - Metadados ->
        < meta  charset = " utf-8 " >
        < meta  name = " viewport " content = " width = device-width, initial-scale = 1, shrink-to-fit = no " >
    
        <! - CSS ->
        < link  rel = " stylesheet " type = " text / css " href = " formulario.css " media = " screen " >

        <! - Título da página (aparece na aba) ->
        < title > Cadastro </ title >
    </ head >

    < corpo >  

        <! - Cabeçalho com título e subtítulo (ambos com css de id "titulo") ->
        < div >
            < h1  id = " titulo " > Cadastro de DEVs </ h1 >
            < p  id = " subtitulo " > Complete suas informações </ p >
            < Br >
        </ div >

        <! - Início do formulário ->
        < formulário >

            < fieldset  class = " grupo " >
                <! - Campo do nome com legenda "nome" e css de classe "campo" ->
                < div  class = " campo " >
                    < label  for = " nome " > < strong > Nome </ strong > </ label >
                    < input  type = " text " name = " nome " id = " nome " obrigatório >
                </ div >

                <! - Campo do sobrenome com legenda "sobrenome" e css de classe "campo" ->
                < div  class = " campo " >
                    < label  for = " sobrenome " > < strong > Sobrenome </ strong > </ label >
                    < input  type = " text " name = " sobrenome " id = " sobrenome " obrigatório >
                </ div >
            </ fieldset > 

            <! - Campo de email com ->
            < div  class = " campo " >
                < label  for = " email " > < strong > Email </ strong > </ label >
                < input  type = " email " name = " email " id = " email " obrigatório >
            </ div >

            <! - Campo de desenvolvimento web com 3 opções de botões selecionáveis ​​(botão de opção) e css de classe "campo" ->
            < div  class = " campo " >
                < label > < strong > De qual lado da aplicação você desenvolver? </ strong > </ label >
                < etiqueta >
                    < input  type = " radio " name = " devweb " value = " frontend " verificado > Front-end
                </ label >
                < etiqueta >
                    < input  type = " radio " name = " devweb " value = " backend " > Back-end
                </ label >
                < etiqueta >
                    < input  type = " radio " name = " devweb " value = " fullstack " > Fullstack
                </ label >
            </ div >

            <! - Campo de senioridade com 3 opções para escolha (selecionar opção) e css de classe "campo" ->
            < div  class = " campo " >
                < label  for = " senioridade " > < strong > Senioridade </ strong > </ label >
                < selecione  id = " senioridade " obrigatório >
                  < opção  selecionada  desabilitada  valor = "" > Selecione </ opção >
                  < opção > Júnior </ opção >
                  < opção > Pleno </ opção >
                  < opção > Sênior </ opção >
                </ select >
            </ div >

            < fieldset  class = " grupo " >
                <! - Campo de tecnologias para escolha de 1 ou mais opções para marcar (caixa de seleção) e css de classe "campo" ->
                < div  id = " check " >
                    < Rótulo > < strong > Selecione como Tecnologias Que utiliza: </ strong > </ rótulo > < br > < br >
                    < input  type = " checkbox " id = " tecnologia1 " name = " tecnologia1 " value = " HTML " >
                    < label  for = " tecnologia1 " > HTML </ label >
                    < input  type = " checkbox " id = " tecnologia2 " name = " tecnologia2 " value = " CSS " >
                    < label  for = " tecnologia2 " > CSS </ label >
                    < input  type = " checkbox " id = " tecnologia3 " name = " tecnologia3 " value = " JavaScript " >
                    < label  for = " tecnologia3 " > JavaScript </ label >
                    < input  type = " checkbox " id = " tecnologia4 " name = " tecnologia4 " value = " PHP " >
                    < label  for = " tecnologia4 " > PHP </ label >
                    < input  type = " checkbox " id = " tecnologia5 " name = " tecnologia5 " value = " C # " >
                    < label  for = " tecnologia5 " > C # </ label >
                    < input  type = " checkbox " id = " tecnologia6 " name = " tecnologia6 " value = " Python " >
                    < label  for = " tecnologia6 " > Python </ label >
                    < input  type = " checkbox " id = " tecnologia7 " name = " tecnologia7 " value = " Java " >
                    < label  for = " tecnologia7 " > Java </ label >
                </ div >
            </ fieldset >

            <! - Caixa de texto ->
            < div  class = " campo " >
                < Br >
                < label  for = " experiencia " > < strong > Conte um pouco mais da sua experiência: </ strong > </ label >
                < textarea  rows = " 6 " style = " width: 26em " id = " experiencia " name = " experiencia " > </ textarea >
            </ div >

            <! - Botão para enviar o formulário ->
            < button  class = " botao " type = " submit " onsubmit = "" > Concluído </ button >            

        </ form >

    </ body >

</ html >

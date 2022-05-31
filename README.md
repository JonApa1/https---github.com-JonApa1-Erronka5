# https---github.com-JonApa1-Erronka5
<!DOCTYPE html>
<html lang="eu">
<head>
    <!-- AWP_In_Variable Name='"Etapa1"' -->
    <!-- AWP_In_Variable Name='"Etapa5"' -->
    <!-- AWP_In_Variable Name='"Etapa13"' -->
    <!-- AWP_In_Variable Name='"Etapa3"' -->
    <!-- AWP_In_Variable Name='"Etapa4"' -->
    <!-- AWP_In_Variable Name='"Etapa12"' -->
    <!-- AWP_In_Variable Name='"Etapa7"' -->

    <meta charset="UTF-8">
    <meta name="description" content="ARI - Industria Informatikako webguneak 
    sortzeko baliabideen tutoriala" />
    <meta name="keywords" content="ARI,Automatizazioa,SIEMENS,TIA,
    web,tutoriala" />
    <meta name="author" content="Zure izena: Talde 1" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erronka 5</title>
    <link rel="stylesheet" href="./css/styles.css">
    <link rel="stylesheet" href="./css/styles-table-variables.css">
 
</head>

<body>
<main>
<div id="dvHMI">
    <div id="dvIzq">
        <div id="dvBotonera">
            <div><h4>BOTONES</h4></div>
            <div class="btnMarcha"><span>MARCHA</span>
            <form method="post">
                <input type="hidden" name='"Etapa1"' value="1"/> 
                <input type="submit" name='Marcha' value="Marcha"/> 
            </form>
            </div>
        </div>
    </div>

   
    <div id="dvProceso">
        <div id="dvCabecera">
            <h1>ERRONKA 5 "Talde 1"</h1>
        </div>
        <div id="dvDibujos">
            <table>
                <tr><th>DIANA A</th><th></th><th>DIANA B</th><th></th><th>DIANA C</th></tr>
             
                 <td id="tdDIANAA">
                        <form id="formDIANAA" method="POST" action="">
                        <img src="./img/i1.jpg"/>
                        <input type="hidden" name='"Etapa1"'  value="1"/>
                   	<div id="dvPilotos">
                        <div><h4>ESTADO</h4></div>
                        <div id="pilotoVerde"><img src="./img/FD.PNG" ></div>
                        <div id="pilotoRojo"><img src="./img/FI.PNG" ></div>
                  	</div>                        
                   	</form>

                    </td>
                    <td id="tdDIANAB"></td>
                    <td id="tdDB">
                        <form id="formDIANAB" method="POST" action="">
                        <img src="./img/i1.jpg"/>
                        <input type="hidden" name='"Etapa5"'  value="1"/>
                    	<div id="dvPilotos">
                        <div><h4>ESTADO</h4></div>
                        <div id="pilotoVerde"><img src="./img/FD.PNG" ></div>
                        <div id="pilotoRojo"><img src="./img/FI.PNG" ></div>
                  	</div>                        
                        </form>

 		    <td id="tdDIANAC"></td>
                    <td id="tdDC">
                        <form id="formDIANAC" method="POST" action="">
                        <img src="./img/i1.jpg"/>
                        <input type="hidden" name='"Etapa13"'  value="1"/>
                    	<div id="dvPilotos">
                        <div><h4>ESTADO</h4></div>
                        <div id="pilotoVerde"><img src="./img/FD.PNG" ></div>
                        <div id="pilotoRojo"><img src="./img/FI.PNG" ></div>
                  	</div>                        
                        </form>
                    </td>
                    </td>
            </table>
        </div>
    </div>
</div>

<form method="POST" action="" id="form01">
        <h1>ENTRADAS</h1>
        <table class="minimalistBlack">
            <caption>Activación de las ENTRADAS del proceso</caption>                
            <tbody>
                <tr>
                    <td>
                        <label for="marcha_for">Etapa 1</label>
                        <input type="text" name='"Etapa1"' id="Etapa1_id" value=':="Etapa1":'/>
                    </td>

                    <td>
                        <label for="Etapa3_for">Etapa 3</label>
                        <input type="text" name='"Etapa3"' id="Etapa3_id" value=':="Etapa3":'/>
                    </td>
                    
                    <td>
                        <label for="Etapa5_for">Etapa 5</label>
                        <input type="text" name='"Etapa5"' id="Etapa5_id" value=':="Etapa5":'/>
                    </td>

                    <td>
                        <label for="Etapa13_for">Etapa 13</label>
                        <input type="text" name='"Etapa13"' id="Etapa13_id" value=':="Etapa13":'/>
                    </td>

                    <td>
                        <label for="Etapa4_for">Etapa 4</label>
                        <input type="text" name='"Etapa4"' id="Etapa4_id" value=':="Etapa4":'/>
                    </td>
                </tr>   
                
                <tr><td colspan="5"><input type="submit" value="Bidali" id="btnSend"></td></tr>
            </tbody>
        </table>

</main> 

</body>

</html>

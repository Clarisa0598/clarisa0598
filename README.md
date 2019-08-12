# clarisa0598
<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <meta name="format-detection" content="telephone=no" />
    <meta name="msapplication-tap-highlight" content="no" />
    <meta name="viewport" content="user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1, width=device-width" />
    <!-- This is a wide open CSP declaration. To lock this down for production, see below. -->
    <meta http-equiv="Content-Security-Policy" content="default-src * 'unsafe-inline'; style-src 'self' 'unsafe-inline'; media-src *" />
    <!-- Good default declaration:
    * gap: is required only on iOS (when using UIWebView) and is needed for JS->native communication
    * https://ssl.gstatic.com is required only on Android and is needed for TalkBack to function properly
    * Disables use of eval() and inline scripts in order to mitigate risk of XSS vulnerabilities. To change this:
        * Enable inline JS: add 'unsafe-inline' to default-src
        * Enable eval(): add 'unsafe-eval' to default-src
    * Create your own at http://cspisawesome.com
    -->
    <!-- <meta http-equiv="Content-Security-Policy" content="default-src 'self' data: gap: 'unsafe-inline' https://ssl.gstatic.com; style-src 'self' 'unsafe-inline'; media-src *" /> -->

    
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link href="css/materialize.css" type="text/css" rel="stylesheet" media="screen,projection"/>
  <link href="css/style.css" type="text/css" rel="stylesheet" media="screen,projection"/>
    <title>My App</title>
</head>

<body>
    <nav class="page-footer teal" role="navigation">
    <div class="nav-wrapper container" >
      <div class="center sliding" ><h6>Ejercicios de Preguntas y Respuestas</h6></div>
    <!-- <a id="logo-container" href="index.html" class="brand-logo">PhoneGap</a>-->

  </nav>
          <article class="full-reset" id="mision-vision">
            <div class="page-header" style="margin-bottom:40px;">
              
            </div>
          </article>
          <!--======================================== prueba de examen ========================================-->
      <SCRIPT LANGUAJE="JavaScript">

function avisoreset() {
  if(confirm("¡ATENCIÓN!. Los datos del test seran Reiniciados.")) {
  document.cuestionario.reset();
  parent.location.reload();
  }
}

var pregunta1 = "0"; 
var pregunta2 = "0"; 
var pregunta3 = "0"; 
var pregunta4 = "0"; 
var pregunta5 = "0";  

function respuesta1(valor) 
{pregunta1 = valor}; 

function respuesta2(valor) 
{pregunta2 = valor}; 

function respuesta3(valor) 
{pregunta3 = valor}; 

function respuesta4(valor) 
{pregunta4 = valor}; 

function respuesta5(valor) 
{pregunta5 = valor}; 

</SCRIPT>
<script language="JavaScript" type="text/JavaScript">
function MM_reloadPage(init) {  //reloads the window if Nav5 resized
  if (init==true) with (navigator) {if ((appName=="Netscape")&&(parseInt(appVersion)==4)) {
    document.MM_pgW=innerWidth; document.MM_pgH=innerHeight; onresize=MM_reloadPage; }}
  else if (innerWidth!=document.MM_pgW || innerHeight!=document.MM_pgH) location.reload();
}
MM_reloadPage(true);
//-->
</script>
</HEAD>
<center>
<ul class="collection with-header">
                                <li class="center-align"><h4>Ejercicios de Matematicas </h4></li>

                                <li class="collection-item" >Para Primaria(6to)</li>
                            </ul></center>
<BODY BGCOLOR="#f8bbd0">

<FORM action="#" >         
1.- ¿Cuál es el número posterior al -15?
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta1" value="A" onclick="respuesta1('A')"/>
      <span>a) -14</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta1" value="B" onclick="respuesta1('B')"/>
      <span>b)  14</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta1" value="C" onclick="respuesta1('C')"/>
      <span>c)  10</span>
    </label></p>
<br>

2.- ¿Qué número es mayor?
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta2" value="A" onclick="respuesta2('A')"/>
      <span>a) -01</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta2" value="B" onclick="respuesta2('B')"/>
      <span>b)  -10</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta2" value="C" onclick="respuesta2('C')"/>
      <span>c)  -05</span>
    </label></p>
<br>


3.- ¿Qué números están ordenados correctamente?
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta3" value="A" onclick="respuesta3('A')"/>
      <span>a) -03 > -3</span>
    </label></p>

  <p class="left-align light">
        <label>
      <input class="with-gap"  type="radio" name="pregunta3" value="B" onclick="respuesta3('B')"/>
      <span>b) -10 > -05</span>
    </label></p>
    
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta3" value="C" onclick="respuesta3('C')"/>
      <span>c) -05 > -05</span>
    </label></p>
<br>

4.- ¿Qué número se sitúa más a la izquierda de la recta numérica?
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta4" value="A" onclick="respuesta4('A')"/>
      <span>a) -20.000</span>
    </label></p>

  <p class="left-align light">
        <label>
      <input class="with-gap"  type="radio" name="pregunta4" value="B" onclick="respuesta4('B')"/>
      <span>b) -20</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta4" value="C" onclick="respuesta4('C')"/>
      <span>c) -2.000</span>
    </label></p>
<br>

5.- ¿Qué número es menor?
  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta5" value="A" onclick="respuesta5('A')"/>
      <span>a) -78</span>
    </label></p>
    
  <p class="left-align light"></p>
    <label>
      <input class="with-gap"  type="radio" name="pregunta5" value="B" onclick="respuesta5('B')"/>
      <span>b) -25</span>
    </label></p>

  <p class="left-align light">
    <label>
      <input class="with-gap"  type="radio" name="pregunta5" value="C" onclick="respuesta5('C')"/>
      <span>c) -56</span>
        </label></p>
<br>
                                                                            
</FORM>

<SCRIPT language="JavaScript">

function examinar() 
{ 
puntuacion=0; 
nocontesta=0; 
contestadas=0; 
puntosmaximos=0; 

if(pregunta1!= "0" )
{
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta1 == "A") {puntuacion=puntuacion+20}
  if(pregunta1 == "B") {puntuacion=puntuacion+0}
  if(pregunta1 == "C") {puntuacion=puntuacion+0}
  
}
else {nocontesta=nocontesta+1} 

if(pregunta2 != "0")
{
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta2 == "A") {puntuacion=puntuacion+20}
  if(pregunta2 == "B") {puntuacion=puntuacion+0}
  if(pregunta2 == "C") {puntuacion=puntuacion+0}
  
}
else {nocontesta=nocontesta+1}

if(pregunta3!= "0" )
{
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta3 == "A") {puntuacion=puntuacion+20}
  if(pregunta3 == "B") {puntuacion=puntuacion+0}
  if(pregunta3 == "C") {puntuacion=puntuacion+0}

}
else {nocontesta=nocontesta+1} 

if(pregunta4 != "0")
{
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta4 == "A") {puntuacion=puntuacion+20}
  if(pregunta4 == "B") {puntuacion=puntuacion+0}
  if(pregunta4 == "C") {puntuacion=puntuacion+0}
}
else {nocontesta=nocontesta+1}

if(pregunta5!= "0" ){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta5 == "A") {puntuacion=puntuacion+20}
  if(pregunta5 == "B") {puntuacion=puntuacion+0}
  if(pregunta5 == "C") {puntuacion=puntuacion+0}
  
}
else {nocontesta=nocontesta+1} 


if (puntosmaximos!=0) 
{indiceacierto=Math.round(100*(puntuacion/puntosmaximos))
} 
else{indiceacierto=0} 


if(indiceacierto<=100&&indiceacierto>=90) 
{
mensaje="Excelente Muy Bien Sigue Asi"} 

if(indiceacierto<90&&indiceacierto>=80){
  mensaje="Muy Bien"} 

if(indiceacierto<70&&indiceacierto>=60){
  mensaje="Regular Deverias Estudiar Mas"} 

if(indiceacierto<50&&indiceacierto>=30){
  mensaje="Mal Echale Ganas"} 

if(indiceacierto<20&&indiceacierto>=0){
  mensaje="REPROBADOOO!!!!"} 

if(contestadas==0){
  mensaje=":-|"} 

alert("Tu puntuación es "+puntuacion+"." +  "\n\nEl número máximo de puntos que podía conseguir era de " + puntosmaximos + ".\n\nHa dejado sin contestar "+ nocontesta+".\n\nSu porcentaje de aciertos es de "+indiceacierto+"%.\n\n"+mensaje+". ") 
}

</SCRIPT>
<SCRIPT language="JavaScript">

function examinar() { 
  puntuacion=0; 
  nocontesta=0; 
  contestadas=0; 
  puntosmaximos=0; 

if(pregunta1!= "0" ){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta1 == "A") {puntuacion=puntuacion+20}
  if(pregunta1 == "B") {puntuacion=puntuacion+0}
  if(pregunta1 == "C") {puntuacion=puntuacion+0}
}
else {nocontesta=nocontesta+1} 

if(pregunta2 != "0"){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta2 == "A") {puntuacion=puntuacion+20}
  if(pregunta2 == "B") {puntuacion=puntuacion+0}
  if(pregunta2 == "C") {puntuacion=puntuacion+0}
}
else {nocontesta=nocontesta+1}

if(pregunta3!= "0" ){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta3 == "A") {puntuacion=puntuacion+20}
  if(pregunta3 == "B") {puntuacion=puntuacion+0}
  if(pregunta3 == "C") {puntuacion=puntuacion+0}
}
else {nocontesta=nocontesta+1} 

if(pregunta4 != "0"){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta4 == "A") {puntuacion=puntuacion+20}
  if(pregunta4 == "B") {puntuacion=puntuacion+0}
  if(pregunta4 == "C") {puntuacion=puntuacion+0}
}
else {nocontesta=nocontesta+1}

if(pregunta5!= "0" ){
  contestadas=contestadas+1
  puntosmaximos=puntosmaximos+20
  if(pregunta5 == "A") {puntuacion=puntuacion+20}
  if(pregunta5 == "B") {puntuacion=puntuacion+0}
  if(pregunta5 == "C") {puntuacion=puntuacion+0}
}

else {nocontesta=nocontesta+1} 

if (puntosmaximos!=0) {
  indiceacierto=Math.round(100*(puntuacion/puntosmaximos))
} 
else{indiceacierto=0} 

if(indiceacierto<=100&&indiceacierto>=90) {
  mensaje="Excelente Muy Bien Sigue Asi"} 

if(indiceacierto<90&&indiceacierto>=80){
  mensaje="Muy Bien"} 

if(indiceacierto<70&&indiceacierto>=60){
  mensaje="Regular Deverias Estudiar Mas"} 

if(indiceacierto<50&&indiceacierto>=30){
  mensaje="Mal Echale Ganas"} 

if(indiceacierto<20&&indiceacierto>=0){
  mensaje="REPROBADOOO!!!!"} 

if(contestadas==0){
  mensaje=":-|"} 
alert("Tu puntuación ="+puntuacion+"." +  "\n\nEl número máximo de puntos es de :" + puntosmaximos + ".\n\nPreguntas sin contestar "+ nocontesta+".\n\nPorcentaje de aciertos es de "+indiceacierto+"%.\n\n"+mensaje+". ")
}
</SCRIPT>
      <center>
        <input class="waves-effect waves-light btn" type="button" name="submit" value="Resultado del Cuestionario es:" onclick="examinar()"> 
         <!--<input class="waves-effect waves-light btn" type="button" name="Reset" value="Reinicar Cuestionario" onClick="avisoreset()">-->
        <input class="waves-effect waves-light btn" type="button" name="solucion" value="Respuestas Correctas" onclick="alert('RESPUESTAS CORRECTAS \n1:A \n2:A \n3:A \n4:A \n5:A')">
        <br><br>
      </center>
  </section>
</body>
        <footer class="page-footer teal">
    <div class="container">
      <div class="row">
        <div class="col l6 s12">
          <h5 class="white-text">Hecho por:Clarisa Medina Alvarez</h5>
        </div>
      </div>
    </div>
    <div class="footer-copyright">
      <div class="container">
        <!--Made by <a class="brown-text text-lighten-3" href="http://materializecss.com">PhoneGap</a>--> 
      </div>
    </div>
  </footer>
</html>

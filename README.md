# PHP

<h4>Tipos primitivos</h4>
<h5>Escalares</h5><br>
String: "Lorem ipsun"
Double: 3.145;
Int: 17;
bool: True or False;
// var_dump($variavel); //exibe o tipo da variavel e valor.
/Compostos:
> Arry: $ vet = [2, 4, 58, 96, 45]
> Object
/Especiais:
// DECLARAÇÃO DE VARIAVIES (Case Sensitive)
$Nome = "Tácio";
$Sobrenome = "Santos";
const pais = "Brasil";

//SAIDA DE DADOS 
//{ECHO} FAZ REFERENCIA QUE OS DADOS SAO PROCESSADOS NO SERVIDOR E O QUE O CLINETE VÊ REPRESENTA O ECO DAQUELA INFOMAÇÃO PARA O CLINETE COMO EM UMA CAVERNA.
ECHO OU PRINT "Seu nome é $Nome $Sobrenome, você mora no " . pais; //{.} representa concatenação no PHP.
// Sequencia de escape 
echo "$nome\"Lorem ipson\" $sobrenome";
<Saida> Tacio "Lorem ipson" Santos

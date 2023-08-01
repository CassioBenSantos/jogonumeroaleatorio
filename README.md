# jogonumeroaleatorio

let numeroMaximo = prompt("Entre com número máximo");
let numero = parseInt(Math.random () *numeroMaximo) +1;
let entrada = -1;
while (entrada != numero) {
    entrada = prompt("Entre com um número e tente acertar!");
    if(entrada > numero) alert ("Entrada maior que o número desejado!")
    if(entrada < numero) alert ("Entrada menor que o número desejado!")
    
}
alert("Parabéns você acertou!");

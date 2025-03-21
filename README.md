# arrays
atividade1
const sala1 = ['Maria','Flávia','Gabriel']
const sala2=['Rafael','Vinicius','Eduarda']

const salasunidas= sala1.concat(sala2)
console.log(salasunidas)

atividade2
const numeros= [1,2,3,4,5,6,7,8,9,10]
const parteNumeros = numeros.slice(3,7)
console.log(parteNumeros)

atividade 3
const frutas= ['Maçã', 'Banana', 'Laranja','Limão','Abacaxi']
frutas.splice(2,2,'Kiwi','pêssego')
console.log(frutas)

atividade 4
const menuPrincipal = ['nhoque', 'macarrão','parmegiana']
const menuDeSobremesas = ['Pudim', 'Torta holandesa','sorvete']
const menuCompleto = menuPrincipal.concat(menuDeSobremesas)
console.log(menuCompleto)

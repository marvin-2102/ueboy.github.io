let iniciar, regras, creditos, sair;//Variáveis para serem usados no menu

let value = 0;

function setup() {
createCanvas(1280, 720);
background('green');
}

function draw() {
  switch(menu()) {
    case 1:
    play();
    break;
    case 2:
    rules();
    break
    case 3:
    credits();
    break;
    case 4:
    quit();
    break;
  }

}

function menu() {
  fill('red');
  stroke('black');
  strokeWeight(3);
  rect(480, 100, 320, 90, 100);
  rect(480, 200, 320, 90, 100);
  rect(480, 300, 320, 90, 100);
  rect(480, 400, 320, 90, 100);
  
  textSize(48);
  fill('yellow');
  
  text('Jogar',580, 160);
  text('Regras',560, 260);
  text('Creditos',545, 360);
  text('Sair',590, 460);
}

function rules() {
  background('green');
  
  textSize(32);
  text('Testando');
}  

  
function credits() {
   //R, G, B
  background('#BDB76B');
   
  fill('white');
  stroke('black');
  strokeWeight(1);
  
  textSize(28);
  fill('black');
  
  text('The Last disease, é um jogo Feito para o trabalho final da disciplina de Lógica de Programação \n (LOP) do ano 2019.2 pelos alunos: Marcus Vinicius, Victor Alves e Ellen Dantas.', 40, 55);
}

function quit() {
   //R, G, B
  background('#BDB76B');
   
  fill('white');
  stroke('black');
  strokeWeight(1);
  
  textSize(28);
  fill('black');
  
  text('saindo', 40, 55);
  window.close();
}




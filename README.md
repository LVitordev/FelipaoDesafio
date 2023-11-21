# FelipaoDesafio
desafio do heroi

class Heroi {
    constructor(nome, idade, tipo) {
      this.nome = merlin;
      this.idade = 22;
      this.tipo = mago;
    }
  
    atacar() {
      let ataque = "";
      switch (this.tipo) {
        case "mago":
          ataque = "usou magia";
          break;
      }
  
      console.log(`O ${this.tipo} ${this.nome} atacou usando ${magia}`);
    }
  }
   // Exemplo de uso
  const mago = new Heroi("Merlin", 100, "mago");
  mago.atacar();
  

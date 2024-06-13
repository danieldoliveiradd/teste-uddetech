# TESTE - DESENVOLVEDOR UDDTECH

## Desafio de Programação em JavaScript

### Contexto:
Você receberá uma array de objetos que representam diferentes modelos de carros.
Cada objeto possui quatro propriedades: `marca`, `modelo`, `preco` e `quilometragem`.

### Tarefas:
1. Retornar todos os carros que têm um preço maior que 40 mil reais.
2. Retornar todos os carros que têm uma quilometragem inferior a 15 mil km.
3. Retornar todos os carros que têm a mesma marca especificada.
4. Retornar todos os carros que têm o mesmo modelo especificado.

### Resultado Esperado:
Crie um novo array contendo apenas os carros que atendem a pelo menos um dos critérios mencionados acima.
Não é necessário exibir ou imprimir os resultados, apenas preparar o array filtrado conforme especificado.

### Array a ser utilizado:

```javascript
const carros = [
    { marca: "Toyota", modelo: "Corolla", preco: 60000, quilometragem: 25000 },
    { marca: "Honda", modelo: "Civic", preco: 55000, quilometragem: 30000 },
    { marca: "Chevrolet", modelo: "Onix", preco: 45000, quilometragem: 20000 },
    { marca: "Ford", modelo: "Ka", preco: 35000, quilometragem: 15000 },
    { marca: "Volkswagen", modelo: "Gol", preco: 38000, quilometragem: 18000 },
    { marca: "Hyundai", modelo: "HB20", preco: 42000, quilometragem: 22000 },
    { marca: "Renault", modelo: "Kwid", preco: 39000, quilometragem: 17000 },
    { marca: "Fiat", modelo: "Argo", preco: 48000, quilometragem: 24000 },
    { marca: "Jeep", modelo: "Renegade", preco: 65000, quilometragem: 28000 },
    { marca: "Nissan", modelo: "Kicks", preco: 52000, quilometragem: 26000 },
    { marca: "Chevrolet", modelo: "Tracker", preco: 58000, quilometragem: 30000 },
    { marca: "Volkswagen", modelo: "T-Cross", preco: 60000, quilometragem: 28000 },
    { marca: "Toyota", modelo: "Yaris", preco: 47000, quilometragem: 23000 },
    { marca: "Honda", modelo: "Fit", preco: 49000, quilometragem: 20000 },
    { marca: "Ford", modelo: "EcoSport", preco: 53000, quilometragem: 25000 },
    { marca: "Hyundai", modelo: "Creta", preco: 56000, quilometragem: 27000 },
    { marca: "Renault", modelo: "Duster", preco: 50000, quilometragem: 22000 },
    { marca: "Fiat", modelo: "Mobi", preco: 32000, quilometragem: 12000 },
    { marca: "Jeep", modelo: "Compass", preco: 70000, quilometragem: 32000 },
    { marca: "Nissan", modelo: "Versa", preco: 42000, quilometragem: 18000 },
    { marca: "Chevrolet", modelo: "S10", preco: 90000, quilometragem: 35000 },
    { marca: "Volkswagen", modelo: "Virtus", preco: 45000, quilometragem: 19000 },
    { marca: "Toyota", modelo: "Hilux", preco: 110000, quilometragem: 40000 },
    { marca: "Honda", modelo: "City", preco: 52000, quilometragem: 24000 },
    { marca: "Ford", modelo: "Ranger", preco: 98000, quilometragem: 38000 },
    { marca: "Hyundai", modelo: "Santa Fe", preco: 135000, quilometragem: 42000 },
    { marca: "Renault", modelo: "Captur", preco: 55000, quilometragem: 27000 },
    { marca: "Fiat", modelo: "Uno", preco: 28000, quilometragem: 15000 },
    { marca: "Jeep", modelo: "Wrangler", preco: 150000, quilometragem: 50000 },
    { marca: "Nissan", modelo: "March", preco: 34000, quilometragem: 16000 }
];
```


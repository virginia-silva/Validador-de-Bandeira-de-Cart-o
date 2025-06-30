# 🧾 Validador de Bandeira de Cartão de Crédito
 
Este projeto JavaScript identifica a **bandeira** de um cartão de crédito com base no número inserido, utilizando expressões regulares.
 
## 🚀 Como funciona
 
A função `getCardFlag` recebe um número de cartão (como string), remove todos os caracteres não numéricos e compara com padrões conhecidos de bandeiras.
 
### Bandeiras suportadas:
- Visa
- MasterCard
- American Express (Amex)
- Diners Club
- Discover
- Hipercard
- Elo
- JCB
- Aura
 
## 💻 Exemplo de uso
 
```javascript
var bandeira = vls.getCardFlag('4111111111111111');
console.log(bandeira); // Saída: 'visa'

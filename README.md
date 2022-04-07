# Chatbot de Delivery com KNN

<!DOCTYPE html>
<html lang="pt-br">
<meta charset="utf-8"/>
  <body width=100%>
      <h3>O chatbot responde às seguintes intenções:</h3>
      <div>
          <ul>
              <li>Pedir o cardápio</li>
              <li>Adicionar item ao pedido</li>
              <li>Pedir a conta</li>
              <li>Inserir endereço para entrega</li>
              <li>Inserir forma de pagamento</li>
              <li>Acompanhar status do pedido</li>
              <li>Cancelar o pedido</li>
          </ul>
          <p>Algumas entradas são tratadas de forma "manual" para melhor controle do fluxo do pedido.</p>
          <p>Os itens são identificados pelas suas variações mais comuns, seguindo o dicionário <em>items_variation</em>. O item de entrada não será adicionado caso não esteja contido em alguma dessas variações.</p>
          <p>O tempo de preparo e de entrega do pedido são calculados de forma aleatória em um intervalo de tempo arbitrário, em segundos, para simulação de visualização do progresso dos processos mencionados.</p>
      </div>
      <hr>
      <div>
          <h3>Cardápio:</h3>
          <h4>Lanches:</h4>
          <ul>
              <li>xburguer → R$12,50</li>
              <li>xbacon → R$14,00</li>
              <li>xsalada → R$15,00</li>
              <li>batata frita → R$9,00</li>
          </ul>
      </div>
      <div>
          <h4>Bebidas:</h4>
          <ul>
              <li>suco de laranja → R$7,00</li>
              <li>coca cola → R$6,00</li>
              <li>guaraná → R$8,00</li>
          </ul>
      </div>
  </body>
</html>

# Forward from

## Introdução

Esse documento aborda a aplicação do método de rastreabilidade forward-from. A rastreabilidade de requisitos desempenha um papel crucial no desenvolvimento de sistemas. Ela permite não apenas identificar e conectar requisitos durante a fase de desenvolvimento, mas também rastreá-los ao longo de todo o ciclo de vida do sistema. Isso se traduz em uma compreensão mais clara das origens e implicações de cada requisito, contribuindo para a garantia da qualidade, gestão eficiente de mudanças e alinhamento contínuo com as necessidades do cliente. Quando aplicamos o método de rastreabilidade forward-from, estamos focados em estabelecer vínculos sólidos entre os requisitos e os desenhos do sistema e implementações [1].

## Metodologia

A metodologia a ser usada será a matriz de rastreabilidade com o uso de referências cruzadas [1], aplicada aos [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/requisitos-elicitados/) e os artefatos desenvolvidos após o processo de elicitação nas etapas [modelagem de requisitos](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/) e [ágil](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/). A relação entre um requisito e um tipo de artefato não é da ordem de um para um, por exemplo, um requisito pode estar presente em mais de um caso de uso. A tabela 1 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representará o artefato criado a partir do requisito.

Os requisitos podem estar ligados a épicos, temas, histórias do usuário, léxicos, casos de usos e cenários. Esses artefatos serão representados nas colunas da matriz de rastreabilidade e são preenchidas com o id/nome do artefato.

## Matriz de rastreabilidade Forward-From

A tabela 1 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representará o artefato criado a partir do requisito.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Matriz de rastreabilidade Forward-from</p></font>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Épico</th>
      <th>Tema</th>
      <th>História de usuário</th>
      <th>Léxico</th>
      <th>Casos de Uso</th>
      <th>Cenários</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>INT01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs01---efetuar-login-com-email-e-senha">HS01</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs02-hs02---efetuar-login-com-govbr">HS02</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT04</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs04---efetuar-logout">HS04</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT05</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs05---listar">HS05</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT06</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs06---pesquisar">HS06</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT07</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs07---visualizar-detalhes">HS07</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT08</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs08---imprimir-danfe">HS08</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT09</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#us09---cadastrar">HS09</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT10</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT11</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/historia-de-usuario.md#hs10---consultar-d%C3%A9bitos-de-ipva">HS10</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT12</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT13</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT14</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT15</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT16</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep07---parcelamentos-administrativos">EP07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT17</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT18</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT19</td>
       <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep07---parcelamentos-administrativos">EP07</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT20</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep08---fale-conosco">EP08</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T04</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT21</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep09---ajuda">EP09</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T04</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT22</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT23</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep02---nota-fiscal">EP02</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T02</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr><tr>
      <td>INT24</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT25</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep01---login">EP01</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T01</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT26</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT27</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT28</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep03---ve%C3%ADculos">EP03</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT29</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep04---im%C3%B3veis">EP04</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT30</td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#ep05---d%C3%ADvida-ativa">EP05</a></td>
      <td><a href="https://github.com/Requisitos-de-Software/2023.2-Economia-DF/blob/main/docs/modelagem/agil/backlog.md#temas">T03</td>
      <td><a href="">HS</a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/GZaranza">Gabriel Zaranza</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Elos

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Matriz de rastreabilidade Forward-from</p></font>

<table>
  <thead>
    <tr>
      <th>Requisito</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>INT01</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>INT02<br>INT03</td>
    </tr>
    <tr>
      <td>INT02</td>
      <td></td>
      <td></td>
      <td></td>
      <td>INT01</td>
      <td></td>
    </tr>
    <tr>
      <td>INT03</td>
      <td></td>
      <td></td>
      <td></td>
      <td>INT01</td>
      <td></td>
    </tr>
    <tr>
      <td>INT04</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT05</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Notal Fiscal<br><br><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#consultar-nota-fiscal">Cenário - Consultar Notal Fiscal<br></a</a></td>
      <td></td>
      <td></td>
      <td>INT06<br>INT07<br>INT08</td>
    </tr>
    <tr>
      <td>INT06</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Notal Fiscal<br></a></td>
      <td></td>
      <td>INT05</td>
      <td></td>
    </tr>
    <tr>
      <td>INT07</td>
      <td></a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Notal Fiscal<br></a></td>
      <td></td>
      <td>INT05</td>
      <td></td>
    </tr>
    <tr>
      <td>INT08</td>
      <td></a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Notal Fiscal<br></a></td>
      <td></td>
      <td>INT05</td>
      <td></td>
    </tr>
    <tr>
      <td>INT09</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Veículo<br></a></td>
      <td></td>
      <td></td>
      <td>INT10<br>INT11</td>
    </tr>
    <tr>
      <td>INT10</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Veículo<br></a><br><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#consultar-veiculo">Cenário - Consultar Veículos<br></a></td>
      <td></td>
      <td>INT09</td>
      <td></td>
    </tr>
    <tr>
      <td>INT11</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Veículo<br></a></td>
      <td></td>
      <td>INT09</td>
      <td></td>
    </tr>
    <tr>
      <td>INT12</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT13</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Imóvel<br></a><br><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#consultar-imovel">Cenário - Consultar Imóvel<br></a></td>
      <td></td>
      <td></td>
      <td>INT14<br>INT15<br>INT29</td>
    </tr>
    <tr>
      <td>INT14</td>
      <td>INT13</td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Imóvel<br></a></td>
      <td></td>
      <td>INT13</td>
      <td></td>
    </tr>
    <tr>
      <td>INT15</td>
      <td>INT13</td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/lexicos/#objetoso">Léxico -  Imóvel<br></a></td>
      <td></td>
      <td>INT13</td>
      <td></td>
    </tr>
    <tr>
      <td>INT16</td>
      <td>INT19</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT17</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#consultar-divida-ativa">Cenário - Consultar dívida ativa<br></a></td>
      <td></td>
      <td></td>
      <td>INT30</td>
    </tr>
    <tr>
      <td>INT18</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT19</td>
       <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#consultar-parcelamentos-administrativos">Cenário - Consultar Parcelamentos Administrativos<br></a></td>
      <td></td>
      <td></td>
      <td>INT16</td>
    </tr>
    <tr>
      <td>INT20</td>
      <td></td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/cenarios/#fale-conosco">Cenário - Fale conosco<br></a></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT21</td>
      <td><a href="https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#ajuda-e-documentacao">AD03<br></a></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT22</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT23</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr><tr>
      <td>INT24</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT25</td>
     <td></td>
      <td></td>
      <td></td>
      <td>INT01</td>
      <td></td>
    </tr>
    <tr>
      <td>INT26</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT27</td>
     <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT28</td>
     <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>INT29</td>
     <td>INT13</td>
      <td></td>
      <td></td>
      <td>INT13</td>
      <td></td>
    </tr>
    <tr>
      <td>INT30</td>
     <td>INT17</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/GZaranza">Gabriel Zaranza</a> e <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>


## Referências Bibliográficas

> SAYÃO, Miriam; DO PRADO LEITE, Julio Cesar Sampaio. Rastreabilidade de requisitos. RITA, v. 13, n. 1, p. 57-86, 2006.
>

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|15/11/2023|Criação do documento|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
|`1.1`|15/11/2023|Requisitos de 1 a 15|[Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
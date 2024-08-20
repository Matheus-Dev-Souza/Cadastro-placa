# Sistema de Cadastro de Placas

Este projeto é um sistema web para cadastro, consulta e geração de relatórios de placas de veículos. Ele permite que os usuários cadastrem fotos de placas, consultem informações de placas específicas e gerem relatórios baseados na cidade.
<p> 📌 Link:  https://18.204.4.40<](https://cadastro-placa-li1w3bp2d-matheus-s-projects-f2fe4fd5.vercel.app </p> 
## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Estrutura do Projeto

- `index.html`: Página principal do sistema.
- `styles.css`: Arquivo de estilos para a página.
- `script.js`: Arquivo de scripts para manipulação do DOM e interações.

## Funcionalidades

### Cadastrar Placa

Permite o cadastro de uma nova placa com foto e cidade.

```html
<form id="cadastroPlacaForm">
  <label for="foto">Foto da Placa:</label>
  <input type="file" id="foto" name="foto" required>

  <label for="cidade">Cidade:</label>
  <input type="text" id="cidade" name="cidade" required>

  <button type="submit">Enviar</button>
</form>
```

### Consultar Placa

Permite a consulta de informações de uma placa específica pelo número da placa.

```html
<form id="consultaPlacaForm">
  <label for="placa">Número da Placa:</label>
  <input type="text" id="placa" name="placa" required>

  <button type="submit">Consultar</button>
</form>
```

### Gerar Relatório por Cidade

Permite a geração de um relatório de placas cadastradas em uma cidade específica.

```html
<form id="relatorioCidadeForm">
  <label for="cidadeRelatorio">Cidade:</label>
  <input type="text" id="cidadeRelatorio" name="cidadeRelatorio" required>

  <button type="submit">Gerar Relatório</button>
</form>
```

## Como Usar

1. Clone o repositório para sua máquina local.
2. Abra o arquivo `index.html` em um navegador web.
3. Utilize as funcionalidades de cadastro, consulta e geração de relatórios conforme necessário.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.


# TrabalhoPraticoL1

Alunos:

Igor da Silva Villamarim - GEC - 1641<br />
Ramon Adônis Pereira de Abreu - GEC - 1581<br />

Boa noite, nosso projeto consiste em um suíte de testes para verificar se um site está funcionando corretamente! Utilizamos a ferramenta Cypress, e escolhemos o site "https://automacaocombatista.herokuapp.com/treinamento/home"

Primeiramente abriremos o Cypress com o seguinte comando: "./node_modules/.bin/cypress open"

Logo em seguida, após a execução do Cypress, ele fará os testes de acordo com o que foi implementado pela gente! (utilizando "cy.visit" para visitar os sites, e utilizando "cy.get" para clicar, digitar e verificar textos de acordo com o que era esperado)

1° teste: Teste para testar se a criação/cadastro do usuário está funcionando corretamente! 

(Nesse teste, o Cypress visitará o site, clicará nas opções para criar/cadastrar um usuário e entrará com dados para verificar se essa função do site está funcionando corretamente!) 


2° teste: Teste para testar se a atualização de usuário está funcionando corretamente!

(Nesse teste, o Cypress visitará o site, clicará nas opções para atualizar um usuário, apagará os dados cadastrados e entrará com novos dados para verificar se essa função do site está funcionando corretamente!)


3° teste: Teste para saber se o site mostra quando alguém tenta criar/cadastrar um usuário inválido!

(Nesse teste, o Cypress visitará o site, clicará nas opções para criar/cadastrar um usuário e entrará com dados errôneos para verificar se o site mostrará a mensagem de erro, e depois, não deixe os dados errôneos serem cadastrados!)


4° teste: Teste para saber se um botão do site está funcionando corretamente!

(Nesse teste, o Cypress visitará o site, e clicará em um botão específico, e verificará se uma mensagem com o texto "Você Clicou no Botão" aparecerá, para verificar se essa função do site está funcionando corretamente!)


5° teste: Teste para saber se a opção de abrir em nova janela está funcionando corretamente!

(Nesse teste, o Cypress visitará o site, e tentará abrir uma nova janela, para verificar se essa função do site está funcionando corretamente!)


6° teste: Teste para saber um botão com um link do site está funcionando corretamente!

(Nesse teste, o Cypress visitará o site, clicará em um link, e verificará se uma mensagem com o texto "Bad Request!!" aparecerá, para verificar se essa função do site está funcionando corretamente!)


Logo após a realização de todos esses testes, geraremos um relatório para ter uma melhor análise sobre eles!<br />
O relátorio é gerado com o seguinte comando: "./node_modules/.bin/cypress run --spec 'cypress/e2e/**/"<br />

Após o relatório ter sido gerado, nossa suíte de testes está completa e o relatório pronto para ser avaliado de acordo com o que foi implementado!!! 



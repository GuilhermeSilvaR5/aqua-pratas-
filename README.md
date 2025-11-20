Justificativa Técnica e Estratégica: Implementações JavaScript 

Foco Atual e Escopo do Projeto 

No atual estágio de desenvolvimento do projeto Aqua Pratas, a estratégia principal é garantir uma presença digital sólida, rápida e com foco absoluto na conversão e engajamento em plataformas externas. 

Analisando o público-alvo e os objetivos de negócio, o foco do website é atuar como uma vitrine de apresentação de alta qualidade e um ponto de direcionamento estratégico. Implementações em JavaScript, implementação de um filtro para exibir apenas itens em estoque, criação de uma aba de contato para aprimorar a comunicação entre a empresa e o cliente, e melhorias na interação geral do usuário com o site. 

O sucesso inicial do site será medido pela clareza das informações, pela qualidade visual e pela eficiência em direcionar o usuário para a principal plataforma de vendas e engajamento da marca, o Instagram ou o canal de contato direto. Manter o código-base simples e focado em HTML/CSS solido e funcional. 

Embora a simplicidade seja a chave para o lançamento, reconhecemos o potencial de aprimoramento e deixamos registrado o que pode ser desenvolvido em etapas posteriores. 

No futuro, essas são as implementações que podem ser desenvolvidas usando JavaScript para refinar a experiência do usuário e expandir as funcionalidades: 

Validação de Formuário: 

Implementar um feedback imediato para a cliente ao preencher o formulário de contato, garantindo que a mensagem seja enviada sem erros ou frustrações. 

Implementar um campo de avaliação e nota para os itens, com base no feedback dos clientes. 

Galerias de Imagens: 

Desenvolver carrosséis interativos e responsivos para as coleções, permitindo que a cliente explore as peças com um toque. 

Filtros de Busca Intuitivos: 

Caso nosso catálogo cresça e se torne mais robusto, podemos adicionar filtros dinâmicos que organizam as joias por estilo, material ou cor em um piscar de olhos, facilitando a descoberta. 

Checklist de Acessibilidade (Status Final) 

O objetivo desta verificação é garantir que o projeto atende aos requisitos mínimos de acessibilidade. 

HTML Semântico  

Uso correto das tags HTML5 para definir as principais regiões da página. 

O <h1> é usado uma única vez por página, garantindo estrutura clara. 

A hierarquia é respeitada, utilizando <h2> para seções principais. 

Imagens e Multimídia 

A imagem do logo possui alt="Aqua Pratas". 

A imagem de fundo é carregada via CSS (ideal para decoração). Requisito: Manter atenção para garantir que futuras imagens decorativas adicionadas no HTML recebam o atributo alt="". 

Formulários 

Verificado no contato.html: Associações label + for/id estão implementadas corretamente para todos os campos. 

Uso do atributo required no HTML em todos os campos. 

O formulário utiliza apenas o elemento <label> explícito para identificação do campo. 

Navegação por Teclado 

Uso de tags nativas (<a> e <button>) que são tabuláveis por padrão. 

O arquivo style.css não possui a regra :focus para elementos interativos, o que impede a visualização clara do elemento ativo para usuários de teclado. 

Linha:   

:focus { 

  outline: 2px solid #005fcc; 

  outline-offset: 2px; 

} 

O skip link (link oculto que aparece ao focar) não foi implementado nos arquivos HTML, dificultando a navegação de usuários de teclado. 

Sugestão:  

<a href="#main-content" class="skip-link">Pular para o conteúdo principal</a> 

 

(Mencionar CSS TBM)  

.skip-link { 

  position: absolute; 

  left: -999px; 

} 

.skip-link:focus { 

  left: 0; 

} 

Teste: 

# Aqua Pratas

Site informativo desenvolvido para apresentar os serviços, produtos e contato da loja Aqua Pratas.  
O projeto foi criado como parte de atividades acadêmicas, utilizando HTML, CSS e JavaScript.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Pages (publicação do site)

---

## Acesso ao Site

- Link do GitHub Pages:  
  https://lara-rodriguess.github.io/aqua-pratas-/servicos.html

- Captura de tela do site publicado:  
  ![Captura do site Aqua Pratas](images/print-site.png)

- Data de publicação:  
  19/11/2025

---

## Testes de Publicação

Durante a verificação do site no GitHub Pages, foi confirmado que:

- Todas as páginas estão carregando corretamente  
- As imagens estão visíveis e sem erro de caminho  
- Os estilos CSS estão sendo aplicados  
- O JavaScript funciona normalmente (quando presente)  
- Todos os arquivos utilizam caminhos relativos, garantindo o funcionamento online

---

## Como Contribuir

1. Faça o fork do repositório  
2. Crie uma branch nova:  
   ```bash

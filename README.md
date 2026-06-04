# notebooklm-ia-tutora-aprendizado-programacao
Caderno temático criado com o NotebookLM para analisar como a IA ajuda e atrapalha estudantes iniciantes no aprendizado de programação.

# Inteligência artificial como tutora para aprender programação

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio do bootcamp da DIO em parceria com a Lupo.

Em meu percurso de aprendizagem na programaçao por conta própria, por vezes me deparei com situações onde o material digamos assim "livre" na internet não fornecia a resposta adequada a situação e afim de evitar perca de tempo, era comum que recorresse a inteligência artificial. 

Durante esse processo, percebi que ferramentas de inteligência artificial podem facilitar bastante o acesso a explicações, exemplos e orientações rápidas. Em contraponto, o uso excessivo da ferramenta como também o uso sem orientação e sem contexto devido pode resultar em frustração pois o aprendizado não se torna produto do tempo dedicado no uso ferramenta.

Receber uma resposta pronta pode economizar tempo, mas isso não significa necessariamente que houve aprendizado. Uma ferramenta que deveria funcionar como tutora também pode gerar dependência, apresentar respostas incorretas ou entregar códigos avançados demais para o nível do estudante.

Por isso, o foco deste caderno temático não é defender ou rejeitar o uso da IA. A proposta é analisar como ela pode ser utilizada como apoio sem substituir a prática, o raciocínio e o desenvolvimento da lógica de programação.

## Objetivos

O objetivo principal deste projeto é analisar como a inteligência artificial generativa pode ser utilizada como uma tutora para estudantes iniciantes de programação.

Os objetivos específicos são:

* identificar situações em que a IA facilita o aprendizado;
* observar riscos e limitações do uso da ferramenta;
* entender como a IA pode afetar a autonomia do estudante;
* refletir sobre o risco de copiar códigos sem compreender a lógica;
* reunir cuidados para utilizar a IA como apoio, e não como substituta do raciocínio;
* criar um miniguia simples para estudantes iniciantes;
* registrar prompts que possam ser reutilizados em estudos futuros.

## Ferramenta utilizada

O caderno temático foi criado no NotebookLM.

Foram adicionadas cinco fontes acadêmicas relacionadas ao uso de inteligência artificial generativa no ensino e na aprendizagem de programação.

Depois disso, foram utilizadas duas configurações diferentes no chat do NotebookLM. As mesmas seis perguntas foram repetidas nas duas configurações para observar como a forma de orientar a IA alterava as respostas.

## Curadoria de fontes

| Fonte                                                                                                                                                                                                                                                             | Contribuição para o projeto                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Uso de IA Generativa no Apoio à Aprendizagem de Programação — Rafael Almeida de Bem](https://repositorio.pucrs.br/dspace/handle/10923/26764)                                                                                                                     | Trabalho de conclusão de curso que discute o uso de IA generativa como apoio personalizado na disciplina de Fundamentos da Programação, incluindo benefícios e limitações. |
| [Análise das Respostas de LLMs em Relação ao Conteúdo Introdutório de Programação: um Comparativo entre o ChatGPT e o Gemini — Luiz Carlos Pereira Filho, Talita de Paula Cypriano de Souza e Luciano Bernardes de Paula](https://doi.org/10.5753/rbie.2025.4477) | Estudo que compara respostas do ChatGPT e do Gemini em conteúdos introdutórios de programação e destaca que as respostas não devem ser aceitas sem verificação.            |
| [Avaliando resoluções de exercícios introdutórios de programação na era das IAs Generativas: um estudo de caso com o ChatGPT — William Simão de Deus e colaboradores](https://doi.org/10.5753/sbie.2024.242283)                                                   | Estudo sobre padrões encontrados em códigos produzidos pelo ChatGPT e diferenças em relação a códigos normalmente escritos por estudantes iniciantes.                      |
| [ChatGPT no auxílio da aprendizagem de programação: um estudo de caso — Silvino Marques da Silva Junior e colaboradores](https://doi.org/10.5753/sbie.2023.234873)                                                                                                | Estudo de caso que analisa o ChatGPT como ferramenta auxiliar no aprendizado de programação, considerando explicações, exemplos, feedback e os riscos de dependência.      |
| [Literature Review on the Integration of Generative AI in Programming Education — Jemimah Nathaniel, Solomon Sunday Oyelere, Jarkko Suhonen e Matti Tedre](https://doi.org/10.1007/s40593-025-00524-3)                                                            | Revisão de literatura sobre a integração da IA generativa no ensino de programação, com atenção à preservação da lógica, da autonomia e do pensamento crítico.             |

## Engenharia de prompts e cicatrizes

### Primeira configuração

A primeira configuração utilizada no NotebookLM foi propositalmente simples:

> Você será um especialista em aprendizado focado em IA para estudo da programação.

Essa instrução gerou respostas úteis, mas com uma abordagem mais ampla.

### Segunda configuração

Depois, utilizei uma configuração mais direcionada ao tema:

> Baseando-se nas fontes adicionadas, quero que você comporte-se como um analista situacional do caso, alguém que esta para estudar qual a utilidade da IA (seu objeto de estudo) como ferramenta para um terceiro (seu individuo de estudo) que esta a utiliza-la como intrutor para aprender programação, independente da linguagem.
>
> O foco é o estudante (individuo de estudo) e suas dificuldades e facilidades ao utilizar a inteligencia artificial para obter aprendizado na area de programaçao.

### Perguntas realizadas

As mesmas seis perguntas foram feitas nas duas configurações:

1. É possível aprender programação utilizando a inteligência artificial?
2. Em quais tarefas a IA pode acelerar o aprendizado de programação?
3. Em quais situações a IA pode atrapalhar o desenvolvimento do aluno?
4. Como usar IA para revisar erros sem copiar cegamente ou como pedir para que ela explique determinado assunto sem que ela defina o código pronto?
5. Como transformar uma resposta da IA em exercício prático ou como devo configurar uma IA como tutor pessoal?
6. Como devo observar que a IA está me ajudando? Como saber que aquela resposta está correta?

### Por que as perguntas foram repetidas?

As perguntas foram mantidas iguais para facilitar a comparação das respostas desenvolvidas pelos prompts.

Dessa forma, a principal variável alterada foi a configuração inicial do chat. Isso permitiu observar se uma orientação mais específica mudava o foco das respostas.

### Evolução registrada

A primeira configuração produziu respostas úteis, mas mais genéricas.

Na segunda configuração, o estudante foi definido com maior clareza como indivíduo de estudo. As respostas passaram a destacar melhor:

* as dificuldades enfrentadas pelo iniciante;
* as facilidades oferecidas pela IA;
* os riscos de dependência;
* a necessidade de manter autonomia;
* a importância de desenvolver lógica e pensamento crítico.

A principal cicatriz do processo foi perceber que uma configuração ampla pode gerar respostas corretas, mas não necessariamente alinhadas ao recorte escolhido para o estudo.

A documentação completa dos dois testes está disponível em:

* [Registro de prompts e respostas do NotebookLM](docs/registro-prompts-notebooklm.md)

## Resumo das respostas obtidas

| Pergunta                                                       | Síntese da resposta obtida                                                                                                                                        |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| É possível aprender programação utilizando IA?                 | Sim, desde que a IA seja usada como ferramenta auxiliar. Ela pode explicar conceitos, apresentar exemplos e oferecer suporte rápido, mas não substitui a prática. |
| Em quais tarefas a IA pode acelerar o aprendizado?             | Explicação de conceitos, exemplos de código, identificação de erros, feedback imediato e divisão de problemas em etapas menores.                                  |
| Quando a IA pode atrapalhar?                                   | Quando entrega soluções prontas, gera dependência, apresenta respostas incorretas ou utiliza estruturas avançadas demais para o nível do estudante.               |
| Como revisar erros sem copiar cegamente?                       | Pedindo pistas graduais, explicações sobre o tipo de erro e orientações sobre o raciocínio, sem solicitar diretamente o código corrigido.                         |
| Como transformar respostas em exercícios?                      | Utilizando a IA para criar desafios, exercícios de depuração e perguntas de revisão, deixando a tentativa de resolução com o estudante.                           |
| Como saber se a IA está ajudando e se a resposta está correta? | Testando o código, comparando a resposta com o conteúdo estudado e verificando se o estudante consegue explicar e refazer a solução sem ajuda.                    |

## Miniguia de estudo

### Como a IA pode ajudar

A inteligência artificial pode ser útil para estudantes iniciantes quando funciona como uma ferramenta de apoio.

Entre os principais benefícios estão:

* **Explicação de conceitos:** a IA pode reformular explicações e apresentar exemplos mais simples.
* **Feedback rápido:** o estudante consegue receber uma orientação no momento em que encontra uma dificuldade.
* **Apoio na correção de erros:** a ferramenta pode ajudar a identificar problemas de sintaxe ou lógica.
* **Estudo no próprio ritmo:** o aluno pode pedir novas explicações sempre que necessário.
* **Redução do receio de errar:** perguntar para uma ferramenta pode ser mais confortável para quem ainda tem vergonha de expor dúvidas.
* **Divisão de problemas:** a IA pode ajudar a separar um exercício complexo em etapas menores.

### Como a IA pode atrapalhar

A facilidade de obter respostas também traz riscos.

Os principais cuidados são:

* **Respostas incorretas:** a IA pode responder com segurança mesmo quando está errada.
* **Cópia sem compreensão:** obter um código pronto não significa entender como ele funciona.
* **Dependência excessiva:** o estudante pode perder a confiança para resolver problemas sozinho.
* **Soluções avançadas demais:** a ferramenta pode usar recursos desnecessários para alguém que ainda está aprendendo o básico.
* **Falsa sensação de aprendizado:** compreender uma explicação enquanto lê não significa conseguir aplicar o conceito depois.
* **Redução da prática:** lógica de programação exige tentativa, erro e repetição.

### Como utilizar a IA sem prejudicar o aprendizado

Algumas atitudes ajudam a manter o equilíbrio:

1. Tentar resolver o exercício antes de pedir ajuda.
2. Pedir pistas antes de solicitar uma resposta completa.
3. Solicitar explicações adequadas ao nível iniciante.
4. Testar o código em um ambiente real.
5. Comparar a resposta com o material estudado.
6. Explicar a solução com as próprias palavras.
7. Refazer o exercício sem consultar a resposta.
8. Evitar copiar e colar códigos que não foram compreendidos.

### Conclusão do miniguia

A IA pode ajudar bastante no aprendizado de programação, principalmente quando explica conceitos, oferece feedback e orienta o estudante durante a resolução de problemas. Porém, de forma alguma ela substitui o "executar" do cérebro humano, o papel e a caneta, nem mesmo em uma área onde a demanda baseia-se em telas e teclados como esta.

Pelo contrário, quando não direcionada corretamente (com objetivo claro do utilizador) ela atrapalha, até mesmo prejudica o aprendizado quando  é utilizada como substituta ao esforço necessário para aprender.

O miniguia original gerado no NotebookLM está disponível em:

* [Miniguia gerado no NotebookLM](docs/miniguia-notebooklm.md)

## Glossário

| Termo                        | Explicação                                                                                                                                   |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **Inteligência artificial**  | Área que busca desenvolver sistemas capazes de executar tarefas associadas à inteligência humana.                                            |
| **IA generativa**            | Tipo de IA capaz de criar conteúdos, como textos, imagens e códigos, a partir de uma instrução.                                              |
| **LLM**                      | Sigla para *Large Language Model*. É um modelo treinado com grande quantidade de textos e capaz de responder perguntas em linguagem natural. |
| **Prompt**                   | Pergunta ou instrução enviada para a IA.                                                                                                     |
| **Engenharia de prompts**    | Processo de organizar e melhorar instruções para obter respostas mais adequadas.                                                             |
| **Lógica de programação**    | Forma de organizar etapas para resolver um problema por meio de um programa.                                                                 |
| **Pensamento computacional** | Capacidade de dividir um problema em partes menores e estruturar uma solução lógica.                                                         |
| **Depuração**                | Processo de encontrar e corrigir erros em um código.                                                                                         |
| **Feedback**                 | Retorno recebido sobre uma tentativa, um erro ou uma solução.                                                                                |
| **Alucinação**               | Resposta incorreta ou inventada apresentada pela IA de forma convincente.                                                                    |
| **Aprendizagem ativa**       | Forma de aprender participando do processo, testando ideias e refletindo sobre os resultados.                                                |
| **Dependência excessiva**    | Situação em que o estudante deixa de exercitar o próprio raciocínio e passa a depender constantemente da ferramenta.                         |
| **Integridade acadêmica**    | Compromisso com uma aprendizagem honesta, sem apresentar respostas copiadas como se fossem resultado do próprio raciocínio.                  |

## Prompts reutilizáveis

Os modelos abaixo podem ser adaptados de acordo com o assunto estudado.

### 1. Entender um conceito

> Explique o conceito de [tema] de forma simples, considerando que sou iniciante em programação. Apresente um exemplo pequeno e não use recursos avançados sem explicar.

### 2. Pedir uma explicação diferente

> Não entendi a explicação sobre [tema]. Explique novamente usando uma analogia do cotidiano e depois faça uma pergunta curta para verificar se compreendi.

### 3. Receber pistas sem obter a solução pronta

> Estou tentando resolver [problema]. Não escreva o código completo. Apresente apenas uma pista inicial para que eu tente avançar sozinho.

### 4. Revisar um erro

> Este é o meu código: [código]. Ele não está funcionando como eu esperava. Não apresente a correção completa. Indique o tipo de erro e explique qual trecho devo analisar primeiro.

### 5. Criar um exercício

> Crie um exercício simples para praticar [tema]. Não mostre a resposta antes da minha tentativa.

### 6. Praticar lógica

> Ajude-me a dividir este problema em etapas menores: [problema]. Não escreva o código. Quero primeiro compreender a lógica da solução.

### 7. Verificar se realmente aprendi

> Faça três perguntas curtas sobre [tema]. Depois, analise minhas respostas e diga quais pontos preciso revisar.

### 8. Evitar uma resposta avançada demais

> Explique como resolver [problema] utilizando somente conceitos básicos adequados para um iniciante. Evite recursão, bibliotecas ou estruturas avançadas que não sejam necessárias.

## Conclusão

Este projeto me ajudou a perceber que a qualidade da resposta de uma IA não depende apenas da ferramenta utilizada. A maneira de formular uma pergunta e definir o contexto também influencia o resultado.

Ao comparar duas configurações no NotebookLM, ficou mais claro que uma instrução genérica pode produzir respostas corretas, mas pouco direcionadas. Quando o foco foi colocado no estudante iniciante, a análise ficou mais adequada ao objetivo do projeto.

A principal conclusão é que a inteligência artificial pode ser uma boa tutora, desde que não assuma o lugar do estudante no processo de aprendizagem. Para aprender programação, ainda é necessário praticar, errar, testar e desenvolver autonomia.

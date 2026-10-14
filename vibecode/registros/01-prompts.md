# Prompts

Registro do que foi pedido à IA (Claude Code), na ordem. As frases entre aspas são as mensagens do aluno, como foram escritas.

## Enunciado da atividade

> Desenvolvam uma landing page, com tema livre, para treinar e explorar os benefícios do vibecode.
>
> O foco não é só o resultado final. Quero ver como você pensou, como se comunicou com a IA e como corrigiu o caminho quando algo não saiu como esperado. (...) quero na pasta do projeto todos os registros dos prompts, as pesquisas, decisões de design, referências visuais, paleta de cores, tudo o que direcionou a resolução final da página.

## 1. Pedido inicial

> "são essas, verifique o que tem e oque não tem e bora fazer ja, tirando o do figma"

A IA leu o enunciado e escolheu um tema sozinha: uma oficina de bicicletas de bairro, a **Biela**. O enunciado deixa o tema livre e o prompt não indicava preferência, então a escolha foi da IA, e não do aluno. Dá para trocar.

## 2. Primeira versão: complicada demais

A IA escreveu uma página cheia de recursos que ninguém pediu: uma "ficha de serviço" que calculava preço e prazo, animação, desenho de engrenagem no fundo, plano de assinatura e um formulário de agendamento que só fingia enviar.

Ao abrir a página no navegador, a IA achou dois defeitos nela:
- o texto "incluso na revisão completa" aparecia em todos os itens da ficha (erro no código JavaScript);
- o título, em peso muito pesado, deixava o "N" e o "M" parecendo letras coladas.

## 3. Correção do aluno

> "preciso que voce tire os vicios de ia e mantenha somente oque a professora pediu também, sendo simples e basico mas conforme oque ela pediu, faça."

**O que a IA fez:** refez a página como uma landing simples, só com HTML e CSS (sem JavaScript, sem animação e sem formulário). Ficou com topo, hero, serviços e preços, como funciona, um depoimento e contato. Também apagou dois arquivos de registro que o enunciado não pedia.

**O que o aluno aprendeu com isso:** a IA tende a entregar mais do que foi pedido. O prompt precisa dizer o que **não** fazer, além do que fazer. Um prompt melhor teria sido: "landing page simples, só HTML e CSS, sem JavaScript, sem animações e sem formulário".

## 4. Outras correções de rota da sessão

- A IA tentou misturar o Bootstrap com a "Fio & Prensa". O aluno corrigiu: "são atividades separada não?".
- O aluno interrompeu a gravação da primeira versão porque achou que a IA ia mexer numa página de outra atividade. A IA tinha criado um arquivo novo, mas não deixou isso claro.
- Antes do commit do Bootstrap, o aluno pediu para tirar a pasta `vibecode/` e devolver depois, para não misturar as duas atividades.
- Regra do aluno para a sessão toda: "não quero que voce faça nenhum comando git, deixa que eu mesmo faço os commits no meu nome". Foi cumprida.

## 5. Referências visuais com prints

A IA tinha escrito o arquivo de referências só com texto e links. O aluno questionou:

> "precisa tirar os prints do referencias pra que?"
> "é pra adicionar em png então?"
> "abre e tire prints e adicione no projeto então, na pasta do vibecode"

**O que a IA fez:** explicou que o enunciado pede "referências visuais" e que ninguém tinha olhado as imagens, abriu os links no navegador e salvou os prints em `registros/referencias/`, em PNG.

**O que não saiu como esperado:** o site do Bike Tailor foi bloqueado pela extensão do navegador na primeira tentativa. A IA tinha avisado que não conseguia abrir e passou o link para o aluno tirar o print. O aluno insistiu:

> "abra o site voce mesmo"

Na segunda tentativa o site abriu e o print foi salvo.

**Aprendizado:** quando a IA diz que não consegue, vale pedir para tentar de novo antes de fazer o trabalho à mão.

## 6. Linguagem do arquivo de referências

> "voce acha que precisa mudar o que aproveitei? deixe uma linguagem de universitario, basica e concisa"

A IA conferiu cada frase de "o que aproveitei" contra a página de verdade (por exemplo, a Biela usa só três cores e o topo tem só o nome) e reescreveu o arquivo com frases curtas.

**Aprendizado:** pedir o tom do texto (aqui, "universitário, básico e conciso") muda o resultado mais do que pedir só "reescreva".

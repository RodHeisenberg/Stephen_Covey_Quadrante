# Tempo de decidir

UC Programação de Aplicativos, Aula 04. Professor Rodrigo Moreira.
Tema: gestão do tempo em TI e os quadrantes de urgência e importância.

## Duas páginas independentes

- `index.html`: página inicial com conceitos, definições, exemplos, análise do caso de João e plano de ação. Sem falas do professor, sem formulários de atividade e sem cronômetro.
- `atividade.html`: atividade individual ou em grupo com duração sugerida de **40 minutos**, cronômetro, 16 questões com autocorreção e reflexão final.
- `.nojekyll`: arquivo auxiliar para a publicação estática.
- `README.md`: instruções de uso e publicação.

Os links “Conteúdo da aula” e “Atividade individual” abrem documentos HTML diferentes. As duas páginas devem permanecer na mesma pasta. A atividade também pode ser acessada diretamente pelo endereço que termina em `/atividade.html`.

Não é necessário instalar programas ou executar comandos. Extraia o ZIP e abra `index.html` para conferir o material. Depois de baixadas, as páginas funcionam sem internet e sem bibliotecas externas. A autocorreção requer JavaScript habilitado.

## Conteúdo da página inicial

1. Stephen Covey e a gestão do tempo em TI.
2. Definições de urgência e importância.
3. Os quatro quadrantes, com definição, exemplos e conduta.
4. Gestão de projetos, comunicação, liderança e eficiência pessoal.
5. Estudo de caso de João, com análise das situações e diagnóstico.
6. Plano de ação por quadrante e resultados esperados.

A página apresenta o conteúdo que pode ser projetado e explicado à turma. Os links da matriz levam às definições e os blocos recolhíveis apresentam esclarecimentos adicionais. O tempo de exposição fica a critério do professor e é independente dos 40 minutos da atividade.

## Atividade de 40 minutos

O novo caso trata de um aplicativo de agendamentos. A atividade pode ser resolvida individualmente ou em grupo. Para grupos, sugere-se 2 a 4 integrantes com alternância entre leitura, operação da página e justificativa das decisões.

- **4 minutos:** leitura do caso e entendimento do objetivo.
- **16 minutos:** classificação de oito tarefas nos quadrantes.
- **12 minutos:** quatro decisões e quatro ações para a sequência de trabalho.
- **8 minutos:** correção, revisão, nova tentativa, reflexão e download do resultado.

O cronômetro começa em 40:00 quando o participante clica em Iniciar. Ele pode ser pausado ou reiniciado. Chegar a zero não bloqueia respostas. O tempo restante é salvo quando o navegador permite; ao voltar à página, a contagem fica pausada e precisa ser retomada pelo botão Iniciar.

## Autocorreção e resultado

- As 16 respostas objetivas compõem um diagnóstico formativo de 0 a 16 pontos.
- É necessário responder todos os itens antes de corrigir. A primeira pendência recebe foco.
- Cada item recebe feedback com justificativa.
- O resultado mostra subtotais de classificação, decisões e agenda.
- “Refazer apenas os erros” reabre as respostas incorretas e mantém os acertos.
- Alterar uma resposta invalida o resultado anterior até a próxima correção.
- A reflexão final é texto livre, sem correção automática.
- “Baixar resultado” gera um relatório `.txt` com identificação opcional, respostas, justificativas, tentativa e reflexão.
- A impressão permite salvar em PDF pelo navegador.
- Não há envio automático ao professor, prazo institucional ou nota oficial definidos na página.

O relatório pode ser editado por quem o recebe e não comprova autoria. Se desejar recolher os resultados, combine o envio pelo canal da turma.

## Progresso e dados locais

Respostas, identificação, reflexão, tempo restante e tentativas ficam no `localStorage` do navegador, quando permitido. O progresso não é sincronizado entre dispositivos. Abrir arquivos locais pode ter restrições de armazenamento que variam entre navegadores.

Em computador compartilhado, use “Começar de novo” e confirme o segundo clique para limpar respostas, reflexão e tentativas. O campo de identificação permanece e pode ser apagado manualmente. Se o armazenamento não estiver disponível, a página avisa e continua funcionando na sessão.

Esta versão usa uma nova chave de armazenamento para que o progresso da versão anterior, que reunia tudo em uma única página, não interfira na nova atividade.

## Publicar no GitHub Pages

1. Extraia o ZIP no computador.
2. Entre no GitHub e crie ou abra o repositório que receberá a aula. Para Pages no plano gratuito, use um repositório público.
3. Abra `Add file` e depois `Upload files`.
4. Envie os arquivos extraídos para a raiz do repositório. Envie `index.html` e `atividade.html` juntos, na mesma pasta. Não envie apenas o ZIP nem coloque uma pasta adicional em volta dos arquivos.
5. Conclua o envio em `Commit changes`.
6. Abra `Settings` e selecione `Pages`.
7. Em `Build and deployment`, escolha `Deploy from a branch` em `Source`.
8. Em `Branch`, selecione a branch que recebeu os arquivos, normalmente `main`, e a pasta `/(root)`. Clique em `Save`.
9. Aguarde a conclusão. A seção Pages exibirá o endereço do site.
10. Compartilhe o endereço principal para o conteúdo ou acrescente `/atividade.html` ao endereço do repositório para a atividade.

Se já publicou a versão anterior, substitua `index.html`, adicione `atividade.html` e atualize `README.md` na mesma branch. A configuração de publicação pode continuar a mesma. Aguarde o novo processamento antes de atualizar a página no navegador.

Se aparecer erro 404, confira a branch, a pasta de publicação e os nomes dos arquivos. Os arquivos precisam terminar em `.html`, sem `.txt`. Consulte também a execução de publicação em `Actions`.

Referências oficiais usadas nas instruções de publicação:
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Gabarito para mediação

- Classificação: QI, QII, QIII, QIV, QI, QII, QIII, QII.
- Decisões: segunda, terceira, primeira, segunda alternativa.
- Agenda: segunda, primeira, terceira, segunda alternativa.

A classificação depende das condições informadas. Uma mudança de prazo ou impacto pode mudar o quadrante. O material preserva o valor das pausas, a resposta a incidentes reais e a necessidade de preparar a equipe antes de delegar.

## Editar os arquivos

Abra `index.html` para editar as definições e o caso de João. Abra `atividade.html` para editar a atividade.

As listas `classification`, `decisions` e `schedule` contêm as questões e os comentários. O campo `answer` começa em zero: 0 corresponde à primeira opção, 1 à segunda e assim por diante. Nos quadrantes: 0 = QI, 1 = QII, 2 = QIII e 3 = QIV. O campo `why` apresenta a explicação da correção.

O cronômetro usa 2400 segundos para 40 minutos. Se mudar a duração, revise também os rótulos e a distribuição do tempo. Ao mudar o gabarito ou a estrutura, altere a chave de armazenamento e a versão para não misturar respostas de edições diferentes.

## Conferência desta revisão

Conferidos no navegador: abertura de páginas diferentes pelos links de navegação, ausência de atividade e de falas do professor no conteúdo, cronômetro inicial de 40:00, validação de respostas incompletas e correção de 16/16. A autocorreção comentada, as novas tentativas, o relatório e o armazenamento local foram preservados.

## Origem do conteúdo

Baseado na apresentação da Aula 04 fornecida pelo professor. O caso de João vem dos slides. O caso do aplicativo de agendamentos e suas questões foram elaborados para a aplicação dos conceitos. O Quadrante IV recebeu explicação própria para completar a matriz.

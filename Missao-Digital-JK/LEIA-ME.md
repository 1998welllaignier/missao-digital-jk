# Missão Digital — O Mistério da Escola Conectada

Professor Welington Laignier · EMEF Juscelino Kubitschek · Curionópolis/PA

## Implantação

1. Extraia o ZIP, mantendo os arquivos na mesma pasta.
2. Abra index.html no Chrome ou Edge. O jogo local não depende de internet.
3. Para uso online, publique index.html, style.css, credits.css, data.js e game.js na mesma pasta de uma hospedagem estática.
4. No GitHub Pages: coloque esses arquivos na raiz do repositório; em Settings > Pages, escolha Deploy from a branch, branch main, pasta /(root), e salve. Aguarde a publicação e use o endereço informado pelo GitHub.
5. Abra o link nas estações. O Veyon serve para acompanhar/controlar as telas; não armazena os resultados.

## Roteiro da aula — 30 minutos

- Identificação: 2 min. O contador orienta a dupla; não inicia sem os dois nomes completos e turma.
- Missões 1 a 4: meta de 5 min cada.
- Missão 5: meta de 6 min.
- Encerramento e conversa: 2 min, dentro do período de 28 min disponível após a identificação.

O cronômetro de jogo começa em 28:00 após a identificação. Ao chegar a zero, registra o resultado parcial automaticamente. Não há espera obrigatória para avançar. Para reservar 2 min de conversa, o professor pode orientar a conclusão aos 26 min de jogo ou usar Encerrar e registrar progresso. Se a identificação ultrapassar 2 min, a duração total ultrapassará a meta de 30 min.

## Cooperação e avaliação

Duplas em uma única aba/computador. Cada missão alterna Jogador 1, Jogador 2 e decisão conjunta. Nos desafios conjuntos, ambos precisam confirmar o acordo. O sistema incentiva a participação, sem identificar fisicamente quem usou o mouse.

Cada missão vale 20 pontos (6 + 6 + 8), totalizando 100. Cada erro desconta 1 ponto do desafio; cada dica desconta 1 ponto. Há até 5 dicas, no máximo 1 por desafio. O valor de cada desafio nunca fica negativo. Após três erros, a explicação revela a solução para permitir aprender e avançar.

## Resultados e privacidade

Baixe o CSV ao terminar. Ele usa UTF-8 com BOM e separador ponto e vírgula, com 15 linhas de desafios e um cabeçalho. Os campos de resumo da equipe se repetem em cada linha: para calcular médias entre equipes, agrupe pelo campo sessao e conte cada sessão apenas uma vez.

O recolhimento dos CSVs é manual. Não há painel central, banco de dados, login de aluno ou envio automático de resultados. O certificado só aparece após resolver todos os desafios; pode ser impresso ou salvo em PDF pela opção do navegador.

O progresso é mantido em sessionStorage enquanto a mesma aba permanecer aberta; recarregar normalmente preserva a sessão quando o navegador permite armazenamento. Fechar a aba pode perder o progresso. Use Nova dupla após exportar. O jogo não coleta dados de outras abas e não faz solicitações de rede próprias.

## Plano pedagógico

Público: 6º ano; dois estudantes por computador.

Objetivos: distinguir hardware e software; reconhecer periféricos e funções; selecionar aplicativos; reconhecer sinais de golpe; organizar arquivos e interpretar sequências e pistas.

Conteúdos: entrada e saída, processador/RAM/SSD, sistema operacional, aplicativos, privacidade e segurança, extensões, pastas e sequências lógicas.

Metodologia: investigação cooperativa em cinco missões, alternância de responsabilidade e confirmação conjunta. O professor acompanha as telas e intervém para apoiar leitura e discussão.

Avaliação: observar participação de ambos, argumentos usados e correção após feedback; analisar pontos, erros e dicas por missão. A pontuação é um indicador de aprendizagem, sem ranking entre equipes.

Relação temática com os eixos de Computação: Pensamento Computacional (ordenação e resolução de enigmas), Mundo Digital (componentes, programas e arquivos) e Cultura Digital (verificação de mensagens e proteção de dados). Não foram atribuídos códigos específicos de habilidades curriculares.

Recursos: computadores com Chrome/Edge, mouse e teclado; rede/internet somente para acesso hospedado. Veyon é opcional.

## Verificação

Testes automatizados de lógica passaram: 15 soluções corretas, máximo de 100 pontos, descontos, limite inferior zero, explicação após três erros, CSV com 16 linhas, proteção de texto em HTML/CSV, cronômetro de 28 minutos, aviso, encerramento incompleto, persistência e certificado condicional. Esses testes usam DOM simulado e não substituem testes de todas as interações no navegador. O funcionamento no Veyon e o percurso completo no Edge ainda precisam de validação no laboratório.

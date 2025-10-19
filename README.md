# Sistema de Gestão - Olimpíadas

Este repositório contém a documentação e modelagens para um sistema de gestão das Olimpíadas. O sistema deve gerenciar competições, inscrições de atletas, alocação de locais e controle de resultados, além de gerar relatórios de medalhas por país.

## Descrição do sistema

Com a chegada das Olimpíadas, um novo sistema de gestão é necessário para coordenar os diferentes aspectos do evento. Este sistema permite o cadastro de competições, inscrição de atletas, alocação de locais para as provas e controle de resultados, com geração de relatórios de medalhas por país.

## Regras de Negócio

1. Cadastro de competições:
   - O sistema deve permitir o cadastro de competições, que incluem o nome da modalidade, data, horário, local e lista de atletas inscritos.
2. Inscrição de atletas:
   - Atletas de diferentes países devem se inscrever em competições específicas. Cada atleta pode participar de várias competições, mas só pode representar um país em cada modalidade.
3. Alocação de locais:
   - Os locais para as competições devem ser alocados de forma a evitar conflitos de horário. Um local só pode abrigar uma competição por vez.
4. Controle de resultados:
   - Após a realização das competições, os resultados devem ser registrados, determinando o atleta vencedor e os classificados em segundo e terceiro lugares.
5. Relatórios de medalhas:
   - O sistema deve gerar relatórios de medalhas, mostrando o desempenho de cada país com base nas medalhas de ouro, prata e bronze conquistadas.

## Histórias de Usuário

- US01 - Cadastro de competições
  - Como organizador, quero cadastrar competições com modalidade, data, horário e local para que as provas sejam programadas.
  - Critérios de aceite: formulário de cadastro, validação de data/hora, lista de atletas (inicialmente vazia).

- US02 - Inscrição de atletas
  - Como atleta, quero me inscrever em competições específicas representando meu país para participar das provas.
  - Critérios de aceite: registro do atleta (nome, país), inscrição em uma ou mais competições, restrição de representar apenas um país por modalidade.

- US03 - Alocação de locais
  - Como coordenador de locais, quero alocar locais para competições evitando conflitos de horário para que não haja sobreposição de eventos no mesmo local.
  - Critérios de aceite: verificação de disponibilidade do local, bloqueio de horários conflitantes.

- US04 - Registro de resultados
  - Como árbitro, quero registrar os resultados das competições para definir vencedor, segundo e terceiro colocados.
  - Critérios de aceite: entrada de resultados, marcação dos três primeiros colocados, atualização do ranking e do relatório de medalhas.

- US05 - Relatório de medalhas
  - Como visitante ou organização, quero visualizar um relatório de medalhas por país para acompanhar o desempenho por nação.
  - Critérios de aceite: contagem de ouro/prata/bronze por país e ordenação por número de ouros, depois pratas e bronzes.

## Imagens e Modelagens

As imagens e arquivos de modelagem devem estar no repositório conforme a estrutura abaixo. 

- imagens/
  - diagrama-de-caso-de-uso.png  
  - diagrama-de-classes.png     
  - diagrama-de-pacotes.png     
  - diagrama-de-componentes.png 
  - diagrama-de-implantacao.png 

- modelagens/
  - diagrama-de-caso-de-uso.drawio 
  - diagrama-de-classes.drawio    
  - diagrama-de-pacotes.drawio    
  - diagrama-de-componentes.drawio
  - diagrama-de-implantacao.drawio

## Conteúdo do repositório

Lista dos arquivos presentes nesta cópia do repositório (local):

- README.md
- imagens/diagrama-de-caso-de-uso.png
- modelagens/diagrama-de-caso-de-uso.drawio

Caminho dos arquivos

- imagens/diagrama-de-classes.png
- imagens/diagrama-de-pacotes.png
- imagens/diagrama-de-componentes.png
- imagens/diagrama-de-implantacao.png
- modelagens/diagrama-de-classes.drawio
- modelagens/diagrama-de-pacotes.drawio
- modelagens/diagrama-de-componentes.drawio
- modelagens/diagrama-de-implantacao.drawio


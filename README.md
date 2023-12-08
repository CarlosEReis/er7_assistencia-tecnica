
<p align="center">
    <a href="https://www.java.com/pt-BR/" target="_blank"><img title="Java" src="https://github.com/CarlosEReis/er7_assistencia-tecnica/assets/12797559/41c08893-7af3-4de9-ac88-9f4d572a2869" alt="java" width="120" height="120"/>
</p>



<div align="center">
  
# Sistema para Gerenciamento de Chamados Técnicos
</div>

Olá, este é um projeto pessoal que estou desenvolvendo para o meu portifólio. Trata-se de um sistema para o gerenciamento de chamados técnicos.

<p align="center">
    <a href="https://www.java.com/pt-BR/" target="_blank"><img title="Java" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://maven.apache.org/" target="_blank"><img title="Maven" src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_maven_icon_130397.png" alt="Maven" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://spring.io/" target="_blank"><img title="Spring" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="spring" width="40" height="40"/></a>&nbsp &nbsp
    <a href="http://jwt.io" target="_blank"><img title="JWT" src="http://jwt.io/img/icon.svg" alt="JWT" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://community.jaspersoft.com/" target="_blank"><img title="Jaspersoft Studio" src="https://images.sftcdn.net/images/t_app-icon-s/p/e6d790bb-aa65-4fab-aa1e-346af12710a0/1081729734/jaspersoft-studio-imgingest-4237344852768170016.png" alt="Jaspersoft Studio" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://www.mysql.com/" target="_blank"><img title="MySQL" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="mysql" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://angular.io/" target="_blank"><img title="Angular" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" alt="angular" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://www.typescriptlang.org/" target="_blank"><img title="Typescript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://po-ui.io/" target="_blank"><img title="PO-UI" src="https://po-ui.io/assets/po-logos/po_color_bg.svg" alt="PO-UI" width="40" height="40"/></a>&nbsp &nbsp
</p>




  ## Tecnologias
  
- **Backend**:

  Java | Spring Boot | Spring Data JPA | Spring Security | JWT | MySQL | FlyWay | Jasper Report

- **Frontend**:

  Angular | PO-UI | Typescript | HTML 5 | CSS 3



🤚 🎥 **Clique** na imagem abaixo para assistir o vídeo, e ver maiores detalhes: 📽 🎞

[![Watch the video](https://github.com/CarlosEReis/er7_assistencia-tecnica/assets/12797559/860baba2-c4a0-45be-84fe-5ed2da72ab3a)](https://www.youtube.com/embed/4UlR75WgHHM)


## Motivação

Este projeto foi concebido dado a motivação de substituir o controle e a gestão de chamados técnicos realizados por meio de planilhas de Excel. A razão para isso é que o processo feito através de planilhas, é excessivamente manual e não garante a integridade das informações, pois qualquer pessoa pode alterá-las ou inserir de forma equivocada. Além disso, a gestão do processo é dificultada pela falta de KPIs que possam indicar problemas e permitir que o gestor tome medidas para melhorar o processo e o SLA para o cliente

## Objetivo

O objetivo deste projeto é desenvolver um sistema automatizado para o controle e a gestão de chamados técnicos e com controle de acesso para administrador, gestor e analista técnico. Este sistema irá substituir o atual método baseado em planilhas de Excel, que é manual e sujeito a erros. O novo sistema deve garantir a integridade das informações, pois evitará alterações não autorizadas e reduzirá a possibilidade do input de informações equivocadas. Além disso, ele incluirá a implementação de KPIs para monitorar o processo e identificar gargalos. Isso permitirá que o gestor tome medidas corretivas e melhore tanto o processo quanto o SLA para o cliente.

## Funcionalidades

O sistema possui as seguintes funcionalidades:

- 📊 **Dashboard** com as seguinte informações
    - 📈Chamados Abertos, Chamados Processados, “Chamados Finalizados e Qtde de 📉equipamentos avaliados
    - 📉Total de chamados abertos e fechado por mês
    - 📈Top 4 produtos que mais são enviados para reparo
    - 📉Top 3 clientes que mais abrem chamados
    - 📈Top 3 técnicos que mais finalizam chamados
    - 📉Total de chamado aberto e fechado por dia
- **Cadastro de Usuários**: Permite criar, editar, ativar e inativar usuários, com diferentes tipos e permissões de acesso.
- **Cadastro de Produtos**: Permite criar, editar, ativar e inativar produtos.
- **Cadastro de Clientes**: Permite criar, editar, ativar e inativar clientes.
- **Cadastro de Chamados Técnicos**: Permite criar, editar, cancelar e excluir chamados técnicos.
- **Envio de e-mail**: Envio de e-mail através de eventos ao criar, iniciar avaliação e finalizar o chamado (alteração de status).
- **Gera PDF do chamado**: Gera um laudo do chamado, na abertura do mesmo e ao finalizar o chamado, adicionando a posição técnica de cada item.

## Tipos de Usuários

O sistema possui os seguintes tipos de usuários, com diferentes níveis de acesso e funcionalidades:

- 👨‍💻 **Administrador**: Acesso total a todas as funcionalidades do sistema, podendo gerenciar todos os cadastros, chamados, relatórios e dashboards.
- 👩‍💼 **Gestor**: Acesso aos cadastros, edições, ativação e inativação de usuários, produtos, clientes e chamados, podendo visualizar o dashboard no contexto geral e os indicadores de desempenho (KPIs).
- 🧑‍🔧 **Analista Técnico**: Acesso somente à visualização dos clientes e produtos, podendo interagir nos chamados técnicos (validar e concluir), e visualizar o dashboard contextualizado no seu usuário.

## Diagrama de Classes:

![diagrama-classe](https://github.com/CarlosEReis/er7_assistencia-tecnica/assets/12797559/83865b20-20e3-40f3-9647-8fa7d3cf6fc2)

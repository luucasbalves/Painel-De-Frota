-Painel de Gestão de Frota (Realtime)

  Sistema completo para gerenciamento de frota em tempo real, com controle de motoristas, obras e operações logísticas.

-Sobre o projeto

  Este sistema foi desenvolvido com o objetivo de facilitar a organização e o acompanhamento de uma frota de caminhões em operações diárias.

  A aplicação permite visualizar, organizar e atualizar informações em tempo real, garantindo mais controle e agilidade na tomada de decisão.

1- Demonstração

 Acesse o sistema online:
👉 https://luucasbalves.github.io/Painel-De-Frota/
   senha de acesso ao modo admin = AdminBal

-Problema que resolve

  Normalmente empresas que trabalham com logística e obras frequentemente enfrentam dificuldades como:

  Falta de visibilidade da frota
	Comunicação descentralizada
	Dificuldade em acompanhar alocações em tempo real
	Controle manual e sujeito a erros

Este sistema resolve esses problemas com um painel centralizado, visual e interativo.

- Tecnologias utilizadas
	HTML5
	CSS3
	JavaScript (Vanilla)
	Firebase Realtime Database
	Service Workers (PWA básico)

- Funcionalidades
 	Gestão de Motoristas
	Cadastro, edição e exclusão
	Controle de status (ativo, oficina, ausente)
	Associação com obras
	Gestão de Obras
	Criação e edição de obras
	Organização por tipo (interna, entrega)
	Vinculação entre obras

- Dashboard em tempo real
	Total de frota
	Motoristas em operação
	Em manutenção
	Ausentes
	Disponíveis

- Atualização em tempo real
	Sincronização automática via Firebase
	Alterações refletidas instantaneamente para todos os usuários

- Drag and Drop
	Movimentação de motoristas entre obras
	Interface intuitiva e rápida

- Agenda (Munk)
	Planejamento mensal de atividades

- Mapa de Obras
	Integração com links do Google Maps

- Integração com WhatsApp
	Envio rápido de mensagens para motoristas

- Histórico de movimentações
	Registro completo de mudanças
	Filtros por data, motorista e obra

- Controle de acesso
	Modo administrador
	Modo visitante (somente visualização)

- Responsividade
	Adaptado para desktop e mobile
	Interface otimizada para uso em campo

- Estrutura do projeto
	/project
  	├── index.html
  	├── manifest.json
  	├── sw.js

- Melhorias futuras
	Implementação de autenticação segura (Firebase Auth)
	Modularização do código (separação em arquivos JS)
	Backend mais robusto
	Sistema de permissões por usuário

-‍ Autor

  Desenvolvido por Lucas Barbosa Alves

- Licença

	Este projeto é de uso privado e educacional.

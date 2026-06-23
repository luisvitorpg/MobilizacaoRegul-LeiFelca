# Gerador de E-mails para Mobilização Cidadã

## Sobre

Esta aplicação web estática foi desenvolvida para facilitar a geração de e-mails relacionados à campanha de mobilização sobre a **Sugestão Legislativa 18/2026**.

O objetivo da ferramenta é reduzir o trabalho manual de preencher informações e formatar mensagens, permitindo que cada participante revise o conteúdo e utilize seu próprio cliente de e-mail para realizar o envio.

A aplicação **não envia e-mails automaticamente**. Ela apenas gera um rascunho personalizado e abre o cliente de e-mail do usuário por meio do protocolo `mailto:`.

Todo o processamento ocorre localmente no navegador.

## Contexto da campanha

Esta ferramenta foi criada para apoiar uma campanha de mobilização que incentiva cidadãos a entrarem em contato com membros da Comissão de Direitos Humanos do Senado a respeito da **Sugestão Legislativa 18/2026**, relacionada à **Lei nº 15.211/2025 (conhecida como "Lei Felca" ou "ECA Digital")**.

Segundo os organizadores da campanha, a sugestão representa uma oportunidade para discutir possíveis alterações na legislação antes de sua plena implementação. Entre os pontos destacados pela campanha estão preocupações sobre exigências de verificação de identidade para acesso a determinados serviços na internet, impactos para plataformas digitais, privacidade dos usuários, custos de conformidade e possíveis efeitos sobre o acesso à internet no Brasil.

O site disponibiliza espaço para apresentar os materiais informativos da campanha (como textos, links e publicações fornecidas pelos organizadores) para que cada participante possa conhecer o contexto antes de decidir se deseja enviar o e-mail.

## Recursos

* Geração automática do e-mail.
* Personalização com nome, cidade, estado e e-mail do usuário.
* Pré-visualização antes do envio.
* Abertura do cliente de e-mail utilizando `mailto:`.
* Compatível com computadores e dispositivos móveis.
* Interface responsiva e acessível.

## Privacidade

Este projeto prioriza a privacidade dos usuários.

* Não coleta dados pessoais.
* Não utiliza banco de dados.
* Não utiliza cookies.
* Não utiliza Local Storage.
* Não utiliza Session Storage.
* Não utiliza IndexedDB.
* Não utiliza serviços de analytics.
* Não utiliza rastreadores.
* Não envia informações para servidores.

Todas as informações inseridas pelo usuário permanecem apenas durante a utilização da página.

## Estrutura

* `index.html` — Estrutura da aplicação.
* `styles.css` — Estilos da interface.
* `script.js` — Lógica da aplicação.

## Personalização

O projeto foi desenvolvido para facilitar futuras alterações.

É possível modificar facilmente:

* Texto-base do e-mail.
* Assuntos.
* Saudações.
* Encerramentos.
* Lista de destinatários em CCO/BCC.
* Conteúdo da seção "Entenda a campanha".

## Hospedagem

O projeto pode ser publicado como um site estático em:

* GitHub Pages
* Cloudflare Pages
* Netlify
* Vercel

Não é necessário backend.


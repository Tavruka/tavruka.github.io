# Diretivas do website Tavruka

## Estrutura
- O site usa páginas separadas: início, jogo, gameplay, sobre/contacto e privacidade. A limitação antiga de uma única página era do Canva e já não se aplica.
- Manter navegação consistente e adaptação a computador e telemóvel.

## Google AdSense
- Preservar o snippet aprovado pelo utilizador em todas as páginas públicas do website, dentro de `<head>`, uma única vez por página:

```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4143591580968042"
     crossorigin="anonymous"></script>
```

- Não substituir o identificador de editor nem remover o snippet durante alterações de design, criação de páginas ou migrações, salvo instrução explícita do utilizador.
- Antes de publicar, verificar que cada página contém exatamente uma ocorrência do script e o identificador correto.
- Este identificador é de editor; os endereços dos sites são configurados separadamente na conta AdSense. A presença do script não confirma aprovação ou anúncios ativos.

## Publicação
- Repositório: https://github.com/Tavruka/tavruka.github.io
- Website: https://tavruka.github.io/
- Manter a cópia de entrega em D:/codex/emberTribeGooglePlay/04_Website sincronizada com alterações publicadas.
- Ao alterar estilos, atualizar a versão no endereço do CSS para evitar misturar HTML novo com estilos antigos em cache.
- Por instrução do utilizador, a publicação principal pertence agora à conta Tavruka e ao repositório tavruka.github.io. Usar https://tavruka.github.io/; a conta pessoal SergioMatos20 deixa de ser o destino principal.

- Configurar o site tavruka.github.io na conta AdSense; o registo anterior sergiomatos20.github.io não verifica este domínio.

## Contacto oficial
- Usar tavrukaapp@gmail.com em contactos, links mailto e política de privacidade do website. Não voltar a introduzir endereços pessoais anteriores.

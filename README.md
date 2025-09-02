📌 Versionamento Semântico

O versionamento semântico (também conhecido como SemVer) é uma forma de dar sentido aos números de versão do software.
Em vez de escolher números aleatórios, seguimos uma lógica que facilita para desenvolvedores, usuários e até para ferramentas automáticas entenderem o que mudou em cada atualização.

A estrutura segue o formato:

MAJOR.MINOR.PATCH


MAJOR → Mudanças grandes, que quebram compatibilidade.
Exemplo: um sistema que tinha um comando e agora funciona de outro jeito.

MINOR → Novas funcionalidades, mas que continuam compatíveis com as versões anteriores.
Exemplo: adicionamos uma nova opção, mas nada do que existia deixou de funcionar.

PATCH → Correções pequenas, sem alterar comportamento esperado.
Exemplo: arrumar um bug ou melhorar a performance.

🚀 Aplicação no projeto

No contexto deste projeto, seguimos o SemVer para dar clareza:

A primeira versão estável foi marcada como v1.0.0.

Caso sejam adicionadas novas funcionalidades sem quebrar o que já existe, lançaremos v1.1.0, v1.2.0, e assim por diante.

Se for apenas um ajuste ou correção de bug, teremos v1.0.1, v1.0.2, etc.

E quando houver mudanças muito grandes, que alterem a forma de uso, passaremos para v2.0.0.

Isso ajuda qualquer pessoa que usar o repositório a entender rapidamente o impacto da atualização só de olhar o número da versão.
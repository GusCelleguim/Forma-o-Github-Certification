### Conhecendo a Administração do GitHub


### O que é a Administração do GitHub?

Os administradores do GitHub têm a missão crucial de proteger os projetos e garantir que as equipes certas possam colaborar de forma eficiente. Atualmente, o GitHub possui três níveis de administração: equipe, organização e empresarial.

---

### Administração em Nível de Equipe

No GitHub, os usuários fazem parte de equipes dentro das organizações. Essas equipes ajudam a organizar permissões e facilitar a comunicação. Conectar suas equipes ao Microsoft Entra ID, por exemplo, pode automatizar atualizações e simplificar a administração.

Os membros de equipe com certas permissões podem:
- Criar, renomear ou excluir equipes.
- Adicionar ou remover membros.
- Gerenciar colaboradores externos.
- Ajustar configurações de visibilidade da equipe, discussões e atribuição de revisões de código.

Essas funcionalidades tornam o processo administrativo mais eficiente, simplificando tarefas como a adição de novos membros e o controle de permissões.

---

### Administração em Nível de Organização

Organizações no GitHub são espaços compartilhados para colaboração em projetos. Proprietários e administradores têm o controle sobre o acesso, podendo:
- Convidar membros.
- Organizar equipes.
- Definir permissões.

Ter uma única organização é recomendado para evitar complexidade e riscos. Proprietários podem usar scripts para automatizar tarefas administrativas, garantindo segurança e eficiência.

---

### Administração em Nível Empresarial

Contas Enterprise no GitHub centralizam o gerenciamento de várias organizações. Os proprietários podem:
- Ativar login único (SAML).
- Adicionar ou remover organizações.
- Controlar cobranças.
- Configurar políticas de segurança.
- Automatizar tarefas administrativas com scripts.

---

### Melhores Práticas

Para otimizar a administração:
- Crie equipes hierárquicas que representem a estrutura da sua empresa.
- Forme equipes com base em interesses ou tecnologias específicas.
- Conecte suas equipes a provedores de identidade para automatizar atualizações e simplificar tarefas administrativas, reduzindo a necessidade de atualizações manuais.

---

### Permissões do GitHub

As permissões são divididas em quatro níveis: repositório, equipe, organização e empresa.

#### Permissões de Repositório
Cinco tipos principais:
1. **Leitura**: Visualizar ou discutir o projeto.
2. **Triagem**: Gerenciar problemas e solicitações.
3. **Gravação**: Contribuir ativamente no projeto.
4. **Manutenção**: Gerenciar o repositório sem acesso a ações críticas.
5. **Administrador**: Acesso total, incluindo ações críticas.

#### Permissões de Equipe
Dois níveis:
1. **Membro**: Herda permissões da equipe pai.
2. **Mantenedor**: Pode alterar nome, adicionar membros e gerenciar revisões de código.

#### Permissões da Organização
1. **Proprietário**: Controle total, incluindo a adição/removal de usuários.
2. **Membro**: Cria e gerencia repositórios e equipes.
3. **Moderador**: Gerencia interações e comentários em repositórios públicos.
4. **Gerente de Cobrança**: Visualiza e edita informações de cobrança.
5. **Gerente de Segurança**: Gerencia alertas e configurações de segurança.
6. **Colaborador Externo**: Acesso a repositórios específicos.

#### Permissões da Empresa
1. **Proprietário Corporativo**: Controle total, gerencia administrações e políticas.
2. **Membro Corporativo**: Funções similares aos membros da organização.
3. **Gerente de Cobrança Corporativo**: Gerencia informações de cobrança.

---

### Segurança e Gerenciamento de Repositórios

#### Regras de Proteção de Branch
- Controle de alterações no repositório.
- Exija aprovações, pull requests, commits assinados e mais.
- Defina regras para todos, inclusive administradores.
- Restrinja quem pode fazer push para branches.

#### Arquivo CODEOWNERS
- Atribua membros ou equipes como proprietários de código.
- Solicite automaticamente revisões de código.

#### Visualizar Tráfego com Insights
- Veja clones completos, visitantes recentes, referências de sites e conteúdo popular.

Para acessar o grafo de tráfego:
- No GitHub.com, vá para a página principal do repositório.
- Selecione Insights e depois Tráfego.

---

Dominar a administração do GitHub é essencial para garantir segurança e eficiência na colaboração de projetos. Com essas práticas, você estará preparado para gerenciar qualquer organização no GitHub.
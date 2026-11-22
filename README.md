# Meu Treino — como publicar e instalar

App de treino (musculação, calistenia e HIIT) que funciona offline e se instala no celular como um app. Não precisa de conta, não tem custo e cada pessoa tem os próprios dados, salvos só no aparelho dela.

## 1. Publicar grátis no GitHub Pages (uma vez só, ~10 minutos)

Faça isto pelo computador (pelo celular também dá, mas é mais trabalhoso).

1. Crie uma conta gratuita em **github.com**.
2. Clique em **New repository** (botão verde "New").
   - Nome: `meu-treino`
   - Marque **Public**
   - Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**.
4. Descompacte o arquivo `meu-treino.zip` e **arraste todos os arquivos** da pasta (não a pasta em si):
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png`
5. Clique em **Commit changes**.
6. Vá em **Settings → Pages**.
   - Em *Source*, escolha **Deploy from a branch**.
   - Branch: **main**, pasta **/ (root)** → **Save**.
7. Espere 1–2 minutos e recarregue a página. Vai aparecer o endereço do app, algo como:
   `https://SEU-USUARIO.github.io/meu-treino/`

Esse é o link para mandar para sua esposa (ou para quem você quiser).

## 2. Instalar no celular

**iPhone:** abra o link no **Safari** → botão **Compartilhar** → **Adicionar à Tela de Início**.

**Android:** abra o link no **Chrome** → menu **⋮** → **Instalar app** (ou **Adicionar à tela inicial**).

Depois de abrir uma vez com internet, o app funciona **offline** (inclusive na academia sem sinal).

## 3. Backup (importante)

Os dados ficam guardados no próprio celular. Se trocar de aparelho, desinstalar o app ou limpar os dados do navegador, eles somem.

- Em **Perfil → Seus dados e backup**, toque em **Exportar backup** (salva um arquivo) ou **Copiar backup** (copia o texto para colar num e-mail ou nota).
- No celular novo, use **Importar arquivo** ou **Importar colando o texto**.

Faça um backup a cada 2–4 semanas.

## 4. Atualizar o app no futuro

Se eu (ou você) alterar o `index.html`, basta subir o arquivo novo no mesmo repositório (**Add file → Upload files**). O app pega a versão nova na próxima vez que for aberto com internet, e os dados de quem já usa são mantidos.

## O que o app faz

- **Treino:** treino do dia com séries, carga e repetições, botão de vídeo para cada exercício, dicas de execução, sugestão de quando aumentar a carga e cronômetro de descanso.
- **Circuito HIIT:** cronômetro em tela cheia com trabalho e descanso, rodadas e bipes.
- **Rotinas:** crie, edite, duplique e reordene treinos, escolha os dias da semana e use modelos prontos (academia 3x, 4x, 5x e casa/calistenia).
- **Exercícios:** cerca de 60 exercícios já cadastrados. Dá para criar os seus, com seu próprio link de vídeo.
- **Progresso:** peso corporal com gráfico e histórico de treinos.
- **Perfil:** metas de calorias e macros calculadas automaticamente, ou as suas próprias (por exemplo, as do nutricionista).

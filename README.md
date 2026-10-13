# App Rotina V1
Aplicativo PWA estático para Android. Dados guardados em localStorage, com backup JSON e cache offline via Service Worker.

## Publicação
1. Crie um repositório vazio no GitHub.
2. Envie **todos os arquivos da pasta** para a raiz do repositório.
3. Na Vercel, importe o repositório, escolha **Other** como framework e mantenha o diretório raiz (`./`). Não é necessário comando de build.
4. Publique e abra a URL HTTPS no Chrome do Android.
5. Use o menu do Chrome > Adicionar à tela inicial / Instalar aplicativo (quando disponível).
6. Acesse uma vez online para instalar o cache offline.

## Limitações conhecidas
- O modo híbrido distingue tarefas essenciais e flexíveis, permite adiar as flexíveis em 15 minutos, mas não replaneja automaticamente o restante do dia.
- O expediente salvo em Configurações não atualiza automaticamente as atividades do dia.
- Sem notificações push ou alertas em segundo plano.
- Dados não sincronizam entre dispositivos; use exportação/importação JSON.
- Dados locais podem ser apagados ao limpar armazenamento do navegador.
- Não há cálculo clínico de qualidade do sono.

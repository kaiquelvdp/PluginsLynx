# LynxShop

LynxShop é um plugin de loja virtual completo para servidores Minecraft Spigot/Paper 1.20.x–1.21.x, com suporte multi-economia, interface gráfica amigável, sistema de permissões robusto, backups e muito mais.

## ⚡ Principais Recursos

- Loja virtual com GUI customizável
- Multi-economia (Vault, PlayerPoints, TokenManager, etc)
- Suporte a múltiplas moedas e seleção na compra
- Gerenciamento completo por comandos ou GUI
- Backup, reload, logs e estatísticas
- Sistema de ajuda integrado e documentação

## 🧩 Requisitos

- **Java 17+**
- **Spigot/Paper 1.20.x ou 1.21.x**
- **Vault** (obrigatório para economia padrão)
- Plugins de economia adicionais (opcional): PlayerPoints, TokenManager, etc.

## 🚀 Instalação

1. Coloque o arquivo `LynxShop.jar` na pasta `plugins` do seu servidor.
2. Reinicie ou recarregue o servidor.
3. Todos os arquivos de configuração serão gerados automaticamente.
4. Edite as configs conforme necessário e use `/lynx reload`.

## ⚙️ Configuração Inicial

- Edite `config.yml` para ajustar prefixos, economias, sons e opções gerais.
- Configure categorias em `categorias.yml`.
- Cadastre itens, preços, estoques e permissões em `itens.yml`.
- Ajuste nomes e formatos das economias em `economias.yml`.
- Personalize as mensagens em `mensagens.yml`.

## 🛒 Criando Sua Primeira Loja

1. Use `/lynx criar` para abrir a GUI administrativa.
2. Crie categorias e adicione itens facilmente pelo menu.
3. Defina preços, descrições e permissões conforme desejar.

## 💰 Configurando Economias

- O plugin detecta automaticamente economias instaladas.
- Configure prioridades e nomes em `economias.yml`.
- Use `/lynx economia listar` para ver as disponíveis.

## 📝 Sistema de Permissões

Veja todas as permissões em [plugin.yml](src/main/resources/plugin.yml) e no comando `/lynx ajuda permissoes`.

## 📚 Comandos

- `/loja` - Abre a loja para jogadores
- `/loja ajuda` - Ajuda do jogador
- `/lynx` - Comandos administrativos
- `/lynx ajuda` - Ajuda administrativa
- `/lynx reload` - Recarrega configs
- `/lynx salvar` - Salva configs
- E muitos outros!

## 🔒 Resolução de Problemas

- Verifique se o Vault está instalado e configurado.
- Veja o log do console para erros detalhados.
- Use `/lynx reload` após alterar arquivos .yml.
- Se persistir, apague as configs e reinicie para regenerar.

## 🛠️ API para Desenvolvedores

Em breve...

## ❓ FAQ

- **Funciona em 1.21.x?** Sim, compatibilidade total!
- **Suporta quantos tipos de moeda?** Quantos quiser, basta configurar.
- **Posso traduzir as mensagens?** Sim, totalmente personalizável.

## 📄 Licença

MIT License

---

**Dúvidas ou sugestões? [Abra uma issue!](https://github.com/kaiquelvdp/PluginsLynx/issues)
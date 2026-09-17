# capivaraos/repo

Repositório oficial de atualizações do **CapivaraOS** (linha desktop / comunidade),
servido em **https://repo.capivaraos.org** via GitHub Pages.

- Conteúdo: a árvore estática do repositório dnf (`marsh/f<rel>/<arch>/{stable,testing}/…`),
  os `.rpm` assinados, o `repodata/` (com `repomd.xml.asc`) e a chave pública.
- **A integridade vem da assinatura GPG** (chave privada offline), não do host — por isso
  qualquer host estático serve e o domínio é repointável sem tocar nos pacotes.
- Publicação: `publish-repo.sh` / `build-updates.sh` do repo `capivaraos-marsh-next` (FEAT-111/114).

> Em preparação para a versão 2.0. Ainda sem pacotes publicados.

# otakinhosads

Repositório pessoal de extensões corrigidas para Mihon e forks compatíveis.

Este repositório existe porque algumas extensões do [Project Nox](https://github.com/Awerkori/fonte-extensoes) (fork de [keiyoushi/extensions-source](https://github.com/keiyoushi/extensions-source)) estavam travando ao abrir a tela de configurações. Aqui ficam só as versões corrigidas, assinadas com uma chave própria.

---

## Links

- **Repositório para Mihon (`index.min.json`):**
  https://raw.githubusercontent.com/matheusjose04/otakinhosads/main/index.min.json

- **Código-fonte das correções (fork privado):**
  https://github.com/matheusjose04/fonte-extensoes

> Para adicionar ao Mihon ou forks compatíveis, copie o link do `index.min.json` acima e adicione-o como repositório de extensões (Explorar → Extensões → Repositórios).

---

## Extensões neste repositório

| Extensão | Versão | O que foi corrigido |
|---|---|---|
| Blackout Comics | 1.6.13 | Tela de configurações travava com `NullPointerException` (`defaultValue` nulo) ao tentar abrir "Limpar sessão". |
| Argos Comics | 1.6.59 | Mesmo crash de `defaultValue` nulo nos botões de login/status/logout, e a tela ficava em branco (título/resumo só eram preenchidos depois de adicionados à tela). |

Ambas continuam com login próprio (Blackout Comics por e-mail/senha, Argos Comics por WebView) — só a tela de configurações estava quebrada.

---

## Sobre

Este não é um repositório de extensões novas — é só um espelho de correções pontuais sobre o trabalho do [Project Nox](https://github.com/Awerkori/fonte-extensoes) e do [Keiyoushi](https://github.com/keiyoushi/extensions-source).

Toda vez que uma correção é feita no código-fonte, uma Action publica automaticamente uma nova versão aqui — os arquivos `.apk`/`.jar` ficam nas [Releases](https://github.com/matheusjose04/otakinhosads/releases) deste repositório, não soltos na árvore de arquivos.

---

## Créditos

### Keiyoushi

Base técnica e a maioria das fontes originais vêm de:
https://github.com/keiyoushi/extensions-source

### Project Nox (Awerkori)

As versões com login próprio do Blackout Comics e do Argos Comics, que aqui foram apenas corrigidas, vêm de:
https://github.com/Awerkori/fonte-extensoes

---

## Aviso

Sem afiliação com os sites suportados pelas extensões, nem com Mihon, Tachiyomi, Keiyoushi ou Project Nox.

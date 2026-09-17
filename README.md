# Site público do Minha Pauta

As páginas que a Google Play exige do aplicativo **Minha Pauta**
(`com.audiencista.app`), publicadas em <https://minhapauta.online>.

| Página | Para que serve |
| --- | --- |
| `index.html` | Página inicial do app |
| `privacidade.html` | Política de Privacidade — obrigatória na ficha da Play |
| `termos.html` | Termos de Uso |
| `excluir-conta.html` | Pedido de exclusão de conta — a Play exige esta URL para quem já desinstalou o app |

São páginas estáticas: HTML e CSS, sem build e sem dependência. Editar e
enviar para a `main` já publica.

O arquivo `CNAME` é o que faz o GitHub Pages servir o domínio próprio.
Apagá-lo derruba `minhapauta.online`.

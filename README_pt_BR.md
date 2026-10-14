<h1 align="center">
<img src="https://i.imgur.com/txmTlvD.png" alt="Shibacoin" width="300"/>
<br/><br/>
Shibacoin Core [SHIC]  
</h1>

Selecionar idioma: EN | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md)

Shibacoin é uma criptomoeda focada na comunidade, criada por um dos shibes originais do Dogecoin de 2013. Foi criada com um propósito, criar uma comunidade nova e divertida, assim como a comunidade original do Dogecoin.

Diferente de todas as iterações anteriores, o Shibacoin é uma moeda de camada 1. Isso significa que não há piscinas de liquidez para drenar, carteiras em lista negra ou contratos inteligentes confusos. O Shibacoin é uma blockchain simples.

Assim como o Dogecoin, o software Shibacoin Core permite que qualquer pessoa opere um nó nas redes de blockchain do Shibacoin e usa o método de hash Scrypt para o Proof of Work. Ele é adaptado do Bitcoin Core e de outras criptomoedas.

Para informações sobre as taxas padrão usadas na rede Shibacoin, por favor consulte a [recomendação de taxas](doc/fee-recommendation.md).

## Diferenças do Dogecoin

O Shibacoin é um fork do Dogecoin. Para fins de familiaridade, tentaremos manter o Shibacoin semelhante ao Dogecoin.

Mudanças:

* Endereços começam com `S` em vez de `D`
* Recursos BIPS começam no bloco gênese
* GUI temático para o Shibacoin

## Uso 💻

Para iniciar sua jornada com o Shibacoin Core, veja o [guia de instalação](INSTALL.md) e o tutorial [começando](doc/getting-started.md).

A API JSON-RPC fornecida pelo Shibacoin Core é autoexplicativa e pode ser navegada com `shibacoin-cli help`, enquanto informações detalhadas para cada comando podem ser visualizadas com `shibacoin-cli help <comando>`. Alternativamente, veja a [documentação do Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - que implementa um protocolo semelhante - para obter uma versão navegável.

### Portas

O Shibacoin Core, por padrão, usa a porta `33864` para comunicação peer-to-peer que é necessária para sincronizar a blockchain "mainnet" e se manter informado sobre novas transações e blocos. Adicionalmente, uma porta JSONRPC pode ser aberta, que por padrão é a porta `33863` para nós mainnet. É altamente recomendável não expor as portas RPC na internet pública.

| Função   | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33864 |   44864 |   18444 |
| RPC      |   33863 |   44863 |   18332 |

## Desenvolvimento contínuo 💻

O Shibacoin Core é um software de código aberto e orientado pela comunidade. O processo de desenvolvimento é aberto e publicamente visível; qualquer um pode ver, discutir e trabalhar no software.

Principais recursos de desenvolvimento:

* [Projetos do GitHub](https://github.com/shibacoinpow/shibacoin/projects) são usados para seguir o trabalho planejado e em progresso para futuros lançamentos.
* [Discussão do GitHub](https://github.com/shibacoinpow/shibacoin/discussions) é usada para discutir recursos, planejados e não planejados, relacionados tanto ao desenvolvimento do software Shibacoin Core, quanto aos protocolos subjacentes e o ativo SHIC.  

### Estratégia de versão
Os números de versão seguem a semântica ```principal.menor.correção```.

### Branches
Existem 3 tipos de branches neste repositório:

- **master:** Estável, contém a versão mais recente do último lançamento *principal.menor*.
- **manutenção:** Estável, contém a versão mais recente de lançamentos anteriores, que ainda estão sob manutenção ativa. Formato: ```<versão>-manut```
- **desenvolvimento:** Instável, contém novo código para lançamentos planejados. Formato: ```<versão>-dev```

*Os branches master e de manutenção são exclusivamente mutáveis por lançamento. Lançamentos planejados sempre terão um branch de desenvolvimento e pull requests devem ser submetidos contra esses. Branches de manutenção são apenas para **correções de bugs,*** por favor, submeta novos recursos contra o branch de desenvolvimento com a versão mais alta.

## Contribuindo 🤝

Se você encontrar um bug ou tiver problemas com este software, por favor, relate usando o [sistema de problemas](https://github.com/shibacoinpow/shibacoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Por favor, veja [o guia de contribuição](CONTRIBUTING.md) para saber como você pode participar do desenvolvimento do Shibacoin Core. Muitas vezes há [tópicos buscando ajuda](https://github.com/shibacoinpow/shibacoin/labels/help%20wanted) onde suas contribuições terão alto impacto e serão muito apreciadas.

## Comunidades 🐸

Você pode se juntar às comunidades em diferentes mídias sociais.
Para ver o que está acontecendo, conhecer pessoas e discutir, encontrar o último meme, aprender sobre o Shibacoin, dar ou pedir ajuda, para compartilhar seu projeto.

## Perguntas Frequentes ❓

Você tem uma pergunta sobre o Shibacoin? A resposta pode estar na [FAQ](doc/FAQ.md) ou na [seção de Perguntas e Respostas](https://github.com/shibacoinpow/shibacoin/discussions/categories/q-a) do quadro de discussão!

## Licença ⚖️
O Shibacoin Core é lançado sob os termos da licença MIT. Veja
[COPYING](COPYING) para mais informações ou veja
[opensource.org](https://opensource.org/licenses/MIT)

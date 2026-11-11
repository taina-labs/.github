# Tainá

A caixa de uma comunidade que decidiu cuidar dos próprios dados.

O Tainá é uma nuvem privada e auto-hospedada para comunidades que querem guardar arquivos e fotos sem depender de uma grande plataforma. Uma caixa serve uma comunidade: as pessoas entram por convite, guardam o que é seu na `casa` e colocam na `praça` o que querem partilhar.

O nome vem do Tupi-Guarani e significa "estrela da manhã", aquela que guia os viajantes no fim da noite. Os nomes dos subsistemas seguem essa mesma escolha cultural: Ybira, Jaci, Maracá, Nhaman, Guará e outros que poderão aparecer com o tempo.

## Por que existe

Fotos de família, documentos e memórias coletivas ficam hoje espalhados por serviços que cobram mensalidade, mudam regras e podem desaparecer. Vazamentos, mercado de dados e uso de conteúdo privado para treinar modelos de linguagem fechados tornam essa dependência ainda mais cara. Quando esses modelos voltam como novos produtos pagos, a comunidade paga duas vezes: com os próprios dados e com a assinatura.

O Tainá é uma tentativa de recuperar **soberania digital brasileira**, começando por algo concreto: a comunidade escolhe onde os dados ficam, quem cuida da máquina e como tudo é recuperado se algo der errado. Nenhum modelo privado precisa ser alimentado com a memória de uma comunidade para que ela possa guardá-la.

Isso não exige que toda pessoa entenda de servidores. O produto precisa ser compreensível para quem usa e para quem instala. Instalação, atualização e recuperação são parte do produto, não detalhes escondidos atrás de uma tela bonita.

## O que já existe

- Interface web para arquivos, pastas, fotos, pessoas e permissões.
- `casa` privada por padrão e `praça` compartilhada por escolha explícita.
- Contas, convites, pedidos de acesso e concessões reversíveis.
- Mural e saúde da comunidade, sem telemetria enviada para fora.
- API JSON v1 e app Flutter para iOS e Android.
- Backup local e restauração, imagens multi-arch e instalação guiada.

A `casa` local é protegida por regras de software e confiança em quem opera a caixa. Quem tem root na máquina pode ler os arquivos. O projeto não apresenta isso como criptografia ponta a ponta.

## Rumo ao 1.0.0

O próximo marco fecha o ciclo **capturar, guardar e recuperar**:

- **No aparelho:** o app envia o rolo de câmera para a `casa`, em iOS e Android, sem publicar nada automaticamente na `praça`.
- **Na caixa:** arquivos e fotos continuam disponíveis na rede e na interface da comunidade.
- **Fora da caixa:** um backup incremental é cifrado antes de ir para o destino externo, para que o provedor não leia seu conteúdo.
- **Na recuperação:** kits aleatórios equivalentes permitem abrir o cofre e restaurar uma instalação nova. Não existe chave de resgate da mantenedora.

Os clientes precisam passar em simulador iOS e emulador Android locais. Instalação, atualização, backup e restore também precisam de ensaios com pessoas e comunidades reais. O [ensaio público](https://github.com/taina-labs/tekoa/blob/main/guias/ensaio-mvp-vm-macos.md) registra o que já passou e o que ainda falta, sem transformar VM em Raspberry Pi nem resultado qualitativo em benchmark.

E2E, espelho bidirecional e propagação de exclusões não fazem parte desse corte.

## Como o ecossistema pode crescer

O cofre é o começo, não uma promessa de que todos estes serviços já existem:

- **Maracá:** identidade, convites, papéis e permissões.
- **Ybira:** arquivos, pastas, zonas, cotas e armazenamento.
- **Jaci:** galeria e linha do tempo sobre os arquivos do Ybira.
- **Nhaman:** instalação, saúde, backup e operação da caixa.
- **Guará:** chat futuro. A assembleia pode aparecer nesse fluxo, mantendo regras próprias para propostas, votos e quórum.
- **Araci e Arapa:** ideias de longo prazo para vídeo, música e áudio.
- **Ka'a e Karai:** ideias para casa inteligente e monitoração.

Busca, backup pessoal portátil e outras melhorias vêm depois do `1.0.0`, orientadas pelo uso das comunidades. Nada nessa lista de futuro deve ser lido como recurso disponível hoje.

## Como participar

**Para usar e experimentar:** acompanhe os guias, teste uma instalação descartável e conte onde o caminho ficou confuso. Ensaios com pessoas não técnicas são especialmente valiosos.

**Para contribuir:** código, testes, documentação, acessibilidade, design e operação são bem-vindos. O Tekoá reúne o estado atual e as decisões; o repositório do Tainá tem as instruções técnicas.

**Para construir com a comunidade:** propostas começam pelo problema que uma comunidade precisa resolver, não por uma lista de serviços para copiar.

## Documentação e código

- [Tekoá](https://github.com/taina-labs/tekoa): documentação, guias e roadmap, a fonte de verdade do projeto.
- [Tainá](https://github.com/taina-labs/taina): caixa, API e app Flutter.
- [Como contribuir](https://github.com/taina-labs/tekoa/blob/main/CONTRIBUTING.md).

O projeto é aberto sob AGPL-3.0. Contato: [zoey.spessanha@zeetech.io](mailto:zoey.spessanha@zeetech.io).

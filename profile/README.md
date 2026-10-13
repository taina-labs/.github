# Tainá: Sua Nuvem, Suas Regras
### Um Projeto Comunitário para Independência Digital

## O que é o Tainá?

Imagine ter seu próprio Netflix, Spotify, Google Drive, WhatsApp e Alexa - mas sem depender de nenhuma grande empresa. Imagine que você e seus **amigos**, seus **afetos**, sua **comunidade** controlam completamente seus dados, suas fotos, suas conversas. Isso é o **Tainá**.

O nome vem do Tupi-Guarani e significa "estrela da manhã" - aquela que guia os viajantes no fim da noite em direção ao amanhecer. É exatamente isso que queremos ser: um guia para comunidades que buscam independência digital.

## Por que isso é importante?

Hoje, nossas vidas digitais estão nas mãos de poucas empresas gigantes:
- Suas fotos de família estão no Google ou iCloud
- Suas conversas estão no WhatsApp ou Telegram  
- Seus filmes estão na Netflix ou Prime
- Sua música está no Spotify ou YouTube

**E se...**
- Esses serviços aumentarem os preços? (já está acontecendo)
- Pudéssemos evitar a vendas dos nossos dados?
- Fosse possível um mundo mais solidário, comunitário e **humano**?

Com o Tainá, você e sua **comunidade** têm controle total. É como ter sua própria "empresa de tecnologia" caseira, mas muito mais simples e **barata**.

## Como funciona na prática?

### O Conceito é Simples

Em vez de cada pessoa pagar R$ 40 para cada serviço de streaming, R$ 20 para serviço de música, R$ 50 para armazenamento em nuvem, etc., um grupo de 20 amigos divide o custo de um pequeno servidor (tipo um computador especial) e a conta de luz.

**Exemplo real de custos:**
- Serviços tradicionais: R$ 200/mês por pessoa
- Com Tainá: R$ 10-20/mês por pessoa
- Economia: R$ 180/mês (R$ 2.160/ano!)

### O que você terá acesso?

> **Onde estamos agora (2026):** o MVP em desenvolvimento é o **cofre de
> arquivos e fotos da comunidade, com instalação indolor** — Ybira + Jaci,
> com contas e convites. Os demais serviços são a visão de longo prazo.
> Detalhes na [RFC 002](https://github.com/taina-labs/tekoa/blob/main/tecnico/RFC_002_MVP.md)
> e no [Roadmap](https://github.com/taina-labs/tekoa/blob/main/ROADMAP.md).

#### [**Ybira**](https://github.com/taina-labs/taina/blob/main/lib/taina/ybira/README.md) - Seu Cofre Digital — **MVP**
Guarde arquivos, documentos, fotos com segurança. Como Google Drive, mas com espaço ilimitado (depende só do HD que vocês comprarem).

#### [**Jaci**](https://github.com/taina-labs/taina/blob/main/lib/taina/jaci/README.md) - Álbum de Memórias — **MVP**
Suas fotos organizadas em grade e linha do tempo. Como Google Fotos, mas privado de verdade. Backup automático do celular e reconhecimento de rostos vêm depois do MVP.

#### [**Nhaman**](https://github.com/taina-labs/taina/blob/main/lib/taina/nhaman/README.md) - Centro de Comando — **parcial no MVP**
Um painel único para controlar todos os serviços. No MVP: setup inicial, gestão de pessoas, backup e atualização.

#### [**Guará**](https://github.com/taina-labs/taina/blob/main/lib/taina/guara/README.md) - Mensageiro Privado — pós-MVP
Conversas e grupos. Tipo WhatsApp, mas suas mensagens ficam no SEU servidor, não nos EUA.

#### [**Araci**](https://github.com/taina-labs/taina/blob/main/lib/taina/araci/README.md) - Seu Cinema em Casa — visão de longo prazo
Como Netflix/Prime, mas você coloca os filmes e séries que quiser. Sem catálogo limitado, sem conteúdo que some do nada.

#### [**Arapa**](https://github.com/taina-labs/taina/blob/main/lib/taina/arapa/README.md) - Sua Rádio Pessoal — visão de longo prazo
Toda sua música, podcasts e audiolivros em um só lugar. Crie playlists, compartilhe com amigos, sem propaganda.

#### [**Ka'a**](https://github.com/taina-labs/taina/blob/main/lib/taina/kaa/README.md) - Casa Inteligente — visão de longo prazo
Controle lâmpadas, câmeras, sensores. Sem depender de Alexa ou Google Home.

#### [**Karai**](https://github.com/taina-labs/taina/blob/main/lib/taina/karai/README.md) - Guardião Digital — visão de longo prazo
Protege tudo, faz backup automático, garante que nada se perca.

#### [**Tekoá**](https://github.com/taina-labs/tekoa) - Documentação e Comunidade
A fonte de luz e saber para a comunidade Tainá.

### Ypy: o núcleo que sustenta tudo

Cada comunidade roda a sua própria caixa do Tainá. O box, a plataforma
hospedada e os produtos futuros (como a Universidade) compartilham o mesmo
núcleo, chamado **Ypy** (Tupi: origem): identidade, arquivos, o modelo social
(casa/praça, zelador/morador), o mural e a assembleia vivem numa biblioteca
aberta de que cada produto depende. É o que faz um produto novo nascer já
falando a mesma língua, sem reimplementar o núcleo.
Ver a [RFC 006](https://github.com/taina-labs/tekoa/blob/main/tecnico/RFC_006_KERNEL.md).

## Quem pode participar?

### Você NÃO precisa ser técnico!

O projeto é pensado para três tipos de pessoas:

**Usuários Comuns**
- Só querem usar os serviços
- Pagam uma mensalidade pequena
- Não precisam entender nada técnico
- Interface simples como qualquer app

**Entusiastas**
- Gostam de tecnologia mas não são programadores
- Podem ajudar a manter o servidor
- Aprendem fazendo
- Ganham desconto ou isenção da mensalidade

**Desenvolvedores**
- Programadores que querem contribuir
- Podem criar novos recursos
- Comunidade open source
- Oportunidade de aprender Elixir

## Como começamos?

### Fase 1: O Começo
**Investimento inicial: R$ 1.000-2.000 dividido entre todos**

Começamos pequeno, com um mini-computador (Raspberry Pi) que cabe na palma da mão. Ele vai rodar:
- Armazenamento de arquivos básico
- Streaming de filmes para 5-8 pessoas simultâneas  
- Backup de fotos do celular
- Chat básico

*20 amigos = R$ 50-100 cada um para começar*

### Fase 2: Crescendo
**Investimento: R$ 3.000-5.000 total**

Migramos para um computador mais potente:
- Suporta 15-20 pessoas ao mesmo tempo
- Todos os serviços funcionando bem
- Velocidade profissional
- Backup automático

*Custo mensal por pessoa: R$ 15-25*

### Fase 3: Profissional
**Investimento: R$ 8.000-12.000 total**

Sistema profissional completo:
- 50+ usuários simultâneos
- Inteligência artificial local
- Assistente virtual próprio
- Casa inteligente completa

*Ainda assim, apenas R$ 20-30 por pessoa/mês*

## Segurança e Privacidade

### Seus dados são SEUS

- **Sem espionagem**: Nenhuma empresa analisando seus dados
- **Sem propaganda**: Algoritmos não manipulam o que você vê
- **Backup triplo**: Suas memórias sempre seguras
- **Criptografia**: Tudo protegido com tecnologia militar
- **Acesso VPN**: Acesse de qualquer lugar do mundo

### Comparação com Serviços Tradicionais

| Aspecto | Serviços Comerciais | Tainá |
|---------|-------------------|--------|
| Controle dos dados | Empresa | Você |
| Privacidade | Limitada | Total |
| Custo mensal | R$ 150+ | R$ 20 |
| Limites de uso | Sim | Não (custo variável) |
| Propaganda | Sim | Nunca |
| Pode desaparecer | Sim | Não |

## Perguntas Frequentes

### "Mas e se der problema técnico?"

A comunidade se ajuda! Sempre terá alguém mais técnico no grupo. Além disso, criaremos:
- Tutoriais em vídeo em português
- Manual ilustrado passo-a-passo

### "E a qualidade? É igual Netflix?"

Para streaming: Sim! 4K, HDR, tudo que seu equipamento suportar.
Para música: Qualidade de CD ou melhor.
Para arquivos: Velocidade de rede local, muito mais rápido que nuvem.

### "Quanto de internet preciso?"

Para hospedar: 50-100 Mbps de upload (fibra ótica comum)
Para usar: Qualquer internet (até 4G funciona bem)

### "E se o servidor queimar?"

Backup automático em 3 lugares:
1. No servidor principal
2. Em outro HD no mesmo local
3. Na casa de outro membro (criptografado)

### "É legal?"

Totalmente! Você está apenas criando sua própria nuvem privada. É como ter um computador potente em casa, mas compartilhado com amigos.

## Como participar?

### Para Usuários

1. **Encontre um grupo** - Procure amigos interessados
2. **Contribua** - R$ 50-100 inicial + R$ 20/mês
3. **Use** - Apps no celular e computador, igualzinho aos comerciais
4. **Aproveite** - Sua nuvem, suas regras!

### Para Entusiastas

1. **Aprenda** - Tutoriais e workshops gratuitos
2. **Monte** - Ajude a configurar o servidor
3. **Mantenha** - 2-3 horas por mês de manutenção
4. **Ganhe** - Isenção da mensalidade ou pagamento da comunidade

### Para Desenvolvedores

1. **Contribua** - Código aberto no GitHub
2. **Crie** - Novos recursos e melhorias
3. **Ensine** - Workshops e mentoria
4. **Cresça** - Aprenda Elixir e sistemas distribuídos

## Por que "Tainá"?

Escolhemos nomes da cultura brasileira para todos os serviços. Tainá, a estrela da manhã, guia o projeto. Cada serviço tem um nome da nossa mitologia:

- **Araci** - Aurora, deusa do amanhecer
- **Arapa** - Som/voz, inspirado na ave Araponga
- **Ybira** - Árvore, símbolo de raízes, crescimento
- **Guará** - Lobo-guará, veloz e protetor
- **Jaci** - Lua, associada à memória e ciclos
- **Ka'a** - Floresta, ambiente vivo e conectado
- **Karai** - Espírito do fogo, força e proteção
- **Nhaman** - Criador primordial (de Nhamandú - início de tudo na mitologia tupi-guarani)
- **Tekoá** - “lugar onde se vive” ou “aldeia”

## Próximos Passos

### Estamos construindo agora:

**MVP** - cofre de arquivos e fotos com instalação plug & play
([RFC 002](https://github.com/taina-labs/tekoa/blob/main/tecnico/RFC_002_MVP.md) ·
[Roadmap](https://github.com/taina-labs/tekoa/blob/main/ROADMAP.md))
**Documentação** - Tutoriais em português no [Tekoá](https://github.com/taina-labs/tekoa)
**Implementação dos Serviços** - Código aberto, **sempre**

### Como você pode ajudar:

- **Divulgue** para amigos interessados
- **Participe** do grupo de discussão
- **Teste** a versão beta
- **Contribua** com ideias e feedback
- **Apoie** financeiramente o desenvolvimento

## Contato

Email: zoey.spessanha@zeetech.io (temporário)
GitHub: github.com/taina-labs

---

### Junte-se a nós!

Estamos construindo mais que tecnologia - estamos criando independência digital para comunidades dissidentes. Cada pessoa que participa torna o projeto mais forte e a rede mais valiosa.

**Sua nuvem. Suas regras. Sua comunidade.**

*Tainá - Guiando comunidades para a independência digital*

---

## Referências e Leitura Adicional

Para quem quiser entender melhor:

1. **O que é auto-hospedagem?** - [Artigo na Wikipedia](https://pt.wikipedia.org/wiki/Auto-hospedagem)
2. **Privacidade Digital** - [Cartilha do CGI.br](https://cartilha.cert.br/privacidade/)
3. **Software Livre** - [Guia do Software Livre](https://softwarelivre.org/)
4. **Comunidades Tecnológicas** - [Mozilla Brasil](https://mozilla.org.br)
5. **Elixir Brasil** - [Elixir em Foco Podcast](https://anchor.fm/elixiremfoco)

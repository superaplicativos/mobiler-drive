# 🚗 MobilerDrive v7.0 — Seu Próprio Aplicativo de Transporte de Passageiros

> **Tecnologia whitelabel completa para você empreender no mercado de mobilidade urbana com sua própria marca, seu código e total liberdade.**

[![Versão](https://img.shields.io/badge/Versão-7.0-6B3FA0?style=for-the-badge)](https://mobiler.com.br)
[![Flutter](https://img.shields.io/badge/Flutter-3.29.2-02569B?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![Laravel](https://img.shields.io/badge/Laravel-PHP%208.2-FF2D20?style=for-the-badge&logo=laravel)](https://laravel.com)
[![Licença](https://img.shields.io/badge/Modelo-Código--Fonte%20Próprio-E8610A?style=for-the-badge)](https://mobiler.com.br)

---

## 📱 O que é o MobilerDrive?

O **MobilerDrive v7.0** é uma plataforma completa de mobilidade urbana — similar ao Uber — desenvolvida pela **Mobiler**, fábrica de software especializada em aplicativos de transporte. Você adquire o **código-fonte completo**, personaliza com sua marca e opera com total autonomia.

São **3 sistemas integrados**:

| Sistema | Plataforma | Público |
|---|---|---|
| **App do Passageiro** | Flutter (Android + iOS) | Usuários finais |
| **App do Motorista** | Flutter (Android + iOS) | Motoristas parceiros |
| **Painel Administrativo** | Laravel (Web) | Gestor da operação |

---

## 🏆 Por que adquirir o MobilerDrive?

### Você é o dono da tecnologia

Diferente de plataformas SaaS que prendem você a contratos e mensalidades perpétuas, aqui você **compra o código-fonte** — assim como se compra um imóvel. Você pode reformar, expandir, colocar sua equipe para trabalhar e hospedar onde quiser.

| ✅ Com MobilerDrive | ❌ Com SaaS concorrente |
|---|---|
| Código-fonte 100% seu | Acesso revogável a qualquer momento |
| Sua equipe pode editar livremente | Dependência total do fornecedor |
| Hospede em qualquer servidor | Servidor obrigatório do fornecedor |
| Sem royalties ou taxas de uso | Mensalidades e taxas por corrida sempre |
| Evolua a plataforma como quiser | Funcionalidades limitadas ao pacote |
| Fábrica de software parceira disponível | Zero customização ou orçamento à parte |

---

## ✨ Funcionalidades da Plataforma

### App do Passageiro
- 📍 Mapa em tempo real com rastreamento do motorista
- 🚗 **Modo Sob Demanda** — solicita corrida no preço fixo calculado
- 💡 **Modo Lance** — passageiro oferta o próprio valor da corrida
- 📅 Agendamento de viagens para datas e horários futuros
- 💳 Múltiplas formas de pagamento: cash, online, cartão, wallet
- 💰 Carteira digital integrada (adicionar, transferir saldo)
- 🎁 Cashback e programa de fidelidade integrados
- 🔖 Cupons e promoções
- 👜 Preferências de viagem (bagagem, animal de estimação)
- 📦 Módulo de Entrega integrado
- ⏱️ Módulo de Aluguel integrado
- 🔒 Botão SOS de emergência
- ⭐ Avaliação e histórico de corridas
- 🌍 Multi-idioma: Português (BR/PT), Inglês, Espanhol
- 🌙 Tema claro/escuro
- 📌 Localizações favoritas (Casa, Trabalho e outros)
- 🔔 Notificações push em tempo real

### App do Motorista
- 📲 Cadastro com envio de documentos pelo próprio app
- ✅ Operação liberada somente após aprovação pelo painel
- 🗺️ Navegação integrada (Google Maps / Waze)
- 📡 Recebimento de solicitações em tempo real
- 🔢 Verificação OTP do passageiro para iniciar corrida
- 📸 Comprovante fotográfico em entregas
- 💵 Painel de ganhos: diário, semanal e histórico completo
- 🏆 Gamificação: níveis, metas e recompensas
- 📋 Histórico de corridas e faturas

### Painel Administrativo (Web)
- 🌐 **God's Eye** — visão de toda a frota no mapa em tempo real
- 📊 Dashboard com métricas de operação
- 👥 Gestão completa de passageiros e motoristas
- 🚙 Gestão de frota e proprietários (owners)
- 💰 Controle financeiro: comissões, repasses, saques
- 🗂️ Relatórios: Finance, Fleet, Owner por período e serviço
- 📣 Campanhas de notificações push segmentadas
- 🏷️ Criação de cupons e promoções
- 🔧 Configuração de tipos de veículo e tarifas
- ⚡ Zonas de pico (surge pricing) por área e horário
- 🏢 **Multi-operador**: gestão por franqueados com painéis independentes
- 📋 Sistema de suporte e tickets
- 🌍 Módulo de traduções automáticas
- 🔐 Permissões por nível de acesso (Admin, Dispatcher, Owner)
- 📡 Dispatcher avançado com atribuição manual de corridas
- ✈️ Gerenciamento de aeroportos e rotas especiais

---

## 💳 Gateways de Pagamento Integrados

A plataforma já vem com integração nativa para os principais gateways do mercado:

**Brasil:** Asaas · OpenPix (Pix) · MercadoPago · Stripe  
**Internacional:** PayPal · Flutterwave · Razorpay · Paystack · Cashfree · CCAvenue · Khalti · MyFatoora · Easypaisa · Payphone · Paytech · Flexpaie · Bankily · Xendit

---

## 🛠️ Stack Tecnológica

```
Backend        →  Laravel (PHP 8.2) + MySQL + Apache
Apps Móveis    →  Flutter 3.29.2 (Dart) — Android & iOS
Autenticação   →  Laravel Sanctum
Notificações   →  Firebase Cloud Messaging
Mapas          →  Google Maps API
Tempo Real     →  WebSockets / Laravel Broadcasting
Servidor       →  Linux VPN + SSL + Crontabs
```

---

## 📲 Telas do App Passageiro

As imagens abaixo mostram a versão 7.0 em funcionamento real:

| Tela Inicial | Seleção de Destino | Escolha de Serviço |
|:---:|:---:|:---:|
| Mapa + localização | Origem/destino | Viagem · Entrega · Aluguel |

| Modo Sob Demanda | Modo Lance | Buscando Motorista |
|:---:|:---:|:---:|
| Tarifa fixada + Viajar Agora | Passageiro define o valor | Raio de busca em tempo real |

| Pagamento | Preferências | Minha Conta |
|:---:|:---:|:---:|
| Cash ou Online | Bagagem · Pet | Perfil · Histórico · SOS |

| Carteira | Localizações Favoritas | Configurações |
|:---:|:---:|:---:|
| Saldo + Transações | Casa · Trabalho | Tema · FAQ · Privacidade |

> 📸 Screenshots completos disponíveis na pasta `/screenshots` deste repositório.

---

## 💰 Investimento

### Aquisição do Código-Fonte — Licença Perpétua

| | Valor |
|---|---|
| **Valor total** | R$ 36.000 |
| **Entrada** | R$ 9.900 |
| **Restante** | Leasing no boleto com juros |

> ✅ **Sem royalties. Sem mensalidades obrigatórias. Sem taxas por corrida.**  
> O código é seu para sempre — como qualquer outro ativo do seu negócio.

---

### Plano de Servidor & Suporte Premium — Opcional

| Recurso | Valor |
|---|---|
| **Mensalidade** | R$ 990/mês |
| **Corridas inclusas** | 2.000 corridas/mês |
| **Corrida excedente** | R$ 0,49 cada |
| **Fidelidade** | Sem fidelidade mínima |

**Inclui:** Servidor gerenciado · SSL · Backups automáticos · Monitoramento · Suporte técnico premium · Atualizações de segurança

> 💡 Prefere hospedar no seu próprio servidor? Sem problema. Essa é exatamente a liberdade que você tem.

---

## 🏭 Fábrica de Software — Evolução Contínua

A Mobiler não para quando entrega o código. Somos uma **fábrica de software full service** especializada em mobilidade urbana.

Precisa de uma nova funcionalidade? Integração com parceiro regional? Mudança de regra de negócio? **Funciona assim:**

```
1. Você traz a demanda
2. Reunião com equipe técnica para alinhamento de escopo
3. Estimativa de horas e orçamento enviado para aprovação
4. Você aprova → desenvolvemos e entregamos
```

Exemplos de customizações já realizadas para clientes:
- Integração com gateways de pagamento regionais
- Módulo de transporte escolar
- Sistema de transporte corporativo
- Módulo de corridas intermunicipais
- Relatórios personalizados de BI
- Redesign completo de interface

---

## 🚀 Como Funciona a Contratação

```
PASSO 1 — Reunião Comercial
Apresentamos a solução, entendemos seu projeto,
alinhamos expectativas. Sem compromisso.

PASSO 2 — Contrato e Pagamento
Formalizamos o contrato, processamos a entrada
e iniciamos a preparação da entrega.

PASSO 3 — Onboarding e Personalização
Coletamos logomarca, cores, dados de integrações
(Firebase, Google Maps, gateways). Configuramos
tudo com a identidade da sua marca.

PASSO 4 — Entrega e Treinamento
Entregamos o código-fonte, publicamos os apps,
treinamos sua equipe e acompanhamos o lançamento.
```

---

## 📚 Documentação Incluída

Com a aquisição você recebe:

- 📖 **Tutorial completo da Plataforma** — guia visual cobrindo Configuração Inicial, Operação no Painel, Gestão de Pessoas e Frota, Marketing, Financeiro, Segurança, App Passageiro, App Motorista, Fluxos e Boas Práticas
- 📡 **Documentação de Rotas API & Web** — todos os endpoints REST documentados com parâmetros, FormRequests e descrições
- 🏗️ **Documentação do Sistema** — arquitetura, requisitos técnicos, stack completa e guia de ambientação do servidor e dos apps
- 🎥 **Videoaulas no YouTube** — treinamentos detalhados para sua equipe aprender de forma prática

---

## 🌟 Diferenciais Exclusivos

### Sem restrições geográficas
Opere em quantas cidades quiser, em qualquer estado ou país. Sem limites por plano.

### Cashback nativo
Sistema de cashback integrado que mantém o saldo dentro do app — muito mais eficaz que cupons tradicionais para retenção de clientes.

### Modo Lance (Bidding)
Funcionalidade exclusiva onde o passageiro pode oferecer o próprio valor da corrida, criando um mercado dinâmico entre passageiro e motorista.

### Painel para franqueados
Estrutura multi-operador pronta para quem quer franquear a operação. Cada franqueado com seu próprio painel, o gestor com visão completa.

### Programa de indicação
"Indique e Ganhe" integrado para crescimento orgânico da base de usuários e motoristas.

---

## 🏙️ Nichos de Mercado

A plataforma já foi adaptada por nossos clientes para dezenas de nichos diferentes:

- Táxi e transporte particular
- Transporte escolar
- Transporte corporativo/executivo
- Transporte intermunicipal
- Mototáxi
- Transporte para eventos
- Transporte hospitalar/saúde
- Cidades médias sem cobertura de grandes apps
- Cooperativas de motoristas

---

## 📞 Fale com o Comercial

Pronto para ter seu próprio aplicativo? Entre em contato com nossa equipe:

| Canal | Contato |
|---|---|
| 📱 **WhatsApp** | [+55 11 99431-7886](https://wa.me/5511994317886) |
| 📧 **E-mail** | [financeiro@mobiler.com.br](mailto:financeiro@mobiler.com.br) |
| 🌐 **Site** | [mobiler.com.br](https://mobiler.com.br) |
| 📍 **Sede** | Rua do Paraíso, 769 — São Paulo, SP |

---

## 🔒 Licença

Este repositório contém o código-fonte do **MobilerDrive v7.0**, licenciado exclusivamente para o cliente adquirente. A redistribuição, sublicenciamento ou comercialização do código é expressamente vedada pelos termos do contrato de aquisição.

**Mobiler** é uma marca registrada no INPI. Todos os direitos reservados.

---

<div align="center">

**Feito com 💜 pela equipe Mobiler**

[mobiler.com.br](https://mobiler.com.br) · [WhatsApp](https://wa.me/5511994317886) · [financeiro@mobiler.com.br](mailto:financeiro@mobiler.com.br)

</div>

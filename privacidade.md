# POLÍTICA DE PRIVACIDADE — LUMIO AI

**Última atualização:** 31 de julho de 2026

Esta Política de Privacidade ("Política") explica como o **Lumio AI** ("Aplicativo", "nós" ou "nosso") coleta, usa, compartilha e protege os dados pessoais dos usuários do Aplicativo ("Usuário" ou "você"). O Lumio AI é disponibilizado por um desenvolvedor independente; as informações de identificação e contato do desenvolvedor estão disponíveis na ficha oficial do Aplicativo na loja de distribuição em que ele foi obtido (por exemplo, na seção "Sobre o desenvolvedor" do Google Play).

Esta Política complementa os nossos **Termos de Uso** e deve ser lida em conjunto com eles. Ao utilizar o Lumio AI, você concorda com as práticas aqui descritas.

Este documento poderá ser traduzido para os demais idiomas suportados pelo Aplicativo para fins de conveniência do Usuário. **Em caso de conflito entre uma versão traduzida e o idioma original em que este documento foi redigido, prevalecerá o idioma original**, exceto quando a legislação aplicável ao Usuário exigir de forma cogente que a versão traduzida prevaleça.

---

## 1. QUE DADOS COLETAMOS

### 1.1. Dados fornecidos diretamente por você
* **Dados de cadastro:** e-mail e senha (armazenada apenas em formato criptografado/hash), ou, caso opte por autenticação social, os dados básicos de perfil fornecidos pelo provedor (ex.: Google Sign-In).
* **Mensagens de conversa:** o conteúdo das mensagens que você troca com os Lumis.
* **Ficha Pessoal e testes de personalidade** *(recurso Pro)*: informações que você opta por fornecer sobre si mesmo, incluindo respostas a testes de personalidade. Dependendo do que você compartilhar, esses dados podem incluir **dados pessoais sensíveis** (por exemplo, informações relacionadas à sua saúde mental ou estado psicológico).
* **PIN local:** caso você configure o bloqueio por PIN, ele é armazenado e verificado **exclusivamente no seu dispositivo** — nunca é transmitido, coletado ou visível para nós.

### 1.2. Dados coletados automaticamente
* **Memória Persistente:** informações que os Lumis retêm automaticamente a partir do que você compartilha espontaneamente durante as conversas, com a finalidade de dar continuidade e coerência às interações futuras. Veja a Cláusula 4.1 e a Cláusula 8 sobre como isso é tratado e como você pode controlá-lo.
* **Dados técnicos do dispositivo:** modelo do aparelho, versão do sistema operacional, identificador de instalação do aplicativo, idioma configurado, e dados de diagnóstico de falhas (*crash logs*), quando aplicável.
* **Endereço IP:** processado transitoriamente pela nossa infraestrutura de rede e de backend para fins de segurança e operação do Serviço.
* **Identificador de notificação push:** um token de dispositivo usado exclusivamente para o envio da notificação diária (Cláusula 11).
* **Registros de uso agregados:** como a contagem de mensagens enviadas, necessária para aplicar os limites do plano gratuito e a política de uso razoável dos planos Pro.

### 1.3. Dados que não coletamos
O Lumio AI **não coleta** dados de localização geográfica, **não acessa** sua lista de contatos, **não coleta** dados biométricos, e **não coleta nem armazena** dados de pagamento (número de cartão, etc.) — essas informações são processadas exclusivamente pelo Google Play Billing, nos termos da Cláusula 4.3.

> *Nota de conformidade: esta seção deve ser conferida contra os SDKs efetivamente integrados ao Aplicativo (ex.: analytics, crash reporting) antes da publicação — veja a Cláusula 10. O formulário de Data Safety do Google Play Console precisa declarar exatamente as mesmas categorias listadas aqui; qualquer divergência entre este documento e aquele formulário é motivo de rejeição ou remoção pela Play Store.*

---

## 2. COMO E POR QUE USAMOS SEUS DADOS

Usamos os dados descritos na Cláusula 1 para as seguintes finalidades:
* Operar e disponibilizar as conversas com os Lumis;
* Personalizar as interações com base na Ficha Pessoal e na Memória Persistente;
* Criar, autenticar e proteger sua conta;
* Processar assinaturas e compras, em conjunto com o Google Play Billing;
* Enviar a notificação diária, caso ativada (Cláusula 11);
* Processar denúncias de conteúdo inadequado e aprimorar os sistemas de moderação;
* Aplicar a política de uso razoável e prevenir fraude, abuso ou uso automatizado indevido;
* Cumprir obrigações legais e responder a solicitações de autoridades competentes.

**Não utilizamos** dados relacionados à sua saúde mental ou estado psicológico para fins de decisão sobre emprego, crédito, seguro ou finalidades semelhantes, nem os compartilhamos publicamente ou com fins de compartilhamento social sem o seu consentimento explícito. **Não vendemos** seus dados pessoais a terceiros para fins de publicidade.

---

## 3. BASE LEGAL PARA O TRATAMENTO

Dependendo da legislação de proteção de dados aplicável ao seu país de residência, tratamos seus dados com base em um ou mais dos seguintes fundamentos: (i) o seu consentimento, especialmente para dados sensíveis, como os da Ficha Pessoal; (ii) a necessidade de execução do contrato firmado por meio dos Termos de Uso, para operar o Serviço que você solicitou; (iii) o cumprimento de obrigação legal ou regulatória; e (iv) nosso interesse legítimo em manter a segurança, prevenir fraudes e melhorar o Serviço, quando esse interesse não prevalecer sobre seus direitos e liberdades fundamentais.

---

## 4. COMPARTILHAMENTO DE DADOS COM TERCEIROS

Não vendemos seus dados pessoais. Compartilhamos dados apenas com os seguintes tipos de terceiros, e apenas na medida necessária para operar o Serviço:

### 4.1. Provedor de Infraestrutura de Inteligência Artificial
Para gerar as respostas dos Lumis, suas mensagens são enviadas, de forma cifrada em trânsito, a um provedor terceirizado de infraestrutura de inteligência artificial. Esse provedor processa os dados **exclusivamente para gerar a resposta solicitada**. Buscamos assegurar — por meio dos termos contratuais do provedor ou de configurações técnicas disponíveis — que esses dados não sejam utilizados por esse provedor para treinar ou aprimorar modelos de terceiros de forma que identifique o Usuário, exceto quando expressamente permitido pela legislação aplicável ou autorizado por você.

> *Nota de conformidade: confirme, nos termos contratuais reais do provedor de IA utilizado, se essa representação é tecnicamente exata (ou seja, se o provedor de fato não usa dados de API para treinamento por padrão) antes de publicar este texto — isso precisa refletir a realidade operacional, não uma aspiração.*

### 4.2. Provedor de Backend e Autenticação
Utilizamos o **Supabase** para autenticação de conta, sincronização e armazenamento de determinados dados de conta.

### 4.3. Google Play
Pagamentos, assinaturas e, quando aplicável, autenticação social (Google Sign-In) são processados pelo Google, sujeitos à própria política de privacidade do Google. Não temos acesso aos dados de pagamento do Usuário.

### 4.4. Autoridades Públicas
Podemos divulgar dados quando exigido por lei, ordem judicial ou solicitação legítima de autoridade competente.

### 4.5. Sucessão Empresarial
Em caso de fusão, aquisição, reorganização ou venda de ativos, seus dados podem ser transferidos como parte dessa operação, sempre sujeitos às proteções equivalentes às aqui descritas.

---

## 5. TRANSFERÊNCIA INTERNACIONAL DE DADOS

O provedor de infraestrutura de inteligência artificial referido na Cláusula 4.1, assim como outros provedores de infraestrutura utilizados pelo Lumio AI, podem processar dados em servidores localizados fora do seu país de residência. **Ao utilizar o Aplicativo, você reconhece e consente com essa eventual transferência internacional de dados**, ciente de que o país de destino pode não possuir grau de proteção de dados reconhecido como equivalente ao do seu país de residência.

---

## 6. SEGURANÇA DOS DADOS

* **No dispositivo:** conversas e dados armazenados localmente utilizam criptografia forte (**AES-GCM**) via **Android Keystore**.
* **Em trânsito:** todas as comunicações entre o Aplicativo e nossos servidores utilizam o protocolo HTTPS/TLS.
* **No backend:** aplicamos controles de acesso técnicos e organizacionais razoáveis sobre os dados armazenados no Supabase.

Nenhum método de transmissão ou armazenamento eletrônico é 100% seguro. Embora adotemos medidas razoáveis para proteger seus dados, não podemos garantir segurança absoluta.

---

## 7. RETENÇÃO E EXCLUSÃO DE DADOS

* Mantemos seus dados pelo tempo necessário para prestar o Serviço, enquanto sua conta estiver ativa.
* Você pode excluir sua conta e os dados associados a qualquer momento, diretamente nas configurações do Aplicativo. Após a exclusão, seus dados são removidos de nossos sistemas ativos em até **[30] dias**, ressalvados prazos de retenção exigidos por lei (por exemplo, registros fiscais) ou necessários para resolver disputas em andamento.
* Caso você deixe de ser assinante Pro, os dados da Ficha Pessoal e a Memória Persistente permanecerão armazenados de forma inacessível por até **[90] dias**, podendo ser reativados mediante nova assinatura; findo esse prazo, poderão ser excluídos automaticamente.
* Cópias de segurança (*backups*) podem reter dados por um período adicional limitado após a exclusão, por razões técnicas de recuperação de desastres.

> *Nota de conformidade: os prazos entre colchetes são valores de referência — defina os prazos reais que o produto vai efetivamente cumprir antes de publicar, e garanta que o formulário de Data Safety do Play Console reflita a mesma política de exclusão declarada aqui.*

---

## 8. SEUS DIREITOS SOBRE OS DADOS

Dependendo da legislação de proteção de dados aplicável ao seu país de residência (por exemplo, o GDPR na União Europeia/Reino Unido, a LGPD no Brasil, a CCPA na Califórnia, a PIPEDA no Canadá, ou legislações equivalentes em outros países), você pode ter o direito de, mediante solicitação:
* Confirmar a existência de tratamento de dados sobre você;
* Acessar os dados que temos sobre você;
* Corrigir dados incompletos, inexatos ou desatualizados;
* Solicitar a anonimização, o bloqueio ou a eliminação de dados desnecessários ou tratados de forma excessiva;
* Solicitar a portabilidade dos seus dados a outro fornecedor de serviço;
* Solicitar a eliminação dos dados tratados com base em consentimento;
* Obter informações sobre com quais terceiros seus dados foram compartilhados;
* Revogar, a qualquer momento, o consentimento fornecido para tratamento de dados sensíveis (como os da Ficha Pessoal);
* Opor-se a determinados tratamentos realizados com base em nosso interesse legítimo.

Para exercer qualquer um desses direitos, entre em contato pelos canais indicados na Cláusula 13. Envidamos esforços para responder dentro de um prazo razoável, observando os prazos específicos exigidos pela legislação aplicável ao seu caso.

---

## 9. CRIANÇAS E ADOLESCENTES

O Lumio AI é destinado exclusivamente a maiores de 18 anos (Cláusula 1 dos Termos de Uso) e não coleta intencionalmente dados de crianças ou adolescentes. Caso tomemos conhecimento de que coletamos dados de um menor de idade, esses dados serão excluídos de nossos sistemas assim que razoavelmente possível.

---

## 10. IDENTIFICADORES, DIAGNÓSTICO E SDKS DE TERCEIROS

O Aplicativo pode utilizar bibliotecas de terceiros (*SDKs*) para funções como diagnóstico de falhas (*crash reporting*) ou métricas agregadas e anônimas de uso, com a finalidade de manter a estabilidade e a qualidade do Serviço.

> *Nota de conformidade: esta cláusula está redigida de forma genérica porque eu não tenho a lista real de SDKs integrados ao Aplicativo. Antes de publicar, substitua este parágrafo por uma lista específica de cada SDK utilizado (ex.: Firebase Crashlytics, Firebase Cloud Messaging para as notificações push), com o que cada um coleta — isso precisa bater exatamente com o formulário de Data Safety do Play Console, categoria por categoria.*

---

## 11. NOTIFICAÇÕES PUSH

Caso você tenha permitido o envio de notificações, utilizamos um identificador de dispositivo (token de notificação push) exclusivamente para entregar a notificação diária. Você pode desativar as notificações a qualquer momento nas configurações do seu dispositivo ou do Aplicativo, sem que isso afete o restante do Serviço.

---

## 12. ALTERAÇÕES A ESTA POLÍTICA

Podemos atualizar esta Política periodicamente para refletir mudanças legislativas, técnicas ou no funcionamento do Serviço. Alterações significativas serão refletidas na data no topo deste documento, e você poderá ser notificado por meio do próprio Aplicativo. O uso continuado do Lumio AI após a publicação das alterações constitui aceitação tácita da nova versão.

---

## 13. CONTATO E ENCARREGADO DE PRIVACIDADE

Dúvidas, solicitações ou exercício dos direitos previstos na Cláusula 8 podem ser dirigidos ao e-mail de suporte oficial cadastrado na ficha da loja no Google Play Console:

* **E-mail de Privacidade/Suporte:** `suporte.lumioai@gmail.com` *(ou o e-mail cadastrado pelo projeto no Play Console)*

Quando a legislação aplicável exigir a designação formal de um responsável pela proteção de dados (por exemplo, um "Encarregado" sob a LGPD ou um "Data Protection Officer" sob o GDPR), faremos essa designação e divulgaremos o contato correspondente.

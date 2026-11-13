# Política de Privacidade — Dose em Dia

**Última atualização:** 11 de novembro de 2026

O Dose em Dia é um diário pessoal de acompanhamento para quem utiliza canetas
de tratamento. Esta política explica, em linguagem simples, quais dados o
aplicativo trata e quais são os seus direitos, em conformidade com a Lei Geral
de Proteção de Dados (LGPD — Lei nº 13.709/2018).

## 1. Quem controla seus dados

Os dados de saúde registrados no aplicativo são inseridos por você e
pertencem a você. O aplicativo não é operado por um serviço de saúde e não
realiza diagnósticos, prescrições ou ajustes de dose.

Enquanto não houver um projeto Firebase configurado e uma conta criada por
você, **nenhum dado sai do aparelho**.

## 2. Dados tratados

O aplicativo pode armazenar, sempre a partir do que você informa:

- nome, e-mail, altura, pesos e meta pessoal;
- medicamentos, doses informadas, datas e locais de aplicação;
- registros de peso, medidas corporais e fotos de progresso;
- sintomas, refeições, hidratação e anotações do diário;
- gastos com o tratamento;
- preferências de lembretes e de segurança.

Não coletamos localização, contatos, microfone, câmera em segundo plano nem
dados de navegação. As fotos são escolhidas por você e salvas apenas na pasta
privada do aplicativo.

## 3. Onde os dados ficam

- **Modo local (padrão):** banco SQLite dentro do armazenamento privado do
  aplicativo, no seu aparelho.
- **Conta opcional:** cópia adicional no Firebase (Google Cloud), vinculada ao
  seu `uid`, protegida por regras que permitem acesso apenas à sua conta.
- **Fotos de progresso:** permanecem somente no aparelho, mesmo com conta.

O Firebase pode processar dados em servidores fora do Brasil. Ao criar a conta,
você autoriza essa transferência internacional nos termos do art. 33 da LGPD.

## 4. Base legal e consentimento

O tratamento em modo local decorre do seu próprio uso do aplicativo. A
sincronização em nuvem depende de **consentimento específico**, solicitado na
tela de criação de conta (art. 7º, I, da LGPD). Você pode revogar o
consentimento a qualquer momento saindo da conta e/ou excluindo-a.

## 5. Compartilhamento

Não vendemos, alugamos nem compartilhamos seus dados com terceiros para
publicidade. O único operador envolvido é o Google Firebase, quando a conta
opcional está ativa. Relatórios em PDF e backups em JSON são gerados **por sua
iniciativa** e compartilhados apenas com quem você escolher.

## 6. Segurança

- Comunicação com o Firebase por HTTPS.
- Regras do Firestore restringem cada usuário à própria árvore de dados.
- Opção de bloqueio por PIN e biometria no aparelho.
- Nenhuma senha é armazenada em texto puro pelo aplicativo; a autenticação é
  feita pelo Firebase Auth.

Nenhum sistema é 100% imune a incidentes. Em caso de incidente relevante,
você será comunicado pelos canais disponíveis.

## 7. Seus direitos

Você pode, a qualquer momento:

- **Acessar e exportar** todos os registros em JSON (Privacidade e dados).
- **Corrigir** qualquer informação nas telas de edição.
- **Apagar** os dados do aparelho (Privacidade e dados → Apagar dados).
- **Excluir a conta e os dados na nuvem** (Conta e nuvem → Excluir conta).
- **Revogar o consentimento** de sincronização saindo da conta.

A exclusão local é imediata e definitiva. A exclusão na nuvem remove os
documentos do Firestore e o usuário do Firebase Auth.

## 8. Retenção

Os dados permanecem enquanto você mantiver o aplicativo ou a conta. Não há
retenção oculta: ao apagar, os registros são removidos. Backups exportados por
você ficam sob sua responsabilidade.

## 9. Crianças e adolescentes

O aplicativo é destinado a pessoas adultas em acompanhamento de tratamento.
Não há coleta intencional de dados de menores de 18 anos sem supervisão
responsável.

## 10. Alterações

Mudanças relevantes nesta política serão refletidas no aplicativo e neste
arquivo, com nova data de atualização.

## 11. Contato

Para exercer direitos ou esclarecer dúvidas, use o canal de suporte informado
na loja de aplicativos ou o e-mail do responsável pelo aplicativo.

---

**Aviso de saúde:** o Dose em Dia é um registro pessoal. Ele não substitui
consulta, diagnóstico ou orientação de profissionais de saúde e não calcula,
recomenda ou ajusta doses.

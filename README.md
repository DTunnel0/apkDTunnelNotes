### 🔥🚀 **DTUNNEL 4.3.10 - OFICIAL** 🔥🚀

1. 🚀 **Novo sistema para pegar o ID do dispositivo**
2. 🚀 **Removido o Prefixo 'Android' do JavaScript**
3. 🚀 **Adicionadas Novas Chamadas de API no HTML**
   - `DtSendNotification.execute(TITLE, MESSAGE, IMAGE_URL)` - Envia uma notificação para sistema nativo do Android.
4. 🚀 **O aplicativo agora envia o nome do usuário atualmente conectado ao painel.**
5. 🚀 **O aplicativo agora envia notificações ao sistema, informando que o dispositivo está online/conectado.**
6. 🚀 **Mais melhorias internas...**

### 🔥🚀 **DTUNNEL 4.3+ - OFICIAL** 🔥🚀

1. 🚀 **Adicionado Modo Avião Automático e Manual**
   - Agora você pode ativar e desativar o modo avião automaticamente ou manualmente, proporcionando mais controle sobre suas conexões.

2. 🚀 **Adicionadas Novas Chamadas de API no HTML**
   - `DtAirplaneActivate.execute()` // Ativa o Modo Avião
   - `DtAirplaneDeactivate.execute()` // Desativa o Modo Avião
   - `DtAirplaneState.execute()` // Retorna ACTIVE ou INACTIVE
   - `DtAppIsCurrentAssistant.execute()` // Retorna ENABLED ou DISABLED
   - `DtGoToVoiceInputSettings.execute()` // Leva para as configurações de assistente
   - `DtAppVersion.execute()` // Retorna a versao atual do app
   - `DtShowMenuDialog.execute()` // Exibe o menu nativo  com ferramentas
   - Aproveite estas novas funções para integrar e controlar o modo avião em sua aplicação de forma mais eficiente.

3. 🚀 **Melhorias na Exibição do IP Local e do Nome da Rede Nativa**
   - Agora, a exibição do IP local e do nome da rede nativa foi aprimorada, proporcionando uma experiência mais clara e precisa.

4. 🚀 **Remoção da Funcionalidade de Atualização de Base via URL**
   - A funcionalidade de atualização de base via URL foi removida para atender aos requisitos da Play Store, que agora exige a instalação de pacotes apenas de fontes conhecidas, aumentando assim a segurança do aplicativo.

5. 🚀 **Melhorias no Modo Avião - Removida a Obrigatoriedade de Ativar o Assistente**
   - Embora ainda seja necessário ativar o assistente para utilizar o modo avião, não há mais a necessidade de forçar o usuário a fazer essa ativação, tornando o processo mais flexível e intuitivo.
   - Agora o app não chama mais o assistante do google.

6. 🚀 **Adicionado um menu com ferramentas**
   - Agora no layout nativo voce um menu com ferramentas.

7. 🚀 **Removido travamentos e crash em config. v2ray**

### 🔥🚀 **DTUNNEL 4.2.8 - OFICIAL** 🔥🚀
1. 🔄 **ADICIONADO SERVICO DE PING**
2. 🛠 **SUPORTE A CONFIGURAÇÕES V2AY JSON**
3. 🛠 **SISTEMA INTERNO DE VERIFICAÇÃO DE REDE**
4. 🛠 **MELHOR SUPORTE A PAYLOADS COM SPLITS**

### 🔥🚀 **DTUNNEL 4.2.7 - OFICIAL** 🔥🚀

1. 🛠 **CORREÇÃO SOBRE O APP NOCIVO**

2. 🛠 **MELHORIAS INTERNAS NO V2RAY**

3. 🧹 **REMOVIDO ALGUMAS LIBS DESNECESSÁRIAS**

4. 🔄 **Implementação de melhorias internas para otimização do desempenho.**

### 🔥🚀 **DTUNNEL 4.2.6 - OFICIAL** 🔥🚀

1. 📱 **Adicionado suporte ao Android 14 (SDK 34).**

2. 🧹 **Remoção do cache do CheckUser para otimização.**

3. 🛠 **Correção no Limiter para dispositivos Android 14.**

4. 🌐 **Remoção do domínio dt.com.br.**

5. ⚡️ **Inclusão do WAKELOCK nos modos de conexão para aumentar a eficiência.**

6. 🐞 **Correção de bug no Android 14: o aplicativo não trava ao reconectar/parar pela notificação.**

7. ⏰ **Reinício do timer da notificação após uma reconexão.**

8. 📶 **Adição do IP local e nome da rede no layout nativo.**

9. ✉️ **Correção e aprimoramento nas mensagens.**

10. 🛠 **Implementação de filtro de configurações pelo nome da rede.**

11. 🔊 **Inclusão de alertas sonoros para alguns estados da conexão.**

12. ⚡️ **Adicionado suporte a PORTA rotate.**

13. 🛠 **Foi feita uma melhoria significativa no sistema de rotate.**

14. 🛠 **Correções no modo de conexão OPENVPN.**

15. 🔄 **Implementação de melhorias internas para otimização do desempenho.**

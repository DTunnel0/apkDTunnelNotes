### 🔥🚀 **DTUNNEL 4.3.16 - LANÇAMENTO OFICIAL** 🔥🚀

#### Bug Fixes:
- **Correção ao copiar log:**  
  Agora o aplicativo não vibra infinitamente ao copiar logs.

#### Novidades:
- **Logs no modo de conexão v2ray (Beta):**  
  Foram adicionados logs ao modo de conexão v2ray.
  
- **Persistência de logs:**  
  Os logs agora permanecem salvos mesmo quando o app é fechado.

#### Melhorias e Novas Funcionalidades:
- **`custom_split_delay` adicionado:**  
  É possível configurar delays personalizados para splits.  
  *Exemplo:* `[custom_split_500]` define um delay de 500ms.
  
- **Otimização dos splits:**  
  Todos os métodos de split foram aprimorados para garantir melhor desempenho.
- **Ping aprimorado:**  
  Ajustes no sistema de ping proporcionam maior precisão e estabilidade.
  
- **Correção na obtenção do host:**  
  Problemas na obtenção do host foram resolvidos.
  
- **Logs preservados ao conectar:**  
  Agora os logs não são mais limpos automaticamente ao clicar em "Conectar".
  
- **Outras melhorias internas:**  
  Diversos ajustes e refinamentos para uma experiência mais fluida e estável.


### 🔥🚀 **DTUNNEL 4.3.14 - LANÇAMENTO OFICIAL** 🔥🚀

- **Melhorias ao salvar device:**  
  Aperfeiçoamento no processo de armazenamento do device no sistema DTunnel.

- **Melhorias ao salvar token FCM:**  
  Otimização no salvamento do token do Firebase Cloud Messaging no sistema DTunnel.

- **Obtenção da localização do usuário:**  
  Agora o aplicativo coleta a localização do usuário (necessita permissão explícita).

- **Outras melhorias internas:**  
  Diversos ajustes e refinamentos para garantir uma experiência mais fluida e estável.

### 🔥🚀 **DTUNNEL 4.3.13 - ATUALIZAÇÃO EM TEMPO REAL** 🔥🚀

#### 🆕 **Novidades desta versão**:

1. **Atualização em Tempo Real**:
   - O aplicativo agora atualiza automaticamente caso o **token gerado pelo Firebase** esteja válido e salvo no sistema de notificações do DTunnel.  
   - Essa funcionalidade garante que as informações do sistema estejam sempre sincronizadas sem a necessidade de atualizações manuais.  

2. **Melhorias em Configurações e Textos**:
   - **Configurações do aplicativo** ajustadas para maior clareza e facilidade de uso.  
   - **Textos do aplicativo** revisados para melhor comunicação com o usuário.  

3. **Otimizações Internas**:
   - Ajustes para melhorar a **estabilidade e desempenho geral**.  
   - Correções de bugs menores relatados pela comunidade.  

### 🔥🚀 **DTUNNEL 4.3.12 - LANÇAMENTO OFICIAL** 🔥🚀

#### 🆕 **Novidades desta versão**:
1. **Nova funcionalidade de CDN**:
   - Agora o aplicativo **obtém automaticamente uma lista de CDNs do sistema**, garantindo maior flexibilidade.  
   - Caso o vendedor tenha cadastrado uma lista de CDNs ela sera utilizada.  
   - `[cdn]`: Utiliza a **primeira CDN da lista** como padrão.  
   - `[cdn_rotate]`: Implementada a **rotação automática de CDNs** para alternar entre as opções disponíveis.  
   - `[cdn_random]`: Adicionada a funcionalidade de **seleção aleatória de CDNs**, permitindo maior dinamismo.  

2. **Payload aprimorada**:
   - Novas chaves adicionadas para suportar as funcionalidades de CDN diretamente na payload.  

3. **Correções e melhorias**:
   - 🚀 **Correção de Bug**: Problema resolvido em que o aplicativo travava ao reconectar com a opção "visto por último" ativada.  
   - 🚀 **Melhorias**: Aperfeiçoamento do alerta de limite excedido para uma experiência mais eficiente.  

4. **Outras melhorias gerais**:
   - Otimizações internas para garantir **maior estabilidade e desempenho** do aplicativo.  
   - **Correções menores** reportadas pelos usuários para melhorar a experiência geral.  

🎉 **Atualize agora e aproveite todas as novidades!**

### 🔥🚀 **DTUNNEL 4.3.11 - LANÇAMENTO OFICIAL** 🔥🚀

1. 🚀 **Correção de Bug**: Problema resolvido em que o aplicativo travava ao reconectar com a opção "visto por último" ativada.
2. 🚀 **Melhorias**: Aperfeiçoamento do alerta de limite excedido para uma experiência mais eficiente.

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

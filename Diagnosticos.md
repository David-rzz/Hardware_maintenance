# 🛠️ **Diagnósticos de erros mais comuns** 
 🕵️ Um guia de como encontrar e solucionar possíveis causas de problemas em seu computador 
 ---
 
Abordaremos nesse guia, algumas situações fictícias de hardware apresentando defeitos e descobriremos seus possíveis causadores. 

---
Índice de problemas 🩺:

 - 🔌 Problemas de inicialização
 - 📽️ Problemas de vídeo
 - 🔊 Problemas de som
 - 🔥 Problemas de superaquecimento
 - 🌐 Problemas de rede


    ---
 ###  **🔌 Problemas de inicialização**
 Se seu computador não dá nenhum sinal de vida, sugiro que confira os seguintes componentes:
 - Certifique-se de que o cabo de força da fonte de alimentação está bem fixo;
 - Confira se os componentes estão bem fixados à placa-mãe.

**Sintomas:**
  - Nenhuma luz acende;
  - Ventoinhas (Fans) não giram;
  - Não emite nenhum bip.
    
  **Possíveis causas:**
  - Fonte de alimentação com defeito;
  - Problemas com a memória-RAM;
  - Botão power com defeito;
  - Superaquecimento.
    
**Fase de testes iniciais:**
   - Teste a fonte com um clipe de papel para descartar problemas nela;
   - Limpe os contatos do módulo de memória-RAM com uma borracha e tente ligar novamente;
   - Caso tenha mais de um módulo de RAM, tente ligar com um de cada vez;
   - Para verificarmos se o botão power está com defeito, use uma chave de fenda para fazer a ligação direta pela placa-mãe.

**Se seu computador liga mas desliga logo em seguida:**
- Um bip curto significa que o POST foi realizado com sucesso;
- Vários bips indicam alguma falha ao iniciar - verifique o manual da placa-mãe;
- Realize a troca da bateria CMOS da BIOS;
- Verifique se as fans estão funcionando corretamente - o computador desliga em casos de superaquecimento.

  ---
  ### **📽️ Problemas de vídeo**
  Se você está enfrentando problemas relacionados à exibição da imagem, este guia pode ser muito útil.

**Sintomas:**
  - Computador liga mas não exibe vídeo;
  - Problemas de resolução de imagem;
  - Artefatos no vídeo;
  - Tela azul em jogos.

**Possíveis causas:**
- Cabo de vídeo mal encaixado;
- Placa de vídeo com defeito;
- Problemas com monitor;
- Configurações de resolução erradas.

**Fase de testes iniciais:**
- Verifique a conexão do cabo de vídeo, normalmente HDMI ou VGA;
- Se seu computador possuir placa de vídeo, o cabo deve ser conectado à ela e não na placa-mãe;
- Tente trocar o cabo HDMI;
- Verifique se seu monitor está funcionando corretamente conectando ele à outro dispositivo;
- Verifique se a placa de vídeo está corretamente conectada;
- Caso não possua placa de vídeo, certifique-se que seu processador possui vídeo integrado;
- Artefatos na tela geralmente indicam problemas com VRAM, consulte um profissional;
- Tela azul pode ser ocasionada por superaquecimento da placa de vídeo.

**Se seu computador exibe vídeo mas com problemas de resolução:**
- Clique com o botão direito do mouse na área de trabalho e selecione "configurações de exibição";
- A partir dessas configurações você poderá alterar coisas como resolução e configurar mais de um monitor;
- Fonte de alimentação fraca pode prejudicar elementos gráficos em casos de placa de vídeo dedicada;
- Tente reinstalar os drivers da placa de vídeo.

**Notas**
- Atualize mensalmente os drivers da placa de vídeo;
- Realize limpezas preventivas para evitar acúmulo de poeira na placa de vídeo;
- Utilize sites oficiais da NVIDIA ou AMD para baixar os drivers;
- Utilize softwares como MSI Afterburner ou HWMonitor para monitorar a temperatura e uso da placa de vídeo;
- Alguns monitores podem possuir drivers próprios, verifique no site da fabricante.

> 💡 **Dica Extra:**  
> Pressione <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> para reiniciar rapidamente os drivers de vídeo.

  ---
### **🔊 Problemas de som**
Se você está lidando com algum tipo de problema relacionado ao som ou dúvidas de como configurar dispositivos, confira este guia:

**Sintomas:**
- Dispositivo de som conectado mas sem som;
- Fones de ouvido bluetooth não conectam;
- Dúvidas para configurar dispositivos de som;
- Som distorcido ou com ruídos.

**Possíveis causas:**
- Cabos conectados de forma errada;
- Drivers desatualizados ou corrompidos
- Conflito de dispositivos, no caso de haver mais de um;
- Problemas no dispositivo de áudio.

**Fase de testes iniciais:**
- Verifique se os cabos do dispositivo de som estão conectados corretamente;
- O som pode sair pelas entradas P2 (caixas de som analógicas), HDMI (televisores/monitores) ou USB (headsets digitais);
- Atualize os drivers de som ou reinstale-os pelo site do fabricante (Realtek, Intel, etc);
- Teste os dispositivos de som em outro aparelho para descartar falha neles;
- Use outra entrada USB ou P2 para descartar mau contato;
- Abra as configurações de som do Windows/Linux e verifique se o sistema está enviando o áudio para o dispositivo correto.

**Se o problema for relacionado ao bluetooth:**
- Reinicie o bluetooth e tente novamente;
- Remova o dispositivo e pareie de novo;
- Verifique se o headset está em modo de pareamento;
- Se houver mais de uma saída de áudio configurada, defina a padrão pelas configurações;
- Utilize softwares como Voicemeeter (Windows) ou Pulseaudio/Pipewire (Linux) para configurar dois dispositivos de som simultâneos.
> 💡 **Dica Extra:**  
> Pressione <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> para reiniciar rapidamente os drivers de vídeo.— isso pode resolver também alguns casos em que o som via HDMI não funciona.

---
### **🔥 Problemas de superaquecimento**
Se seu computador está superaquecendo mesmo em tarefas simples, pode ser um indicativo de problemas que devem ser resolvidos agora para evitar danos aos componentes no futuro.

**Sintomas:**
- Temperatura dos componentes altas;
- Cabo de alimentação quente;
- Desligamentos ou reinicializações repentinas;
- Tela azul ou travamentos.

**Possíveis causas:**
- Poeira acumulada nos componentes;
- Fans com defeito ou mal posicionadas;
- Componente com defeito;
- Fonte de alimentação de baixa qualidade;
- Pasta térmica ressecada;
- Mau planejamento do fluxo de ar no gabinete;
- Overclock mal planejado;

**Fase inicial de testes:**
- Monitore a temperatura do computador com softwares como MSI Afterburner por exemplo;
- Realize uma limpeza completa no gabinete, fans, dissipadores e filtros de ar;
- Perceba se existe um componente em específico que esteja superaquecendo - Ex. Apenas CPU ou GPU;
- Confira a qualidade da sua fonte de alimentação e se a potência fornecida por ela é o suficiente para seu setup;
- Realize a troca da pasta térmica da CPU;
- Certifique-se que o fluxo de ar no gabinete está sendo eficiente e que todas as fans estão girando;
- Depois de um overclock, a refrigeração atual pode se tornar insuficiente;

> 💡 **Dica Extra:**
> Se o superaquecimento ocorrer apenas em jogos ou softwares pesados, verifique o uso de GPU/CPU. O problema pode estar em overclock automático do fabricante (turbo boost) exigindo uma refrigeração melhor do que a instalada.

---

     
     
     
     

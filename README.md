# Agente-dia-das-mulheres
Este projeto implementa um agente automatizado que envia e-mails personalizados às funcionárias da empresa no Dia Internacional da Mulher.

A solução utiliza Azure Logic Apps para orquestração do fluxo e Azure OpenAI para gerar mensagens corporativas personalizadas. O agente coleta a lista de colaboradoras, cria textos únicos para cada pessoa e envia automaticamente os e-mails via Outlook 365.

O objetivo é reduzir trabalho manual, padronizar a comunicação institucional e garantir que todas as funcionárias recebam reconhecimento no dia 8 de março.

## Objetivo

Automatizar e personalizar mensagens corporativas de homenagem às colaboradoras, reduzindo trabalho manual do RH.

## Arquitetura

-   Azure Logic Apps
-   Azure OpenAI ( GPT-4o-mini)
-   Outlook 365 Connector

## Fluxo

1.  Trigger recorrente (8 de março)
2.  Geração de mensagem personalizada via OpenAI
3.  Envio de e-mail para cada colaboradora
4.  Log de execução

## Prints 

![alt text](image-1.png)
!![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)

## Referencias
- [Microsoft Learn](https://learn.microsoft.com/)
- [Azure Community](https://techcommunity.microsoft.com/azure)
- [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/)
 [Azure AI Foundry](https://learn.microsoft.com/azure/ai-studio/)

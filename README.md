# ClusterWhatsApp
  
## Clusterização de Conversas de WhatsApp.  
Separar em grupos de acordo com a similidade das conversas. O número de cluster é definido pela variável "k" que deve ser definidade pelo usuário. É gerado o "gráfico de cotovelo" para se surgerir um valor otimizado, mas maioria das simulações não é gerado um valor satisfatório.
  
  
### Necessário ser no formato PT-BR  
Conversas no formato do Aplicativo no idioma PT-BR.  
"Conversa do WhatsApp com ___________ .txt"  
DD/MM/AA HH:MM - Autor: Mensagem  
  
Diferente do formato no idioma ENG.  
"WhatsApp Chat with _______ .txt"  
MM/DD/YY, HH:MM - Author: Message  
  
Exemplo com k = 3.  
  
|               Título               |    Cluster    |
| ---------------------------------- | ------------- |
| Conversa do WhatsApp com Escritóio |       0       |
| Conversa do WhatsApp com João      |       1       |
| Conversa do WhatsApp com Maria     |       1       |
| Conversa do WhatsApp com Pizzaria  |       2       |

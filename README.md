# Agente_de_Saude
Chatbot de Agente de Saúde construído no Colab usando Genai, Google Search e Google Maps.

Funcionamento:

1. O chatbot oferece 3 opções:
   
1 - Emergência médica
2 - Consulta médica
3 - Outros serviços médicos

3. A depender da escolha do paciente (usuário), que o chatbot verifica se foi correta, o chatbot responde uma mensagem reconfortante / motivadora diferente.

4. O chatbot pergunta qual especialidade médica ou problema de saúde. E segue para a próxima pergunta somente após alguma resposta do paciente.

5. O chatbot pergunta qual seria a localidade (cidade/rua/bairro). E segue para a próxima pergunta somente após alguma resposta do paciente.

6. O chatbot pergunta se o paciente tem plano de saúde e se sim, pede para informar qual. 

7. Informando ou não no plano de saúde, o chatbot chama o Agente Buscador de Locais de Saúde passando as informações que o usuário forneceu.

8. O Agente é configurado para usar o Google Search e o Google Maps. Além de outros detalhes como resposta clara e direta, para uma pessoa que está com pressa. E também passando um padrão de resposta. Esse prompt foi testado e aprimorado várias vezes.

9. O Agente responde e o chatbot exibe a resposta formatada. Perguntando em seguinda se o paciente foi atendido. 

10. Se o paciente responder que não, então o chatbot pergunta se deseja fazer um novo atendimento. E tendo não de novo como resposta, o chatbot continua no mesmo atendimento e solicita mais detalhes para chamar o Agente Buscador de Locais de Saúde novamente e oferecer outra resposta. 

11. Se o paciente desejar um novo atendimento, o chatbot volta ao passo 1o.

12. Senão, se o paciente não desejar um novo atendimento, o chatbot se despede.

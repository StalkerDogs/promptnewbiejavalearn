# promptnewbiejavalearn
Projeto ajudar alunos iniciantes a testar seus códigos, ter um feedbak amigável sobre o erro, pedir explicação sobre o código e coisas do tipo estruturando orientações de conversação entre IA e Usuário através de um prompt aplicado no deepseek. 
O script define um interpretador de código altamente restrito e estruturado, projetado para guiar o usuário na execução de códigos de programação específicos. Aqui estão suas funcionalidades e vantagens para a aprendizagem de programação:

### **Funcionalidades:**
1. **Configuração Inicial Personalizada:**
   - Pergunta ao usuário sobre sua língua nativa, nome e linguagem de programação desejada.
   - Configura a sintaxe correta de comentários e entrada/saída de dados conforme a linguagem escolhida.

2. **Execução Estrita de Código:**
   - Apenas interpreta códigos válidos na linguagem especificada.
   - Bloqueia qualquer entrada que não seja código ou comentários.
   - Requer que comandos de saída sejam explicitamente chamados.

3. **Simulação de Entrada de Dados:**
   - Pausa a execução para aguardar entradas do usuário quando necessário.
   - Simula prompts para entrada de dados.

4. **Mensagens de Erro Didáticas:**
   - Exibe mensagens de erro originais e traduzidas para a língua do usuário.
   - Fornece sugestões de correção numeradas e ordenadas.

5. **Controle de Fluxo e Correção de Erros:**
   - Para a execução ao encontrar um erro e solicita correção.
   - Verifica a correção e prossegue a partir do ponto onde parou, se válida.
   - Reaplica as regras caso o erro persista.

6. **Interação Exclusiva via Comentários:**
   - Apenas responde a perguntas formatadas como comentários.
   - Gera exemplos para o usuário entender como perguntar corretamente.

7. **Restrições para Foco no Código:**
   - Não responde perguntas fora do contexto de programação.
   - Proíbe a mudança de comportamento durante a execução.

---

### **Vantagens para a Aprendizagem de Programação:**
1. **Foco Total no Código:**
   - Evita distrações, pois só responde a entradas formatadas corretamente.
   - Garante que o usuário pratique a sintaxe correta da linguagem.

2. **Simulação Realista de Interpretadores e Compiladores:**
   - Ensina o usuário a lidar com erros como em um ambiente real de programação.
   - Ajuda a entender como linguagens lidam com entradas, saídas e erros.

3. **Desenvolvimento da Autocorreção e Depuração de Código:**
   - O usuário deve corrigir seus próprios erros com base nas sugestões fornecidas.
   - Incentiva o raciocínio lógico para entender mensagens de erro.

4. **Adaptação a Diferentes Linguagens de Programação:**
   - Guia o usuário na configuração correta para diferentes linguagens.
   - Ajuda a compreender diferenças sintáticas entre linguagens.

5. **Interação Didática e Controlada:**
   - O formato estruturado impede respostas vagas ou incorretas.
   - Força o aprendizado por tentativa e erro dentro de um ambiente seguro.

6. **Reforço da Escrita Correta de Código:**
   - Exige a chamada explícita de funções de saída para ver resultados.
   - Ensina boas práticas de programação ao não permitir execução incorreta.

Esse tipo de interpretador é ideal para iniciantes, pois força o aprendizado estruturado e a prática correta de escrita de código, além de ensinar a lidar com erros de forma eficiente.

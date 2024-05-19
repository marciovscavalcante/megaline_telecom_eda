# AVALIAÇÃO DE DESEMPENHO DOS PLANOS DE SERVIÇOS:
## Impacto na Receita e Implicações para Estratégias de Marketing

Este projeto visa analisar os dados dos serviços da empresa de telecomunicações Megaline (Chamadas (ligações), Mensagens (SMS) e Internet (dados)) a fim de demonstrar qual dos seus planos de assinatura, "Surf" e "Ultimate", gera mais receita e assim ajustar o orçamento de publicidade.

---

**Bibliotecas utilizadas:**

- pandas
- numpy
- scipy
- matplotlib
- seaborn

---

## CONCLUSÃO:
### COMPORTAMENTO DOS USUÁRIOS

#### CHAMADAS:
Ambos os planos têm uma média de uso de minutos em torno de 400 minutos, indicando um equilíbrio nesse aspecto. O plano Surf tem um volume maior de minutos utilizados, mas as médias permanecem semelhantes entre os dois planos.

#### MENSAGENS:
Os usuários do plano Surf usam significativamente mais mensagens do que os usuários do plano Ultimate, apesar das médias serem semelhantes.

#### INTERNET:
Assim como nas chamadas, o uso de dados de internet é significativamente maior pelos usuários do plano Surf, apesar das médias serem semelhantes.

#### RECEITA:
As receitas de ambos os planos aumentam gradualmente ao longo do ano, sendo que a receita do plano 'Ultimate' é consistentemente maior que a do plano 'Surf', chegando a dobrar a partir do 2º semestre.

---

### TESTES DE HIPÓTESES:

- **Teste de Hipótese 1:** Realizamos o Teste T Student com amostras independentes neste caso e o resultado do teste **REJEITOU** a hipótese nula, indicando que as receitas médias dos usuários dos planos Ultimate e Surf são **DIFERENTES**, confirmando a observação de que a receita do plano 'Ultimate' é majoritariamente maior que a do plano 'Surf'.

- **Teste de Hipótese 2:** Realizamos o Teste T Student com amostras independentes neste caso e o resultado do teste também **REJEITOU** a hipótese nula, indicando que a receita média dos usuários da área de NY-NJ **É DIFERENTE** da receita média das demais regiões.

---

### INSIGHTS:

Analisando os três serviços oferecidos pela empresa dentro de dois planos distintos, chegamos à conclusão de que os usuários do plano 'Surf' demandam muito mais da empresa, no entanto, geram menos receita do que os usuários do plano 'Ultimate'.

Com estes dados, a equipe de marketing pode ajustar seus orçamentos para favorecer o plano 'Ultimate', que gera mais receita e demanda menos serviço. A empresa pode se valer também dos dados e criar, por exemplo, novos planos intermediários e/ou ainda ajustar os planos atuais.

Essas conclusões são fundamentais para entender as tendências de comportamento dos usuários de cada plano e podem orientar novas estratégias na adequação nos produtos e serviços em curso e no desenvolvimento de novos produtos para a empresa.

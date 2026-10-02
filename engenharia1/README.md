### Trecho 1: O Conceito de Engenharia de Software

> What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years? The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.” “Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create. Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

**Comentário:**

O ponto principal desse trecho é mostrar a diferença entre só escrever código e fazer engenharia de verdade. Programar é resolver um problema agora; engenharia de software é garantir que esse sistema continue funcionando, fácil de manter e seguro daqui a anos, quando o projeto crescer e outras pessoas forem mexer.

A comparação com a engenharia tradicional é perfeita: conforme o software passou a controlar coisas essenciais do nosso dia a dia, a gente não pode mais tratar o desenvolvimento sem rigor. É a diferença entre só fazer funcionar e construir algo que dure.

---

### Trecho 2: Programming Over Time

> Programming Over Time We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers. One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation? The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:
> 
> - **Time and Change:** How code will need to adapt over the length of its life
> - **Scale and Growth:** How an organization will need to adapt as it evolves
> - **Trade-offs and Costs:** How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

**Comentário:**

A ideia forte desse trecho é a definição de engenharia de software como "programação integrada ao tempo". Não se trata apenas de criar uma solução que funcione hoje, mas de gerenciar todo o ciclo do código ao longo dos anos, incluindo mudanças, crescimento da equipe e manutenção. Os três pilares citados — tempo, escala e as trocas necessárias em cada decisão — resumem bem o desafio real da área: fazer escolhas sustentáveis para que o sistema não vire um problema no futuro.

---

### Exemplos de Trade-offs

1. **Velocidade de Entrega vs. Qualidade do Código (Débito Técnico)**
   - **A troca:** Entregar uma funcionalidade rápida para cumprir um prazo apertado.
   - **O trade-off:** Você ganha tempo agora, mas abre mão da organização do código. No futuro, vai gastar mais tempo corrigindo bugs ou refatorando.

2. **Desempenho em Memória vs. Uso de Processamento**
   - **A troca:** Fazer o cache de resultados de consultas pesadas na memória RAM para a aplicação responder instantaneamente.
   - **O trade-off:** A resposta fica ultra rápida, mas o consumo de memória RAM aumenta consideravelmente.

3. **Software Próprio (Sob Medida) vs. Software Pronto (SaaS)**
   - **A troca:** Desenvolver um sistema do zero totalmente adaptado ao seu processo.
   - **O trade-off:** Você ganha flexibilidade total, mas abre mão de tempo e orçamento em comparação a assinar algo pronto.

---

### Minhas Contribuições no Projeto (API)

- Código base inicial para o grupo ter uma ideia do que precisávamos.
- Histórico para a IA ter um parâmetro de diálogo com o cliente.
- Filtros para facilitar a busca por imóveis no CSV.

### Habilidades Aprendidas

- Integração de IA local (Ollama) em bots.
- Armazenamento e persistência de informações via código.
- Leitura e estruturação de bases de código mais avançadas.






============================================================================================

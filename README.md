# 🧪 Test Driven Development

Repositório destinado à aplicação dos estudos sobre TDD - principalmente quanto ao curso Fullcycle.

**📍Objetivo:** Aprender a construir testes sólidos para fortalecer a aplicação e utilizá-los com maior frequência.

**🗃️ Utilidade dos testes:**

- Detectar regressões: impedir que sejam introduzidos bugs em funcionalidades previamente corretas.
- Independência de falhas humanas: ao independer de testes manuais e repetitivos, os testes automatizados se tornam menos propícios a falhas humanas.
- Percepção de cobertura: testes automatizados apontam áreas desfalcadas de testes e vulneráveis a erros.


## ⚛️ Testes unitários 

Focados em verificar o comportamento de pequenas unidades do código, como funções, métodos ou classes. Eles são escritos para testar uma funcionalidade específica de forma isolada.

- ao testar componentes indivindualmente, fica mais fácil identificar exatamente onde um erro está ocorrendo.
- servem como uma forma de documentação que demonstra como cada unidade deve se comportar
- facilita a refatoração pois alertam quanto a possíveis quebras
- garante que as entradas e saídas das funções permaneçam consistentes

## 🧩 Testes de integração 

Verificam a interação entre diferentes módulos ou componentes do sistema. O objetivo é assegurar que, quando combinados, esses componentes continuem funcionando corretamente.

- confirma que a comunicação entre módulos está funcionando conforme o esperado
- identifica compatibilidade entre diferentes partes do sistema ou com serviços externos
- garante que os dadosfluem corretamente através dos diferentes componentes
- auxilia a identificar falhas na integração com banco de dados, sistemas de arquivos ou serviços de terceiros
- captura problemas na troca de informações entre módulos, como chamadas de API malformadas ou contratos quebrados

## 💯 Testes e2e 

Simulam o real comportamento do usuário, testando o sistema completo desde a interface até o backend e vice-versa. Eles verificam todos os componentes do sistema funcionam juntos em um ambiente que replica o de produção.

- assegura que o software atende às expectativas do usuário final
- confirma que processos essenciais como cadastro, login ou compras, funcionam sem problemas
- testa o sistema em condições próximas ao uso real, incluindo possíveis interações complexas
- identifica problemas que só surgem quando todos os componentes estão operando juntos
- ajuda a revelar inconsistências ou mal-entendidos nos requisitos do sistema.
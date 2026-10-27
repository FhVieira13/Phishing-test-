# Simulação de Phishing com Kali Linux

## Sobre o projeto

Projeto desenvolvido como parte do desafio de cibersegurança da Digital Innovation One (DIO), com o objetivo de compreender o funcionamento de páginas de autenticação fraudulentas e os riscos associados a ataques de phishing.

O laboratório utiliza o Kali Linux para estudar uma simulação de página de login em ambiente de rede privada.

## Objetivos

- Compreender o funcionamento do phishing.
- Estudar o uso do Social-Engineer Toolkit (SEToolkit).
- Analisar os elementos visuais de uma página de autenticação.
- Documentar os resultados de um teste controlado.
- Identificar medidas de prevenção contra o roubo de credenciais.

## Ferramentas e ambiente

- Kali Linux
- Social-Engineer Toolkit (SEToolkit)
- Navegador web
- Ambiente de virtualização e rede de laboratório
- GitHub para documentação

## Evidências do teste

A captura de tela demonstra uma página de login acessada por um endereço IP privado (`172.16.0.98`).

Durante a análise, foram observados:

- Campos para identificação do usuário e senha.
- Botão de acesso à conta.
- Mensagem informando uma falha de autenticação.
- Acesso por HTTP sem indicação de conexão segura no navegador.

A aparência de uma página não é suficiente para confirmar sua legitimidade. O endereço acessado e o contexto da autenticação também devem ser verificados.

## Análise técnica

O phishing utiliza páginas ou mensagens fraudulentas para induzir pessoas a fornecer informações confidenciais.

Em um laboratório controlado, é possível analisar o comportamento de uma página de login e verificar como informações de teste são processadas, sem utilizar contas reais ou coletar credenciais de terceiros.

A mensagem de erro exibida não comprova, isoladamente, que houve captura de dados.

## Recomendações de segurança

- Conferir o endereço do site antes de inserir credenciais.
- Utilizar autenticação multifator.
- Não acessar páginas de login por links suspeitos.
- Evitar inserir dados pessoais em páginas não verificadas.
- Utilizar somente contas fictícias em testes de laboratório.

## Conclusão

A atividade permitiu observar elementos de uma página de autenticação simulada e refletir sobre os riscos do phishing e a importância da conscientização em segurança da informação.

Os testes devem permanecer restritos a ambientes autorizados e controlados.

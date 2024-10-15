<body>
    <h1>Documentação do Projeto</h1>
    <h2>Cnh.java</h2>
    <p>
        A classe <strong>Cnh</strong> representa a Carteira Nacional de Habilitação (CNH) com seus atributos e métodos. Esta classe contém informações como o número da CNH, nome do titular, pontos acumulados, data de expiração e status da CNH.
    </p>
    <h2>CnhRepository.java</h2>
    <p>
        A classe <strong>CnhRepository</strong> é responsável por fornecer uma lista de CNHs para serem processadas. Ela simula um repositório de dados, retornando uma lista de objetos <strong>Cnh</strong> pré-configurados.
    </p>
    <h2>DroolsApplication.java</h2>
    <p>
        A classe <strong>DroolsApplication</strong> executa o motor de regras Drools para processar uma lista de CNHs. Ela carrega as regras, insere as CNHs na sessão e dispara todas as regras definidas no arquivo <strong>rules.drl</strong>.
    </p>
    <h2>Status.java</h2>
    <p>
        A enumeração <strong>Status</strong> define os possíveis estados de uma CNH, incluindo se ela está válida, inválida ou ainda não processada.
    </p>
    <h2>kmodule.xml</h2>
    <p>
        O arquivo <strong>kmodule.xml</strong> configura o módulo de conhecimento do Drools, especificando a base de regras e as sessões que serão utilizadas durante a execução.
    </p>
    <h2>rules.drl</h2>
    <p>
        O arquivo <strong>rules.drl</strong> contém as regras de negócios que serão aplicadas às CNHs, verificando expiração, pontos acumulados e definindo o status final da CNH.
    </p>
    <h2>AppTest.java</h2>
    <p>
        A classe <strong>AppTest</strong> contém um teste unitário simples usando o JUnit para validar a infraestrutura de testes.
    </p>
</body>
</html>
"# drools" 
"# drools" 

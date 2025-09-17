INTEGRANTES: 
1 - GABRIEL TRUSNOVEC MATEUS / RM: 550873
2 - OTAVIO ANTÔNIO DE LIMA KESAN / RM: 565830
3 - JULIVAN WAGNER AMORIM FILHO / RM: 559030
4 - VINICIUS FRANÇA COVIELLO / RM: 557988
5 - OLIVIER VIRTHE / RM: 98585

ALTERADO O CÓDIGO PARA O CÓDIGO MAIS ATUAL E COM MAIS FUNCIONALIDADES, COMO:
1. Inicialização automática de dados de exemplo no banco de dados ao iniciar a aplicação.
2. Criação de usuários padrão (admin e user) caso não existam, garantindo acesso inicial ao sistema.
3. Adição dos repositórios UsuarioRepository e PasswordEncoder como dependências para manipulação de usuários e senhas seguras.
4. Inserção de robôs logísticos com diferentes modelos, status e localizações.
5. Geração de eventos sensoriais simulados para cada robô, com tipos e leituras variadas.
6. Geração de entregas simuladas para robôs ativos, incluindo lógica de origem, destino, status, datas, distância e observações.
E FEITOS COMENTARIOS DAS DIFERENÇAS PRINCIPAIS NO CÓDIGO, SENDO ELES NOS ARQUIVOS:
- DataInitializer.java
- CorsConfig.java

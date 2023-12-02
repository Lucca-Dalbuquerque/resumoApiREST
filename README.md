 # Api REST e RESTFul

    API REST é uma forma de interface de programação de aplicativos que segue os princípios da arquitetura REST. Ele usa o protocolo HTTP para permitir a comunicação e troca de dados entre diferentes programas pela Web. A arquitetura REST é baseada em recursos identificados por URLs. Cada recurso pode ser acessado por meio de um conjunto definido e padronizado de operações sem estado (representadas por verbos HTTP).

    Uma implementação RESTful é uma API que segue os princípios arquitetônicos REST de forma mais completa e rigorosa. Ele atende a outros padrões, como interface unificada, cliente sem estado e operações baseadas em recursos. A interface unificada estabelece um conjunto de regras para a interação entre cliente e servidor, incluindo a identificação de recursos, sua operação através de representações correspondentes e a descoberta automática de recursos através de links hipermídia.
    Um cliente sem estado ocorre quando cada solicitação do cliente contém todas as informações necessárias para realizar a solicitação, sem depender de nenhum contexto armazenado no servidor. Operações baseadas em recursos significam que cada solicitação do cliente opera em um recurso específico identificado pela URL.



## Diferenças entre REST e RESTFul

    API REST e RESTful representam os mesmos princípios, mas a diferença está apenas na sintaxe. Os sistemas que usam princípios REST são chamados de RESTful. REST é uma arquitetura web, um conjunto de princípios, regras e restrições, enquanto RESTful é um sistema específico que aplica conceitos REST. Uma API RESTful é uma implementação mais completa e rigorosa desses princípios, aderindo a padrões adicionais, como interfaces unificadas, clientes sem estado e operações baseadas em recursos.

## HTTP verbs

    Os verbos HTTP são usados para indicar a ação que deve ser realizada em um recurso. Os principais verbos HTTP são GET, POST, PUT e DELETE. O verbo GET é usado para recuperar informações de um recurso. O verbo POST é usado para enviar informações para um recurso. O verbo PUT é usado para atualizar um recurso existente. O verbo DELETE é usado para excluir um recurso.

## HTTP Status Code

    Os códigos de status HTTP são usados para indicar o resultado de uma solicitação HTTP. Eles são divididos em cinco classes, cada uma representando uma categoria geral de resposta. Essas são as cinco classes de códigos: respostas informativas (100-199), respostas bem-sucedidas (200-299), mensagens de redirecionamento (300-399), respostas de erro do cliente (400-499) e respostas de erro do servidor (500-599).  Alguns dos códigos de status mais comuns incluem:

    200 OK: A solicitação foi bem-sucedida.
    201 Created: A solicitação foi bem-sucedida e um novo recurso foi criado como resultado.
    204 No Content: Não há conteúdo para enviar para esta solicitação, mas os cabeçalhos podem ser úteis.
    400 Bad Request: A solicitação não pôde ser entendida ou foi malformada.
    401 Unauthorized: A solicitação requer autenticação do usuário.
    403 Forbidden: O servidor entendeu a solicitação, mas se recusa a autorizá-la.
    404 Not Found: O servidor não pode encontrar o recurso solicitado.
    500 Internal Server Error: O servidor encontrou um erro inesperado que impediu a conclusão da solicitação.


    Autor do resumo:Lucca Lima D'Albuquerque - 01534204
# SafesDrive

Introdução

         Neste projeto, nós queremos criar uma drive pessoal, mas com o fator distributivo.
O nosso objetivo é que o usuário da nossa drive consiga fazer o upload de ficheiros, documentos, para a sua drive pessoal e que tenha a confiança que nunca vai perder nada, pois terá tudo guardado em vários servidores. Para tal feito teremos implementação de um sistema distribuído tolerante a faltas, no qual os diferentes componentes do sistema são executados de forma distribuída e cooperam através de uma rede de comunicação.

        O utilizador fará o login, envia o ficheiro e o sistema distribuirá os dados nos diferentes servidores. Se desligarmos um dos servidores, o servidor poderá conseguir descarregar os ficheiros.

 Motivação

        A principal motivação é facilitar ao utilizador de ter uma maior confiança na utilização da sua drive pessoal, através de um sistema capaz de armazenar os seus ficheiros de forma distribuída de modo a puder obtê-lo a qualquer hora.

Problemas a abordar

      Na atualidade, os utilizadores armazenam uma grande quantidade de informação, como fotografias, documentos, vídeos e outros tipos de ficheiros, utilizando um sistema ou serviço como a cloud, para armazenar os dados ou ficheiros. Uns dos principais problemas é a indisponibilidade de um ficheiro caso o servidor esteja fora de serviço. 

      Entretanto, neste projeto pretendemos abordar esses problemas desenvolvendo um sistema de armazenamento distribuído on-line.


Possíveis Soluções

Baseando-se nos problemas já definidos, as principais soluções são as seguintes:

•	Armazenamento distribuído - a principal solução será distribuir cópias completas de ficheiros por diferentes servidores.

•	Sistema tolerante a falhas - será implementado um mecanismo que permite ao sistema detetar quando um servidor deixa de estar disponível e utilizar uma réplica armazenado noutro servidor.


REQUISITOS FUNCIONAIS E NÃO FUNCIONAIS


Requisitos funcionais
•	Registo e autenticação de utilizadores
•	Upload/download de arquivos
•	Armazenamento distribuído
•	Replicação de ficheiros

Requisitos não funcionais
•	Alta Disponibilidade
•	Tolerância a falhas
•	Durabilidade

IDENTIFICAÇÃO DO PÚBLICO-ALVO


Estudantes
•	Idade:15-30.
•	Localização: Escolas, Institutos e Universidades.
•	Habilitação: Variável.
•	Características: Necessitam de armazenar trabalho, projetos, apresentações e documentos académicos.


Professores
•	Idade: 25-65
•	Localização: Instituições de ensino.
•	Habilitação: Ensino Superior
•	Características: Armazenam e partilham documentos, materiais de ensino, projetos de investigação e conjuntos de dados.


Pequenas empresas
•	Idade: 19 - 60
•	Localização: Principalmente em Portugal
•	Habilitação: Variável 
•	Características: Necessitam de armazenar documentos empresariais.

Equipas de desenvolvimento
•	Idade: 20- 65
•	Localização: Portugal e outros países lusófonos.
•	Habilitação: Formação Técnica ou Superior
•	Características: Responsáveis pelo desenvolvimento.

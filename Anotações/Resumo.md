#### Pensamento computacional

Baseado em 4 pilares:

- Decomposição
- Reconhecimento de padrões
- Abstração
- Design de algoritmos



Uma vez que se descobre a solução de um problema é preciso testar e aperfeiçoar a solução encontrada, determinar pontos de melhoria e refinamento.

#### Ato de aperfeiçoar

##### Melhor uso de recurso

- Encontrar solução eficiente
- Otimizar processos

##### Melhorar códigos e algoritmos

- Simplificar linhas de códigos

- Funções bem definidas

  

#### Introdução ao Git e GitHub

O Git é um sistema de versionamento distribuído de código.

A sigla SHA significa Secure Hash Algorithm ( Algorítimo de Hash Seguro), é um conjunto de funções hash cripitografadas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

Quando este comando é dado no Git é feita a encriptação do documento gerando um conjunto 40 caracteres e vai servir de identificação, caso este documento sofra alguma alteração é gerado outro conjunto de caracteres. 

##### Objetos internos do Git responsáveis pelo versionamento dos códigos

- Blobs: vai armazenar os arquivos, contém metadados e o sha1 do arquivo.
- Trees: armazenas as Blobs, também contém metadados, armazena o sha do arquivo e seu nome.
- Commits: leva um carimbo de tempo, data e hora de quando foi criado, aponta para uma tree, autor, mensagem, parente.

As bolhas (Blobs) tem o sha1 do arquivo.

As árvores (Trees) apontam para as Blobs e tem um sha1 criptando os metadados.

Caso algo seja alterado no arquivo em que a Tree esta apontando, quando for gerado o sha1 desses metadados, o sha da Blob também terá mudado e consequentemente o da Tree também.

O GitHub é o repositório remoto usada por desenvolvedores para armazenar os códigos de seus projetos.


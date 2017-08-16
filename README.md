# Sobre o 'teste'

Esse é um teste feito para conhecer um  pouco mais de cada candidato a vaga de DevOps na Geru. Não se trata de um teste objetivo, capaz de gerar uma nota ou uma taxa de acerto, mas sim de um estudo de caso com o propósito de conhecer os conhecimentos, experiências e modo de trabalhar de um cadidato. Sinta-se livre para desenvolver sua solução para o problema proposto e em caso de dúvidas entre em contato no devops`at`geru.com.br.

# Cenário

Dentro do diretório `app` existe uma aplicação muito simples em Flask. Quando essa aplicação  subir ela irá ler uma variável de ambiente `GERU_PASS` que será a senha da api. Ou seja, ao executarmos uma chamada para essa aplicação devemos passar um `Header` de  `Authorization` com o token específico. Você deve nos informar como podemos definir/trocar esse token facilmente.

Seu objetivo é fazer deploy dessa aplicação na AWS. Você provavelmente precisará criar uma conta free-tier na AWS, ou utilizar uma sua já existente. Mas não se preocupe, não iremos olhar sua conta ou chamar sua aplicação já rodando, queremos que você crie uma forma de que possamos criar toda infraestrutura em nossa conta de forma simples. Você escolhe a forma. Crie um `passos.md` descrevendo todos os passos para que possamos executar sua infraestrutura em nosso ambiente. Esses são os pontos de atenção:

* Você deve clonar esse repositório e commitar todas as modificações, porém, não abra um pull request ou deixe seu código de resposta aberto.
* Depois que terminar, compacte todo o diretório e nos envie. *Queremos analisar seus commits*.
* Você deverá partir de um ambiente na AWS sem nenhuma infraestrutura já criada.
* A aplicação deverá rodar em um containner docker.

Sinta-se livre para mudar o código da aplicação se julgar necessário.

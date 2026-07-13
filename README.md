# Dokumento
### O que é?
O **dokumento** é um guia de configuração de distribuições *linux* recém instaladas.
Ele visa listar e explicar os processos de configuração iniciais, até chegarmos em um ambiente *linux* organizado, bonito, funcional e produtivo.
Além disso, o **dokumento** contém uma enciclopédia, listando e explicando cada ferramenta individualmente, além de referenciar a documentação original da mesma. Assim, caso o usuário não seja suprido pelo guia, ele saiba para onde ir.

### Como usar?
O **dokumento** é pensado para ser a primeira coisa que o usuário baixa após terminar uma instalação.
Portanto, após a instalação da distribuição *linux*, clone este repositório em seu computador e tenha em mãos um guia local para as etapas de configuração do seu sistema.
```bash
git clone https://github.com/bertolajr/dokumento.git
```
Alternativamente, mas igualmente válido, você também pode mover o **dokumento** para um *pendrive*. Assim, mesmo que não haja conexão wi-fi na recém instalada distribuição, você pode usufruir deste guia.

Ele é desenvolvido para ser lido via terminal, e por isso optei pela simplicidade do *.txt*, sem nenhum tipo de formatação. Portanto, após clonar, basta utilizar o `cat` para visualizar o conteúdo desejado.
```bash
cat ~/dokumento/nome_do_arquivo.txt | less
```
Além disso, por conter também uma enciclopédia, o **dokumento** não se aplica somente à configuração inicial. É interessante mantê-lo salvo após a instalação, para que você possa consultá-lo a qualquer momento.

### Motivação para o desenvolvimento do dokumento
Quando instalamos uma distribuição *linux*, devemos configurá-la. Entretanto, as ferramentas que utilizamos neste processo geralmente são usadas somente nesse momento, não sendo necessárias até a próxima vez em que instalarmos uma nova distribuição. Com isso, facilmente nos esquecemos destes processos.

Pensei então em fazer um guia, a princípio para uso pessoal, onde ficaria guardado em meus backups para quando eu precisasse.
Porém, conforme fui escrevendo o guia, percebi que poderia se tornar um projeto maior. Seria egoísta da minha parte não compartilhar esse documento, e se eu fosse compartilhar, deveria então fazer algo mais organizado.

Daí veio a ideia do **dokumento**, um repositório que contenha os passos e ferramentas da configuração de uma distribuição, sem que tenhamos que olhar para a documentação original da ferramenta. Isso não significa que olhar a documentação original é ruim; pelo contrário. Porém muitas vezes precisamos de apenas algum uso específico da ferramenta, que pode ser facilmente resumido, como feito nesse guia. Além disso, o **dokumento** referencia a documentação original das ferramentas para a completude do projeto.

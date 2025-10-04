<<<<<<< HEAD
# Iniciando na AWS

Estou iniciando minha jornada nas ferramentas da AWS, Git e Github para uma transição de carreira para área de tecnologia.

## 💻 Resumo das Aulas:

Como criar recursos na AWS:

Via portal, AWS SDK e cloud shell
(https://aws.amazon.com/pt/)

Criei uma conta no portal, para ter acessoas as ferramentas.

criei meu IAM Root e o AIM id para ter acesso e sempre manter meu root protegido. Verificamos todas a opções de custo para criar uma maquina virtual, em quais regiões.

Já no CLI aprendemos a criar usuarios, grupos, e disponibilizar acessos. 
Criamos uma automação para que esses usuários fossem criados mais raidamente por meio da ferramente AWS CLI e Git Bash.

Com acesso ao EC2: 

Aprendemos a criar as maquinas virtuais, utilizando a estrutura IAAS de serviço;
Aprednemos a escolher a EC2 correta para cada tipo de maquina depdendo da necessidade do projeto.

Otimizando o uso da EC2, e reduzindo custo conforme cada necessidade. 
Criando automação para que as maquinas gerem o menor custo possivel diante de suas necessidades e programando um possivel ligar e desligar quando não estão sendo utulizadas.

Opção de escalar recursos na Horizotal e vertical e para que cada uma delas é utilizada. 

Aprendemos sobre o EBS e o S3 e para que é utilizado cada recuso.

Vimos em detalhes cada classe do S3:

S3 Standard;
S3 intelligent Tiering;
S3 Express One Zone;
S3 Standard infrequent Access
S3 One zone Infrequent Access
S3 Glacier Instant Retrivial
S3 Glacier Flexivel
S3 Glacier Deep Archive
(https://aws.amazon.com/pt/s3/storage-classes/#topic-0)

Lifecycle: Que permite fazer transição de objetos e migrar automaticamente para classe Glacier.

Na sequência passamos para AMI: 
É a criação e uso de imagens no EC2;
Cria imagem da maquina virtual para espelhar para as demais.

Snashots EBS:

É um backup nativo da AWS, que faz o backup em determinados momentos, sendo possivel configurar a frequência que os snapshot são tirados.
Os valore cobrados são diferente em cada região.

Diferença entre imagem e snapshots:

No EC2 a imagem da maquina  da AMI faz o backup de um servidor inteiro, incluindo todos os volumes do EBS anexados. Já um snapshot  é uma copia pontual de um determinado volume , podendo tirar snapshot de volumes do EBS e salva-los no armazenamento do S3.

```
git init
```
## 🔍 Referências:

Site da Dio, Bootcamp, codegirls;
(https://aws.amazon.com/)
[Site para criar o readme](readme.so)



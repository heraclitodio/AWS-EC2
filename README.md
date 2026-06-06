# AWS-EC2
Gerenciando Instâncias EC2 na AWS

O EC2 é um servico da AWS do tipo IAAS que oferece unidades computacionais para seus clientes em um modelo opex. 
No EC2 um usuário administrador pode contratar as máquinas especificando os requisitos / componentes que ela terá, tanto requisitos de hardware como quantidade de memória, núcleos da cpu, etc, quanto recursos de software como o sistema operacional da máquina. Existem máquinas mais otimizadas para diferentes propósitos, proposito generico, melhor processamento,  mais memoria, melhor armazenamento, computação acelerada. O custo de cada máquina pode ser calculado nesse site https://calculator.aws/
Existem diversos modelos de contratos no EC2:
  1. O sob demanda, onde o usuário é cobrado de acordo com o que for utilizado, no entanto o custo desse modelo é geralmente maior que os outros dependendo da demanda.
  2. Instancias Reservadas, se reserva aquela máquina pelo período de tempo
  3. Instancias Spot, usuario paga pelo que usar como a sob demanda, o problem é que elas podem ser desalocadas a qualquer momento com um aviso de 2 minutos
  
Quando um recurso não estiver sendo usado, é necessário para a instancia do EC2 e desalocar o recurso para evitar gastos
AMI podem ser criadas para criar imagens de maquinas virtuais que podem lançar instáncias do EC2, uma AMI pode lançar vários EC2 diferentes
O EC2 pode ser conectado ao EBS para armazenar arquivos no formato de blocos e gerar backups

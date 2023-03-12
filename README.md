# TratamentoBDImagom
Migração e tratamento de dados referentes aos atendimentos e serviços ofertado pelo Na Hora DF no período entre 2017 e 2021.

Coluna informando qual a ocorrencia de atendimento
ocorrencia_atendimento:
INC -INICIO CHAMADO
AVI - ATENDIMENTO VIRTUAL
AUS - AUSENTE
INI -INICIO ATENDIMENTO
FIM - FIM ATENDIMENTO
ISA - INICIO SUSPENSAO ATENDIMENTO
FSA - FIM SUAPENSAO ATENDIMENTO
CAN - ATENDIMENTO CANCELADO

- Cada ocorrencia do atendimento será ligada a uma data_hora, sendo assim será criada uma tabela para cada data_hora referente a cada atendimento;
- As tabelas presentes dentro do banco: unidade-id_usuario-cod_servico-TipoServico-orgao_sigla-orgao-INC-AUS-AVI-INI-ISA-FSA-CAN-FIM-avaliacao.

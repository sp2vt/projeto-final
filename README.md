+--
+-- estrutura da tabela "estado"
+--
+
+ drop table se existe "estado"cascade,
+
create table estado (
+ id bigserial not null,
+ nome varchar (60) ,
+ + uf varchar(2),
+ ibge inteiro ,
+ pais inteiro,
+ dd json,
+ /*chaves*/
+ constraint estado-pkey
+ chave primaria (id)
+ ),
+
+ comentario na tabela estado
+ is unidades federativas `,
+ +
+ --
+ --inserindo dados na tabela "estado"
+ --
+ +
+ insert into "estado" (id,nome,uf,ibge,pais,ddd)valores
+(1,acre,ac,12,1,{68}
+ (2,alagoas,al,27,1,[82]
+ (3,amazonas,am,13,1,[97,92] )
+ (4,amapa,ap,16,1,[96] )
+ 5,bahia,ba,29,1,[88,85] )
+ 

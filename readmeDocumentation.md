##site desenvolvido por Inovare Soluções version 2017


legenda {
	
	'<=' significa que o que está ao lado direito está contido no elemento a esquerda; 
	'=>' significa que o que está ao lado esquerdo está contido no elemento a direita;
	''  significa que é um elemento pai 

	%obs: tudo que for precedido de um '*' refere-se a uma classe;	
}


@autores {
	
	nome:
	nome: 
	nome: 


	endereco:
	data: 24-02-2017 
}


$finalidade do site => Projeto elaborado visando atender as necessidades de uma instituição de ensino. Promover o conhecimento entre os seus alunnos, bem como integrá-los socialmente; 

$estrutura do template=>


container {
	
	'header' <=>  section <= logo;
	'header' <=>  section <= banner animation; 

}

navbar {
	
	'menu de navegação' <= home, serviços, educacional, galeria de fotos, contatos, lojinha;
}

container {

	'section row' <= article *col-md-9 , aside *col-md-3 <= post, foto, agenda; 
	'section row' <= article *col-md-9 , aside *col-md-3 <= post, foto, agenda;
}

nav row {
	
	'nav *col-md-9 *paginacao' <= nav *pagination *pagination-sm *mypagination;
	'aside *visitas *col-md-3' <= span 1000 visitas hoje | 45 mes;
}

footer {

	container <= nav <= ul ;
	container <= nav <= ul *redeSociais;
}
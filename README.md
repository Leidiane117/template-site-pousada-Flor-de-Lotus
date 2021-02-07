# TEMPLATE PARA O SITE POUSADA FLOR DE LÓTUS 🌷
   Html5, CSS3, Bootstrap e Jquery



## Projeto desenvolvido com proposito de ser um template de aplicação para um site de uma Pousada

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## ESTRUTURA DO PROJETO

| Diretório                    	| finalidade       	                                                                                        | 
|------------------------------	|---------------------------------------------------------------------------------------------------------- |
| src\main\java\config 			| Interface com as propriedades dos arquivos de ambiente 'Properties'                                       |
| src\main\java\data    		| Reponsável por ler arquivos yaml file e retonar objeto HashMap com os valores dos campos                  |
| src\main\java\dates 			| Metodos de suporte para trabalhar com datas                                                              	|
| src\main\java\driver 			| Responsável por fabricar os drivers para rodar local e remoto para varios navegadores                    	|
| src\main\java\pages			| Local onde deve ser criado as pages objects para facilitar a manutenção do projeto                       	|
| src\main\java\report			| Metodo responsável pela criação de screenshot anexada no Report Alure                                		|
| src\main\java\support			| Metodos de suporte a interação com os elementos web fazendo ações de click e esperas explicitas          	|
| src\main\resources\conf	    | Arquivos de configuração segregados por ambiente                                                        	|
| src\test\java\hooks          	| Metodos que executam antes e depois de cada teste (@Before, @After)                                   	|
| src\test\java\runner         	| Metodo prinicipal que inicia os testes via cucumber                                                      	|
| src\test\java\steps         	| Local onde deve ser criado as classes que representam os steps definition do cucumber                    	|
| src\test\resources\data      	| Massa de dados segregada por ambiente, escritos em arquivos yaml                                      	|
| src\test\resources\features 	| Funcionalidade e cenários de teste escritos em linguagem DSL (Gherkin language)                        	|   
    


## ESTRUTURA DO PROJETO 

| Diretório                    	| finalidade       	                                                                                        | 
|------------------------------	|---------------------------------------------------------------------------------------------------------- |
| css                            | Responsável pela estilização das páginas do site                                                          |
| imagem                         | Responsável pelo armazenamento das imagens das páginas do site                                            |
| js                             | Responsável pela criação de funções e utilização da biblioteca Jquery para as páginas do site             |
| acomodacoesPousada.html-       | Página responsável pela visualização das acomodações da pousada                                           |
| fotosPousada.html-             | Página responsável pela visuzalização das fotos da pousada                                                |
| index.html                     | Página principal do site                                                                                  |
| localizacaoPousada.html        | Página responsável por informar a localização da pousada utilizando Google Maps                           |
| reservasonline.html            | Página responsável por fazer as reservas online da pousada                                                |
| sobreNos.html                  | Página responsável por informar sobre a pousada                                                            |


## FERRAMENTAS UTILIZADAS

Visual Studio Code--------------------------- Como editor de texto

Interface------------------------------------ Mozila Firefox for Ubuntu versão 1.0

Sistema Operacional ------------------------- Linux Ubuntu 20.4


# GEOLOCALIZAÇÃO COM PYTHON/DJANGO

## No PyCharm cria-se um projeto com o nome "geo" em um ambiente virtual
    
## Instala-se as bibliotecas necessárias para  a aplicação funcionar:
    
    " pip install django geoip2 requests "
    
    django -> Framework utilizado na aplicação
    geoip2 -> Traduz o IP de uma localidade
    requests -> Busca dados numa API
    		
=========================================================================

## Criando projeto com nome "geo" com um ponto no final para não criar subpasta no projeto
	
    " django-admin startproject geo ."
		
## criando uma aplicação com nome "core"
	
    " django-admin startapp core "
		
	Adiciona todos e faz o commit
    		
    Commit: Criação do projeto geo e criação da aplicação core

=========================================================================


    Commit: Modificando arquivo README, com correções de formatação

==========================================================================

## Download dos arquivos binarios do Geoip, para consulta de cidades e países

[Github/GeoLite](https://github.com/P3TERX/GeoLite.mmdb?tab=readme-ov-file)
	
	Criar dentro da aplicação "core" um diretório com o nome "geoip"
	
	Copia os arquivos "GeoLite2-City.mmdb" e "GeoLite2-Country.mmdb"
	para dentro do diretório "geoip"
	
Commit: Download dos arquivos binarios do Geoip, para consulta de cidades e países

=============================================================================

Commit: Modificando arquivo README, correção de link (Github/Geolite)

===================================================================

### Utilizando uma API da Empresa "Yelp" para fazer buscas:
 	
 	[Yelp](https://www.yelp.com)
 	
 	Será preciso fazer uma conta no site.
 	Depois no rodapé do site clicar em Programadores/Yelp Fusion/Get Started
 	Cria o app e na opção "API Key" copia a chave e salva em algum lugar


### Fazendo configurações básicas no settings

### Corrigindo localização do diretório "geoip"

	core/geoip/GeoLite2-City.mmdb -> geoip/GeoLite2-City.mmdb
    core/geoip/GeoLite2-Country.mmdb -> geoip/GeoLite2-Country.mmdb
        

Commit: Utilizando uma API da Empresa (Yelp) para fazer buscas, configurações básicas no settings e corrigindo localização do diretório (geoip)
# Para rodar o WordPress pelo Docker:

## Baixe o Docker pelo link
https://www.docker.com/products/docker-desktop/

## Baixe os arquivos acima na sua máquina clicando em Code > Download Zip

Descompacte os arquivos e dentro da pasta e abra o terminal (basta apertar o botão direito que aparece nas opções), digite:
> Docker pull wordpress

 Espere o download
 

> docker-compose -f "docker-compose.yml" up -d --build

Espere terminar... <br>

Terminou?<br>
Tudo pronto!
Agora basta acessar <strong>http://localhost:8080/</strong> no seu navegador e começar a usar normalmente seu ambiente WordPress!!


<br>
<br>
<br>
<br>

`Ps: O endereço que você acessa no navegador só está disponível quando o Container está rodando, por padrão o Docker inicia junto ao Sistema Operacional e deixei o container setado pra rodar junto ao Docker, mas caso isso não aconteça vc pode ir no programa e na sessão 'Containers' dar play manualmente.`

Dentro da pasta do seu projeto: 
py -3 -m venv .venv
Depois: 
.venv\Scripts\activate  "Server para ativar a virtualização do flask"
E agora: 
pip3 install flask  "usar somente 1 vez para instalar o flask apos isso essa etapa pode ser pulada"
Seguido de: 
$env:FLASK_APP = "index.py"  "comando para executar o flask e o nome do seu app ele pode varias de acordo com o nome criado nesse caso Index.py"
E então o starte com:
flask run  "comando para executar o servidor flask e ele exibir localhost o seu app ou site"

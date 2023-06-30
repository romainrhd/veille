URL : https://volta.sh/

Volta est un outil qui permet de gérer la version de node, npm ou yarn dans un projet de manière isolé des autres projets. Cela permet d'avoir des versions de node différentes suivants les projets sur lesquels on travaille. 

Volta va pin la version de node ou de yarn directement dans le package.json. Cela permet de rendre transparent le versionning de node. Dès qu'on va lancer une commande node, volta fait le check dans le package.json si une version de node est spécifié par volta. Si c'est le cas, il prend la version spécifiée dans le package.json.
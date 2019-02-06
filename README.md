# 5ta Clase

// anotar todo lo que aprendí con markdown
## temas revisados
- utilizar un **forEach** para lanzar promesas y guardar los resultados en un vector **push**
- **Promise.all**  espera que todas las promesas asíncronas se completen
- el resultado de Promise.all es un vector, 
- el orden de los elementos del vector corresponde al orden de la llamadas de las promesas llamadas en el forEach.
- **Promise.race**, espera la promesa mas rapida

### Gits
- copiar llave publica y privada del _usuario root_ a un _usuario especifico_
  494  cd ~
  495  pwd
  496  cd .ssh/
  497  ls -la
  498  cp id_rsa /home/mabel/.ssh/
  499  cp id_rsa.pub /home/mabel/.ssh/
  500  exit

### comandos revisados
- git pull origin master --allow-unrelated-histories
- rm -rf .gitignore
- mv .gitignore~HEAD  .gitignore

- node cuatro.js tres cuatro cinco seis


  399  ssh-keygen -t rsa -C "mabelpeniagarcia777@gmail.com"
  400  cat ~/.ssh/id_rsa.pub
  401  ls -la
  402  ls -la ~/.ssh/
  403  cat ~/.ssh/id_rsa.pub

### instalaciones
- npm init, 
- npm init -y,
- npx install-peerdeps --dev eslint-config-airbnb

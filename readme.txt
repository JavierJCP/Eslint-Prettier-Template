si estubieramos trabajando con react tendriamos que añadir
en .eslintrc.js'
env: {},
settings: {
  version : {
    version: 'detect',
  },
},

y en extends dentro del mismo archivo 
'plugin: react/jsx-runtime' 

ojo: instalar npm i -D eslint-config-prettier, para la compatibilidad 
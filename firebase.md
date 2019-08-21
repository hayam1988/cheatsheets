#firebase 
`npm install -g firebase-tools`
`firebase login`

### deployment
### On command line
`npm run build`: builds your app and puts the optimized code in the "build" folder (this is part of create-react-app) RUN THIS EACH TIME !!

`firebase init` : start a new firebase project

- Choose firebase products(at least pick "Hosting")

- Public directory: type in "build"

- Configure as a single page app?: "y" 

- Overwrite build/index.html: "n" 

* if there are other option go with the default
`firebase deploy`


### other things on firebase 
You may have to update  ".rules" to make your database more secure

[firebase](https://firebase.google.com/docs/web/setup)





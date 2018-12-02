# Steps

- Create project

	ng new angular-openclassrooms --style=scss --skip-tests=true
	
- Install Bootstrap 4

	npm install bootstrap --save

- component
	
	ng generate component appareil

	ng generate service appareil
	
	ng g c auth

	ng g c appareil-view

	ng generate service services/auth

	ng generate component single-appareil
	ng generate component four-oh-four

	ng generate service services/auth-guard

	ng generate component EditAppareil

Model 

	ng generate class models/User

	ng generate service services/user

	ng generate component UserList
	ng generate component NewUser

# Start dev server - localhost:4200

    ng serve


# firebase

https://firebase.google.com/

compte : mdiop.sne@gmail.com
project : angular openclassrooms tuto
https://angular-openclassrooms-tuto.firebaseio.com/

# Deploy demo to github page

https://www.npmjs.com/package/angular-cli-ghpages

	npm install -g angular-cli-ghpages
	 
	ng build --prod --base-href https://diop-malick.github.io/angular-openclassrooms/

	ngh --dir=dist/angular-openclassrooms –no-silent --message="First deploy" --name="diop-malick" --email=diop-malick@hotmail.fr
React
	yarn create react-app <name app> --template typescript
	yarn add firebase
	yarn add node-sass@^5.0.0
	yarn add react-router-dom
	yarn add @types/react-router-dom -D
	yarn add classnames

Deploy:
	yarn global add firebase-tools
	firebase login
	firebase init
	yarn build
	firebase deploy


Node
	mkdir <name App>
	yarn init -y
	yarn add typescript -D
	yarn tsc --init
	yarn tsc
	yarn add express
	yarn add @types/express -D
	yarn add ts-node-dev -D
	yarn add typeorm reflect-metadata sqlite3
	yarn add uuid
	yarn add @types/uuid -D
	yarn add express-async-errors
	yarn add jsonwebtoken
	yarn add @types/jsonwebtoken -D
	yarn add bcryptjs
	yarn add @types/bcryptjs -D
	yarn add class-transformer
	yarn add cors
	yarn add @types/cors -D
	
Migrations:
	yarn typeorm migration:create -n CreateUsers
	yarn typeorm migration:run
	yarn typeorm migration:revert

	yarn typeorm entity:create -n User
	
	yarn typeorm migration:create -n CreateTags
	
	yarn typeorm migration:create -n CreateCompliments
	
	yarn typeorm migration:create -n AlterUserAddPassword

Welcome !

cd nextjs-blog
Then run the following command:

npm run dev

check from http://localhost:3000


Install and configure Swagger

Prerequisite
    Create an live swagger page, e.g: pages/api-doc.tsx
    Create an api route on nextjs, e.g: pages/api/doc.ts


Create a JSON config file as next-swagger-doc.json under root project folder
Run cli for generating swagger file
yarn next-swagger-doc-cli next-swagger-doc.json

Then /public/swagger.json is created

Test if Swagger is working fine
http://localhost:3000/api-doc
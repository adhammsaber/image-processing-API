# image-processing-API
this is a project done using express server , node.js and typescript
with an API that takes an image name , width and heigt 
and resize it using sharp package and handled different kind of errors
that might encounter the user.

1- to try the code , you can use the following url:
http://localhost:3000/api/images?file_name=fjord&width=300&height=300

2- to build the code from typescript to javascript , use the following command:
npm run build

3- to test the code , you can use the following command :
npm run test

4-to get the server to work you can use one of the following commands:
npm run start ====> typescript
node build/index =====> javascript

5-the format of the old image and the resized image would be as follows :
image_name.jpg =====> in the full folder (./assets/full)
image_name-width-height.jpg =====> in the thumb folder (./assets/thumb)

# AI-Image-Generation-App

It is a MERN Stack Web Application which is used to create AI generated images by writing the name of user and writing the description of the image that we want to create using AI and share it on the community which we can see on the home page. And it will always fetch the data that we shared on the community as we are storing the data on the MongoDB Atlas database on the cloud. We can also download the images from the community and it will show the name who have created the image and the description of the image.


## Technologies that are used in this project.
  <ul>
    <li>Vite</li> 
    <li>React</li> 
    <li>File-saver</li> 
    <li>React-Router-Dom</li> 
    <li>Tailwind-CSS</li> 
    <li>Mongoose</li> 
    <li>Express</li>  
    <li>MongoDB</li> 
    <li>Cloudinary</li>
    <li>Nodemon</li>  
    <li>Cors</li> 
    <li>Openai</li>  
  </ul>


## Features

- Fetch AI-Generated image using openai api
- Fetch All the images and related data saved on the MongoDB Atlas database
- Download the AI-Generated images from homepage
- Saving the image and its related data into MongoDB Atlas Database


## Deployment

The app has been deployed on 
https://ai-image-generator-new.netlify.app/ 

and server on 
https://ai-image-generation-server.vercel.app/


## FAQ

#### How to Generate AI-Generated Image ?

First go on Create, then enter your Name and the Description of the image that you want to generate and click on Generate and wait some time.

#### How to store the image in the MongoDB Atlas database ?

After Generating the AI-Generated image click on share with the community it will store the image and related data in the MongoDB Atlas Database redirect you to homepage where you can see the AI-Generated image created by you.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`OPENAI_API_KEY`
`MONGODB_URL`
`CLOUDINARY_CLOUD_NAME`
`CLOUDINARY_API_KEY`
`CLOUDINARY_API_SECRET`
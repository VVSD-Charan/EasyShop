# EasyShop

## EasyShop is a user-friendly E-commerce application that empowers users to effortlessly browse and buy products through a seamless shopping experience. By offering intuitive navigation through categories and flexible filters such as color, price range, size, and brand, EasyShop ensures customers can quickly find and purchase exactly what they need with utmost convenience.

### Technologies used : 
<ul>
  <li>React.JS</li>
  <li>Redux</li>
  <li>Express.JS</li>
  <li>MongoDB</li>
  <li>Stripe</li>
  <li>Cloudinary</li>
  <li>JWT</li>
  <li>Node.JS</li>
  <li>CSS</li>
</ul>

### Steps to set up and run project
<ul>
  <li>Create an account in Cloudinary , Stripe</li>
  <li>Run <strong>npm install</strong> to install all required npm packages</li>
  <li>Change endpoint secret code in <strong>app/app.js</strong> with your existing code provided by stripe (PS : Even though account is same the code changes each time a new session is created. So keep changing it whenever code is to be executed)</li>
  <li>Create a .env file in project folder in backend an fill values of JWT_KEY, STRIPE_KEY , CLOUDINARY_CLOUD_NAME , CLOUDINARY_API_KEY , CLOUDINARY_API_SECREAT_KEY , MONGO_URL(Present in local mongoDB) as per values in your created accounts. </li>
  <li>Open 2 terminals. 1 terminal to run backend part , 1 terminal for frontend. Both can be run using <strong>npm start</strong></li>
  <li>Download stripe and perform operations as instructed in it. Stripe must be running while opening project</li>
</ul>

### Glimpse of Website

#### Admin Home page 
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/d14c0316-a7d5-4fd0-a650-6e789e47a871)
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/49e1f5a8-f06f-4e71-9656-f8f17e852866)

#### Products Page
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/3521d354-a6b7-4cc9-85b1-0900b98f3098)

#### Product description page
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/6ad409ef-617f-496b-97d4-28cac8de0943)

#### Admin Dashboard
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/34b677ea-1549-44bf-a40e-93617e6de05c)
##### Add products page (Admin)
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/b5f02e68-6774-4209-b8a6-e20404aa8762)
##### Manage products stock (Admin)
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/c2d9298e-849e-42aa-b2a7-f357158b75d9)

#### Log-in page
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/70008d51-31af-4b16-9275-e3d6f4a01b1d)

#### Register or Sign-up page
![image](https://github.com/VVSD-Charan/EasyShop/assets/105978561/babc78cb-276f-407d-88ff-95f58a6d8e12)





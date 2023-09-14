# restaurantBackend

1. **config**
   - Shows the db Settings in mongoDB Cloud
   - DB name, MongoDB Uri

2. **controllers**
   - functions for the auth, reservation, restaurant
   - authController (login, signout, delete)
   - reservationController (CRUD)
   - restaurantController (CRUD)

3. **routes**
   - Setting the endpoints for each controllers
   - authRoute
   - reservationRoute
   - restaurantRoute

## Project setup

1. Install project dependencies and database configuration:
   - Begin by installing the necessary project dependencies with the following commands:
```
npm install
```
   - Additionally, configure the database settings within MongoDB Cloud, specifying the database name and MongoDB Uri.

2. Compile and enable hot-reloading for development:
   - To compile the application and enable hot-reloading for an optimal development experience, use the following command:
   ```
   node index.js
   ```

3. Access the restaurantBackend app:
   - After running the previous command, open your web browser and navigate to the designated local server address, typically http://localhost:3000. This will grant you access to the restaurantBackend app.

## Technologies Used
- Node.js
- Express.js
- MongoDB

## Acknowledgements
- This project was developed as part of learning Vue.js and web development at Vanier Cegep. Special thanks to Professor Peter Ng and other various online resources for providing valuable guidance and tutorials.

## For an Inquiries
- Please contact Pierre, at 2295472@edu.vaniercollege.qc.ca




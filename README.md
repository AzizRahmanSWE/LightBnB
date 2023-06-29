An app that will allow home owners to rent out their homes to people on vacation, creating an alternative to hotels and bed and breakfasts (AirBnb Clone).

## LighBnB Project Structure
!["Homepage ScreenShot"](https://github.com/Friies/LightBnB/blob/master/LightBnB_WebApp/Images/Homepage.png)
!["Logged User ScreenShot"](https://github.com/Friies/LightBnB/blob/master/LightBnB_WebApp/Images/Logged_in_user.png)
!["Login Page ScreenShot"](https://github.com/Friies/LightBnB/blob/master/LightBnB_WebApp/Images/Login_page.png)
!["Sign Up ScreenShot"](https://github.com/Friies/LightBnB/blob/master/LightBnB_WebApp/Images/Sign_up_page.png)

## Dependencies
- pg
- Express
- Nodemon
- bcrypt
- cookie-session


## Getting Started
- Clone and navigate to the directory.
- Start database server by entering `psql -U your_username -d your_database_name` in the terminal.
- Import the seed files by using `\i` followed by the path.
  - `\i /LightBnb/seeds/01_seeds.sql`
  - `\i /LightBnb/seeds/02_seeds.sql`
- Install all the dependencies by running command `npm install`.
- Run the development web server in the LightBnB_WebApp directory, using the `npm run local` command.
- The terminal will display "listening on port 3000 😎".
- Type http://localhost:3000/ in your browser (chrome, safari, etc.) search bar to access the site.
- Enjoy the Experience.

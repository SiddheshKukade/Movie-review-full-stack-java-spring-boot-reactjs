# Movie Review App

Welcome to the Movie Review App repository! This full-stack application is built using Java Spring Boot for the backend API and ReactJS for the frontend user interface. The backend utilizes MongoDB Atlas cloud as the database to store and manage movie data and user reviews.

## Demo:
#### Desktop View
![image](https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs/assets/65951872/3c1a2734-880d-4bd1-8259-6c9933487fb3)
#### Mobile View:
Mobile Responsive

![image](https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs/assets/65951872/3150c436-62cf-44a7-9399-f056ab6e0ec8)
#### Writing Reviews:
![image](https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs/assets/65951872/4d2264de-a891-4e51-a63a-5f11fb2acc59)

### Watch Vides Fetched From Youtube and Write reviews:
![image](https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs/assets/65951872/4c687d94-913d-4e87-99be-3b1cb49fc497)

## Top Features

- **User Authentication**: Secure user authentication system to allow users to create accounts, log in, and manage their profiles.
- **Browse Movies**: Users can explore a vast collection of movies with detailed information.
- **Search Functionality**: A powerful search feature enables users to find movies based on titles, genres, actors, and more.
- **Write Reviews**: Registered users can write and submit reviews for their favorite movies.
- **Rating System**: Users can rate movies and view the average rating given by other users.
- **Responsive UI**: The user interface is responsive and optimized for various devices, ensuring a seamless user experience.

## Installation Steps

### Backend (Java Spring Boot)

1. **Clone the repository:**
 
git clone [https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs.git](https://github.com/SiddheshKukade/Movie-review-full-stack-java-spring-boot-reactjs/edit/master/README.md)
 

2. **Navigate to the backend directory:**
 ```
cd movie-review-app/backend

 ```

3. **Set up MongoDB Atlas:**
- Create an account on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- Create a new cluster and obtain the connection string.

4. **Configure MongoDB Connection:**
- Replace `<mongo_connection_string>` in `application.properties` with your MongoDB connection string.

5. **Run the Spring Boot Application:**
 ```
./mvnw spring-boot:run
 
```
6. The backend server should now be running at `http://localhost:8080`.

### Frontend (ReactJS)

1. **Navigate to the frontend directory:**
 ```
cd movie-review-app/frontend
 ```

2. **Install dependencies:**
 ```
npm install
 ```

3. **Set up environment variables:**
- Create a `.env` file in the frontend directory.
- Add the following line to the `.env` file and replace `<backend_api_url>` with the actual backend API URL (e.g., `http://localhost:8080`):
 
REACT_APP_API_URL=<backend_api_url>
 

4. **Run the React App:**

```
npm start
 ```

5. The React app should now be running at `http://localhost:3000`.

## Contributing

If you want to contribute to this project and make it better, your help is very welcome. Create a pull request with your proposed changes, and we will review it as soon as possible.

Happy coding! 🚀
@SiddheshKukade

# Employee review system

This Employee review web application is created for employees to submit feedback toward each other's performance. User's could have either "employee" or "admin" role. There are two dashboard pages based on the role of the employee those dashboard pages will be rendered, User with role of admin can assign employees to participate in review of other employees. Employees can only submit feedback required by assigned reviews. \
It is built using NodeJs, ExpressJs, MongoDB, EJS and JavaScript.
https://employee-review-system-vyfm.onrender.com/

![image](https://user-images.githubusercontent.com/35091245/205214105-5b3f7c6d-4baf-4079-acea-076bca8a13c0.png)


## ⚙️ Functionality

### Admin's functions

- Add employee
- Delete employee
- Update employee details
- Assign review to employee
- Update review of employee

### Employee's functions

- Submit reviews assigned to it
- View reviews given by others

## 🧑‍💻 Getting started

- Fork the project
- Clone the forked repository in your local system
- Create .env file in the root directory and add the following:-
  - PORT="Your port number"
  - MONGODB_URL="Your MongoDB URL"
  - SESSION_SECRET_KEY="Your secret session key"
- Install all required packages

```bash
npm install
```

- Run project

```bash
npm start
```

The project is running on the port number provided by you.

## 🛠️ Tools Used

- NodeJS
- MongoDB
- ExpressJS
- EJS
- Bootstrap

### 📚 Libraries:

- bcryptjs
- connect-flash
- connect-mongo
- cookie-parser
- dotenv
- ejs
- express
- express-ejs-layout
- express-session
- mongoose
- passport
- passport-jwt
- passport-local

## 🖼️ Screenshots
![image](https://user-images.githubusercontent.com/35091245/205214233-04937a10-2672-423e-b26f-f1d6ba94c485.png)
![image](https://user-images.githubusercontent.com/35091245/205214277-d8dd523a-f919-460f-9361-427eccfdea60.png)
![image](https://user-images.githubusercontent.com/35091245/205214395-61622d49-c4e5-490f-8603-e72559248828.png)




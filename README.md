# Style Share

A simple web-based platform where users can easily create, explore, and share Tailwind CSS components and designs with fellow users.

## Project Description

Style Share is a collaborative platform designed to streamline the process of creating and sharing Tailwind CSS components. Users can explore a wide range of design components created by the community, contribute their own, and engage with fellow designers and developers to enhance their web development projects.

## TechStack

- TypeScript
- Express
- React
- Recoil
- Prisma + MongoDB
- Tailwind

## Screenshots

![alt text](./screenshots/Screenshot_home.png)
![alt text](./screenshots/Screenshot_about.png)
![alt text](./screenshots/Screenshot_login.png)
![alt text](./screenshots/Screenshot_sign.png)
![alt text](./screenshots/Screenshot_post.png)
![alt text](./screenshots/Screenshot_code.png)
![alt text](./screenshots/Screenshot_create_post.png)
![alt text](./screenshots/Screenshot_leaderboard.png)

## Video


https://github.com/VaibhavArora314/StyleShare/assets/142779809/f5e9ee4d-291b-4dd5-915f-a76688efbd97



## Setting Up on your machine

1. Go to the backend folder and create a .env file similar to [.env.example](https://github.com/VaibhavArora314/StyleShare/blob/main/backend/.env.example)
2. Run the following commands in the backend folder

   ```sh
   npm install
   npm run build
   npm run dev
   ```

   The npm run build cmd will handle the Prisma migrations, and also build the frontend folder which will be served by the express server.

   Possible Problems:

   - Prisma may give error for MongoDB replica set, in such case use Mongodb atlas for the database instead of the local database or start a Mongo docker container with the replica set.

3. In case you are modifying the frontend and you want hot module reloading, then run the following commands in the frontend directory
   ```sh
   npm install
   npm run dev
   ```
   Also, set the default base URL of the backend (don't push this to GitHub) or simply uncomment the following:
   [App.tsx lines 17-18](https://github.com/VaibhavArora314/StyleShare/blob/ffb31d5bd3f68fbd76b300a736d56c2a0f1f77ac/frontend/src/App.tsx#L17-L18)

## How to Contribute

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Clone the repository.
   ```sh
   git clone https://github.com/VaibhavArora314/StyleShare.git
   ```
3. Create a new branch.
   ```sh
   git checkout -b your-branch-name
   ```
4. Make your changes.
5. Commit your changes.
   ```sh
   git commit -m 'Add some feature'
   ```
6. Push to the branch.
   ```sh
   git push origin your-branch-name
   ```
7. Open a pull request.

## Our Contributors

<p><a href="https://github.com/VaibhavArora314/StyleShare/contributors">
  <img src="https://contributors-img.web.app/image?repo=VaibhavArora314/StyleShare" />
</a></p>

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/VaibhavArora314/StyleShare/blob/main/LICENSE) file for more details.

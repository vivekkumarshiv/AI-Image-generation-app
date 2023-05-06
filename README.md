# MyFull Stack AI Image Generator App

This is a Full Stack AI Image Generator App that uses OpenAI API, Cloudinary, React JS, REST API, Express JS, and MongoDB. The app allows users to generate realistic images based on a given text input using OpenAI's GPT-3 model. Users can also upload images, which are stored in a Cloudinary account and saved in a MongoDB database. The app also provides CRUD functionalities to manage the uploaded images.

## Features

- Generate realistic images based on a given text input using OpenAI's GPT-3 model.
- Upload images and store them in a Cloudinary account and MongoDB database.
- Manage uploaded images with CRUD functionalities.
- User authentication and authorization.

## Technologies Used

- [OpenAI API](https://openai.com/)
- [Cloudinary](https://cloudinary.com/)
- [React JS](https://reactjs.org/)
- [REST API](https://restfulapi.net/)
- [Express JS](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository.

```bash
git clone https://github.com/yourusername/myfull-stack-ai-image-generator-app.git
```

2. Install dependencies.

```bash
cd myfull-stack-ai-image-generator-app
npm install
```

3. Set up a Cloudinary account and create a `.env` file at the root directory of the project with the following content:

```
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

4. Set up an OpenAI account and create a `.env` file at the root directory of the project with the following content:

```
OPENAI_API_KEY=your_openai_api_key
```

5. Set up a MongoDB database and create a `.env` file at the root directory of the project with the following content:

```
MONGODB_URI=your_mongodb_uri
```

6. Start the server and client.

```bash
npm run dev
```

## Usage

1. Open your web browser and go to `http://localhost:3000`.
2. Sign up or log in with your credentials.
3. To generate an image based on a text input, enter the text in the text box and click on the "Generate Image" button.
4. To upload an image, click on the "Upload Image" button and select the image file to upload.
5. To manage uploaded images, click on the "My Images" button to go to the "My Images" page. On this page, you can view, edit, and delete uploaded images.





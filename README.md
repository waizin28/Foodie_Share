<img width="1728" alt="Screenshot 2024-10-26 at 12 10 59 AM" src="https://github.com/user-attachments/assets/12f16c2e-e943-420a-a630-08d58c270567">

# FoodieShare 🍲 

**FoodieShare** is a platform for food enthusiasts to share their favorite recipes, discover new dishes, and connect with a community of food lovers. Whether you’re a professional chef, a home cook, or someone who simply loves great food, FoodieShare provides a space to explore, create, and share culinary inspiration.

## Features
- **Discover Recipes:** Browse a collection of recipes shared by food lovers around the world.
- **Share Your Recipes:** Upload your own recipes with images, ingredients, and step-by-step instructions.
- **Connect with Food Lovers:** Follow other users, leave comments, and get inspired by their creations.
- **Search and Filter:** Easily find recipes based on cuisine, dietary preferences, difficulty level, and more.
- **Save Favorites:** Bookmark recipes you want to try later for easy access.
  
## Getting Started

### Prerequisites
Make sure you have the following installed on your system:
- **Node.js** and **npm** for managing dependencies
- **MongoDB** (if using a local database) or a MongoDB cloud service
  
### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/foodie-share.git
    cd foodie-share
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Configure Environment Variables**
   Create a `.env` file in the project root and set the following variables:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```

4. **Run the Application**
    ```bash
    npm start
    ```
   The app should now be running on `http://localhost:5000`.

## API Endpoints

- **GET /api/recipes** - Retrieve all recipes
- **POST /api/recipes** - Add a new recipe (authenticated users only)
- **GET /api/recipes/:id** - Retrieve a single recipe by ID
- **POST /api/users/register** - Register a new user
- **POST /api/users/login** - Login a user
- **GET /api/users/:id** - Get a user profile

## Technologies Used

- **Frontend:** React, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ORM)
- **Authentication:** JSON Web Tokens (JWT)
  
## Contributing

We welcome contributions! If you’d like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thank you to everyone in the FoodieShare community for sharing your culinary creations, ideas, and inspiration. This platform wouldn’t be possible without your passion for food!
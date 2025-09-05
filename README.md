# HGOAI

HGOAI is an AI-powered SaaS platform that provides a suite of tools for content generation, image editing, and resume analysis. The project is designed to deliver multiple AI functionalities through a single, responsive web application.

---

## Features
* **Generate Article:** Create detailed, long-form articles from a simple text prompt.
* **Generate Blog Titles:** Produce creative titles for blog posts.
* **Generate Images:** Create original images from descriptive text using a text-to-image model.
* **Remove Image Background:** Automatically remove backgrounds from uploaded images.
* **Remove Image Object:** Select and erase unwanted objects from an image.
* **Review Resume:** Analyze resume content for improvements in formatting and keywords.

---

## Technology Stack
* **Frontend:** HTML, CSS, JavaScript, React, Tailwind CSS
* **Backend:**  Node.js (Express)
* **Database:** Neon (Serverless PostgreSQL)

---

### Getting Started
To set up a local development environment, follow these steps:

1.  **Clone the repository:**
   ```bash
   git clone https://github.com/lcbalsa/hgoai.git
   cd hgoai
   ```
2. **Navigate to the project directories:**
   ```bash
   # Navigate to the client directory
   cd client
   npm install

   # Navigate to the server directory
   cd server
   npm install
   ```

### Configure environment variables:

Create a `.env` file in the server directory.

Add the following required keys to the server's .env file:
Neon database connection string
* `DATABASE_URL` (for your Neon database connection string)
* `CLERK_PUBLISHABLE_KEY`
* `CLERK_SECRET_KEY`
* `CLOUDINARY_CLOUD_NAME`
* `CLOUDINARY_API_KEY`
* `CLOUDINARY_API_SECRET`
* `GEMINI_API_KEY`
* `CLIPDROP_API_KEY`

### Start the client and server applications:

```bash
# Start the client (in the 'client' directory)
npm run dev

# Start the server (in a separate terminal, from the 'server' directory)
npm start server
```

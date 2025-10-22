# DECORWORLD
🏡 AI Declutter & Design Studio

This is a single-page web application (SPA) designed to help users organize, style, and visualize the transformation of their rooms using the power of the Gemini API for multi-modal analysis and image generation.

The entire application logic (HTML, Tailwind CSS styling, and JavaScript) is contained within the single index.html file.

✨ Features

This app uses Google's Gemini models to deliver three core services:

Analyze Room (VLM/Gemini 2.5 Flash): Upload a photo to get a detailed, step-by-step plan for decluttering and organization, focusing on messy areas and storage needs.

Style Vision & Shopping List (LLM/Gemini 2.5 Flash): Generate a tailored interior design style (e.g., Scandinavian, Industrial) and a pragmatic shopping list of organizational items based on the initial room analysis.

Visualize New Room (Image Generation/Imagen 3.0): Generate a photo-realistic visualization of the room after it has been organized and redesigned, providing a clear "after" picture of the transformation.

🚀 Setup & Installation

Since this is a single, self-contained HTML file, setup is very simple.

1. Download the File

Save the code from the Canvas document (index.html) to a file named index.html.

Place it in a new, empty project folder.

2. API Key Requirement

⚠️ Note on APIs: The app requires access to the Gemini and Imagen APIs. In the Canvas environment, the API key is automatically supplied. When hosting this app yourself, you will need to manage API access. For security, do not hardcode your API key in the index.html file.

3. Running Locally (For Testing)

You can open index.html directly in your browser, but due to browser security restrictions (CORS and mixed content), the API calls to Google's servers may fail.

4. Hosting for Full Functionality (Recommended)

To ensure the API calls work correctly and securely (using HTTPS), you must host the file on a web server.

Option A: Quick Static Hosting (Vercel, Netlify)

Initialize a Git repository in your project folder.

Commit the index.html file.

Connect your repository to a static hosting provider like Vercel or Netlify.

These platforms will automatically deploy the file, providing you with a secure (HTTPS) URL.

Option B: GitHub Pages

Create a public repository on GitHub.

Upload the index.html file to the root of the repository.

Go to Settings > Pages and select the branch containing the code to deploy the site.

🛠️ Technology Stack

Frontend: Pure HTML/JavaScript

Styling: Tailwind CSS (loaded via CDN)

Markdown Rendering: Marked.js (loaded via CDN)

APIs:

gemini-2.5-flash-preview-09-2025 (Analysis, Style, Shopping)

imagen-3.0-generate-002 (Visualization)

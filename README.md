🎨 Art Space
Art Space is a web platform that empowers artists by giving them a clean, modern online space to showcase and sell their artwork directly to customers. It’s built with modern web tooling and deployed on Vercel for fast, responsive delivery.

Live Demo: https://gravity-space-rose.vercel.app/ 
Contact: rugambayvan1@gmail.com 

Key Features
Artist/product listings

Responsive, mobile-first UI

Fast development with modern stack (React + Tailwind)

Easy deployment via Vercel

Tech Stack
Frontend: React (likely using Vite)

Styling: Tailwind CSS

Deployment: Vercel

Package Manager: npm

Full Setup Instructions (Every Step)
1. Prerequisites
Install the following if you don’t already have them:

Node.js (v16+ recommended) — includes npm.
Verify with:
node --version
npm --version

Git — to clone the repository.
Verify with:
git --version

2. Clone the Repository
In your terminal, run:

git clone https://github.com/Yvantrey/art-space.git
cd art-space

3. Copy and Configure Environment Variables
There is a .env.example file that shows the environment variables the app expects. To use it:

cp .env.example .env

Then open the .env file and fill in the required values.
(If it’s empty or has placeholders, replace them with real values such as API keys, URLs, etc.)

4. Install Dependencies
Run:

npm install

If you see a bun.lockb file and prefer Bun, you can also run:

bun install

But npm is the default unless you intentionally switch.

5. Run in Development Mode
Start the dev server:

npm run dev

The server will usually run at:
http://localhost:5173

6. Build for Production
To build an optimized version for deployment:

npm run build

7. Preview Production Build Locally
After building:

npm run preview

This serves the production version locally for final testing.

Project Structure
art-space/
├── public/ → Static assets
├── src/ → App source code
│ ├── components/ → Reusable UI components
│ ├── pages/ → Route-level components
│ ├── App.jsx → Root React component
│ └── index.css → Global styles (Tailwind)
├── .env.example → Sample environment variables
├── package.json → Project config and scripts
├── vite.config.js → Vite configuration
├── tailwind.config.js → Tailwind setup
└── vercel.json → Vercel deployment config

Common Scripts
npm run dev → Start development server

npm run build → Build for production

npm run preview → Preview production build locally

(Add any others if applicable, like test or lint commands.)

Deployment (Vercel)
To deploy the project on Vercel:

Push your code to GitHub (if not already).

Log in to https://vercel.com and click “New Project”.

Import the GitHub repo.

Set required environment variables in Vercel dashboard (match .env).

Click “Deploy”.


Contributing
Fork the repository

Create a new branch: git checkout -b feature/your-feature

Make your changes

Commit: git commit -m "Add feature"

Push: git push origin feature/your-feature

Open a Pull Request

Suggested Improvements
Add authentication for artists and buyers

Integrate payment options

Add dashboard for managing artworks

Email notifications

Testing (unit/integration)

Contact
For feedback, questions, or collaboration:

Email: rugambayvan1@gmail.com 
GitHub: https://github.com/Yvantrey 

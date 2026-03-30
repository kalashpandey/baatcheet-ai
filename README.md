
# BaatCheet AI - India's #1 AI Social Coach

BaatCheet AI helps Indian users craft the perfect replies for Instagram, WhatsApp, and dating apps using Groq Llama 3 AI.

## 🚀 Deployment Options (Free)

Since this is a Next.js app, you can easily deploy it for free on platforms other than Firebase.

### 1. Vercel (Recommended for Next.js)
1. Push your code to a **GitHub**, GitLab, or Bitbucket repository.
2. Sign in to [Vercel](https://vercel.com/) and click **"New Project"**.
3. Import your repository.
4. **Important:** Under "Environment Variables", add:
   - `GROQ_API_KEY`: Your Groq API key from console.groq.com.
5. Click **Deploy**. Vercel will automatically detect Next.js and handle the build.

### 2. Netlify
1. Push your code to a Git provider.
2. Sign in to [Netlify](https://www.netlify.com/) and select **"Import from Git"**.
3. Connect your repository.
4. In the "Site configuration" > "Environment variables" section, add your `GROQ_API_KEY`.
5. Netlify will use the `@netlify/plugin-nextjs` to deploy your app.

## 🛠 Tech Stack
- **Framework:** Next.js (App Router)
- **AI:** Groq (Llama 3.3 70B)
- **UI:** React, Tailwind CSS, ShadCN UI
- **Storage:** LocalStorage (for usage tracking & history)

## 🔑 Environment Variables
Make sure to set the following in your deployment platform's dashboard:
- `GROQ_API_KEY`: Required for generating AI replies.

## 📦 Local Development
1. Install dependencies: `npm install`
2. Run the dev server: `npm run dev`
3. Open [http://localhost:9002](http://localhost:9002) in your browser.

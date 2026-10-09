# Portfolio: deploy on Vercel

Folder contents: index.html, photo.jpg, Hari_Shanker_Mishra_CV.pdf, vercel.json. It is a plain static site, so no build step is needed.

## Option A: Vercel CLI (fastest)
1. Install Node.js, then run: npm i -g vercel
2. Open a terminal inside this folder and run: vercel login
3. Run: vercel   (accept the defaults; Framework = Other, no build command, output directory = ./)
4. Run: vercel --prod   to get your live link.

## Option B: GitHub + Vercel dashboard (best for updates)
1. Create a GitHub repository and upload all files in this folder.
2. Go to vercel.com, sign in with GitHub, click Add New > Project and import the repository.
3. Framework Preset = Other, leave Build Command empty, click Deploy.
4. Every later push to GitHub redeploys automatically.

## After deploying
- Settings > Domains lets you add a custom domain such as harishankermishra.com.
- Add your GitHub link in the contact section of index.html once your profile is ready.
- The CV PDF contains your phone number and will be public. Replace it with a no-phone version if you prefer.
- Keep project descriptions general. Do not add confidential details about client systems.

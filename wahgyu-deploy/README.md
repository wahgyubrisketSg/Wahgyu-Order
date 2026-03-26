# WAH! GYU — Ordering Website

Singapore's first & only smoked Japanese Toriyama wagyu brisket.

## Deploy to Vercel (Step by Step)

### Step 1: Upload to GitHub
1. Go to [github.com/new](https://github.com/new)
2. Name the repository `wahgyu-order`
3. Keep it **Public** and click **Create repository**
4. On the next page, click **"uploading an existing file"**
5. Drag & drop ALL files from this folder into the upload area
6. Click **Commit changes**

### Step 2: Deploy on Vercel
1. Go to [vercel.com/new](https://vercel.com/new)
2. Click **Import** next to your `wahgyu-order` repository
3. Framework Preset should auto-detect as **Vite**
4. Click **Deploy**
5. Wait ~60 seconds — your site will be live!

### Step 3: Your live URL
Vercel will give you a URL like: `wahgyu-order.vercel.app`
Share this with your customers!

### Optional: Custom Domain
To use a domain like `wahgyu.sg`:
1. Buy the domain from a registrar (Namecheap, GoDaddy, etc.)
2. In Vercel dashboard → Settings → Domains → Add your domain
3. Follow the DNS instructions Vercel provides

## Tech Stack
- React 18 + Vite
- Web3Forms (email notifications)
- PayNow QR (payment)

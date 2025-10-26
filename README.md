🏏 Cricket AI Predictor - Telegram Mini App (HTML/JS)
​Yeh ek single-file Telegram Mini App hai, jisko HTML, Tailwind CSS, aur Vanilla JavaScript use karke banaya gaya hai. Ismein Google Gemini API aur Firebase Firestore ki integration hai, taaki yeh AI-powered cricket predictions de sake aur monetization (Free Trial/Premium Gate) handle kar sake.
​🚀 Setup Aur Deploy Kaise Karein
​Kyunki yeh ek single index.html file hai, isko deploy karna bahut aasan hai.
​1. File Upload
​Pura index.html file copy karke apne repository mein daal dein.
​2. Configuration Update Karein
​index.html file ke <script type="module"> block mein yeh teen (3) variables zaroor change karein:
// --- CONFIGURATION (UPI ID AUR LINKS APKE HISAB SE) ---
const UPI_ID = "Muahshi7759@ybl"; // <-- Apna UPI ID Yahan Daalein
const PREMIUM_TELEGRAM_LINK = "[https://t.me/your_premium_group](https://t.me/your_premium_group)"; // <-- Apna Telegram Channel Link Yahan Daalein
const AFFILIATE_LINK = "[https://your-betting-platform.com](https://your-betting-platform.com)"; // <-- Apna Betting/Affiliate Link Yahan Daalein
3. Deployment
​Yeh app kisi bhi static file hosting service (jaise GitHub Pages, Vercel, Netlify) par deploy ho sakta hai.
​GitHub par repository banao.
​Files upload karo.
​GitHub Pages ko setup karo, taaki index.html ek public URL par available ho jaaye.
​4. Telegram Bot Se Jodein
​Apna Telegram Bot banao aur uske BotFather settings mein jaakar yeh URL daalo.
​Example URL: https://yourusername.github.io/your-repo-name/index.html
​✨ Features
​Single-File Architecture: Easy deployment ke liye saara code ek hi index.html mein hai.
​Gemini API Integration: Live data use karke detailed cricket predictions (Pitch Report, Toss Decision, Key Battles).
​Firebase Firestore: User tracking ke liye (freeCount aur isPremium status save karta hai).
​Monetization Gate: Pehle prediction ke baad Premium Modal show hota hai.
​Mobile-First UI: Telegram Web App SDK aur Tailwind CSS ke saath fully responsive design.
​Robustness: Firebase configuration missing error aur API request retries ke liye fixes daale gaye hain.
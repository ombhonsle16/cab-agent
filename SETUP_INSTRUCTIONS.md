# Bhonsle Family Travel Sahayak — Best Rollout Setup Guide (Path 1)

## Step 1: Deploy to Vercel (Takes 60 Seconds)
1. Unzip this folder (`bhonsle_vercel_and_tasker_bundle.zip`).
2. It already contains `index.html` and `vercel.json`.
3. Upload the folder to **Vercel** (or push to your GitHub repo connected to Vercel) to get your permanent `https://...vercel.app` link.

## Step 2: Add to Home Screen on Mom, Dad, Ajoba & Aaji's Phones
1. Open the Vercel `https://` link in **Chrome** on each family phone.
2. Tap **⋮ (top-right menu) → Add to Home screen** and name it **Travel Sahayak**.
3. For **Ajoba & Aaji**, tap the **👴 Senior Mode: ON** button in the top bar — this locks the screen into Extra-Large text and shows only the 1-Tap Voice Command mic, your exact family places (*Om's House Dahisar*, *Sai Vishram / Nia's Home*, *Aai's Home Panvel*, *Oberoi Sky City*, *Divyom Goa*, *Dhanshri Salon*), and the **Call / WhatsApp Om** bar.

## Step 3: Optional Tasker + AutoInput Live Auto-Clicker (For 100% Hands-Free "Confirm" Tap)
1. On their Android phone, install **Tasker** and **AutoInput** from the Google Play Store.
2. Long-press the **Profiles** tab inside Tasker → tap **Import Profile** → select `Bhonsle_AI_Cab_Agent.prf.xml` from this folder.
3. Enable **Tasker** and **AutoInput** in **Android Settings → Accessibility**.
4. Now, whenever the AI Agent finishes scanning in the web app, tapping **⚡ Trigger Tasker Auto-Clicker** (or speaking a destination) triggers `bhonsleagent://autobook` directly on the phone!

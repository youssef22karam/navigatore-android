# How to get your APK from GitHub (no Android Studio needed)

## Step 1 — Create a free GitHub account
Go to https://github.com and sign up (free).

## Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `navigator-app`
3. Set it to **Public** (or Private — both work)
4. Click **Create repository**

## Step 3 — Upload the project files
On your new empty repo page, click **uploading an existing file**:
1. Unzip `navigator-android.zip` on your computer
2. Drag ALL the contents of the `navigator-android/` folder into GitHub
3. Make sure you include the hidden `.github/` folder!
   - On Mac: press Cmd+Shift+. to show hidden files
   - On Windows: tick "Hidden items" in File Explorer
4. Click **Commit changes**

## Step 4 — Watch it build
1. Click the **Actions** tab on your repo
2. You'll see "Build Navigator APK" running (yellow spinner)
3. Wait ~3–5 minutes for it to finish (green ✓)

## Step 5 — Download your APK
1. Click on the completed workflow run
2. Scroll down to **Artifacts**
3. Click **Navigator-debug-APK** — it downloads a zip
4. Unzip it → you have `app-debug.apk`

## Step 6 — Install on your phone
1. On your Android phone:
   - Go to **Settings → Security** (or Apps)
   - Enable **Install unknown apps** for your browser or Files app
2. Transfer the APK to your phone (email it to yourself, Google Drive, USB, etc.)
3. Open the APK file on your phone → tap **Install**
4. Open **Navigator** — it will ask for location permission → tap **Allow**

## Updating the app
Any time you push a change to GitHub, the APK rebuilds automatically.
Just repeat Step 5 to get the new APK.

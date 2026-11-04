# Storyroom

A roleplay chat app you install on your phone. It talks to an AI provider directly with your own API key, so no Claude.ai login is needed.

## 1. Get a free API key

1. Sign up for free at https://openrouter.ai.
2. Create an API key (Settings → Keys) and copy it.

The app comes set to the model `openrouter/free`, which only uses free models, so you're never charged. Free models can have usage limits and are less polished than paid ones. If you ever want better writing, you can enter a paid model name in the app or switch the provider to the Anthropic API (paid, https://console.anthropic.com).

## 2. Put the app online (free, one time)

The phone needs to load the app from an `https://` address once to install it.

**GitHub Pages:**
1. Make a free account at https://github.com and create a new **public** repository called `storyroom`.
2. Click **Add file → Upload files** and upload everything in this folder (not the folder itself).
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute your app is at `https://YOUR-USERNAME.github.io/storyroom/`.

Netlify or Cloudflare Pages work too: drag this folder onto their deploy page.

Your API key is never uploaded. It's only typed into the app on your phone and stays there.

## 3. Install on your phone

- **iPhone:** open the link in **Safari**, tap **Share → Add to Home Screen**.
- **Android:** open the link in **Chrome**, tap **⋮ → Install app** (or **Add to Home screen**).

Open Storyroom from your home screen, tap **Setup**, and enter your provider, API key and model.

## Notes

- Chats and settings are stored on the device. Use **Back up** and **Restore** in Setup to move them between devices.
- The content rating (All ages / Teen / Mature) and the avoid/allow boxes shape what the story aims for. The model still follows its provider's own rules.
- To update the app later, upload the changed files to the same place. The installed app picks up the new version next time it opens online.

# Cosmic Sandbox — GitHub Pages package

This is a ready-to-publish copy of the game. The website entry point is `index.html`; the included workflow publishes it to GitHub Pages over HTTPS.

## Publish it

1. Create a **public** GitHub repository named `cosmic-sandbox`.
2. Upload the contents of this folder to the repository's `main` branch. Keep `.github/workflows/pages.yml` in place.
3. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the publishing source.
4. Open **Actions** and wait for **Publish Cosmic Sandbox** to finish. GitHub will show the website address in the deployment details. It will look like `https://YOUR-ACCOUNT.github.io/cosmic-sandbox/`.

After the first setup, future pushes to `main` publish automatically.

## New SandBox and online chat

The game now includes a separate SandBox workbench for physics, chemistry, atomic and nuclear experiments, and a particle accelerator. Invite-only chat uses PeerJS over WebRTC with short room codes; messages are temporary and are not stored. Chat requires the PeerJS script and connection service to be reachable, which school networks may restrict.


The Activities board adds 19 guided challenges across orbits, chemistry, cosmic events, the particle accelerator, fission, the Life Lab, and Academy/Forge. Completing activities awards Mastery Points and progress saves on the device.

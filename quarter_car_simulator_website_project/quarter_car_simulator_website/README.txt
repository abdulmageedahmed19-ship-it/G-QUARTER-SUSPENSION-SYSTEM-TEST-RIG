# Quarter-Car Active Suspension Simulator

This is a standalone website. It uses plain HTML, CSS and JavaScript; no framework,
package installation, server, or internet connection is required to run it locally.

## Run locally
1. Extract this folder if you received it as a ZIP.
2. Open `index.html` in Google Chrome, Microsoft Edge, or Firefox.
3. The simulation starts automatically. Use the left-side sliders and controls.

## Publish as a public website with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example
   `quarter-car-suspension-simulator`.
2. Upload `index.html` to the repository root and commit the change.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to deploy. The Pages screen will show your public website URL.

## Publish with Netlify Drop
1. Open Netlify and sign in.
2. Drag the folder containing `index.html` onto Netlify Drop.
3. Netlify will publish it and provide a public URL.

## Files
- `index.html` — complete website source (HTML, CSS and JavaScript in one file).

## Model limitations
The website is a simplified 2-degree-of-freedom quarter-car model with a PID force
controller and sinusoidal road input used as a simplified representation of roller
excitation. It is not a full multibody CAD model, roller-contact model, structural
FEA model, or safety validation. Replace the illustrative parameter defaults with
measured component data and validate the model before using results for engineering
decisions or fabrication.

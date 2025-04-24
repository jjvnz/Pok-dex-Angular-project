# Pokédex Angular Deployment

## Setting Up a Netlify Account

1. Visit [Netlify](https://www.netlify.com/) and click "Sign up."
2. Sign up using GitHub or an email address.
3. Verify your email and log in.
4. Click "New site from Git" and connect your GitHub account.
5. Select the `Pok-dex-Angular-project` repository and configure:
   - Base directory: `/`
   - Build command: `npm run build`
   - Publish directory: `dist/pokedex-angular`
6. Deploy the site and note the public URL (e.g., `https://pok-dex-angular.netlify.app/`).

## Project Overview

This project is an Angular-based Pokédex application that displays Pokémon from the first three generations, using the [PokéAPI](https://pokeapi.co/).
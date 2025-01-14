# SvelteKit Uno Game

![UNO](./static/pics/uno_banner_1280x640.png)

Here is the structure for this project:

We hop to build a simple Uno game using SvelteKit. This will demonstrate basic card handling, game logic, and multiplayer capabilities. We will use TailwindCSS for styling and Socket.io for multiplayer.

---

Here is the structure for this project:
![Structure](./static/pics/uno-flow-1.png)

![Game Start](./static/pics/ui-game-start.png)
![Game Play](./static/pics/ui-game-play.png)

Game Loop:

## Getting Started

Clone the repository and install the dependencies.

```bash
git clone https://github.com/timscodebase/uno.git
cd uno
npm install  // or pnpm install
```

To run the project:
```bash
npx vite build
npm run dev
```

### Prerequisites

- You will need to have Node.js installed on your machine. You can download it from [here](https://nodejs.org/en/download/).
- You will need to have a GitHub account. You can create one [here](https://github.com/).
- [PnPm](https://pnpm.io/) is not required, but greatly improves proformance. You can install it with `npm install -g pnpm`.

### Using TailwindCSS with Svelte

- To use TailwindCSS in the ```<style>``` tag, import tailwind classes in the following way:
  ```
  <style>
    @tailwind base;
	@tailwind components;
	@tailwind utilities;
  </style>
  ```  


#### Hacktoberfest 2023

This repository is for Hacktoberfest 2023. Join us in creating a fun game for everyone to play while learning about SvelteKit, TailwindCSS and Socket.io.

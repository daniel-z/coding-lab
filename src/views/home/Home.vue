<template src="./Home.html"></template>
<style lang="scss" src="./Home.scss" scoped></style>

<script>
const codeExperiments = [
  {
    name: "Vision Player",
    links: {
      code: "https://github.com/daniel-z/visionplayer",
      preview: "https://visionplayer.danielzamorano.pro/"
    },
    description:
      "I created a web music player that combines music with HD background images. I decided to experiment using Spotify & Unsplash APIs and learn Angular + Ngrx.",
    tags: [
      "Angular",
      "NGRX",
      "Babel",
      "Webpack",
      "node",
      "npm",
      "spotify",
      "unsplash",
      "REST",
      "API",
      "Saas"
    ]
  },
  {
    name: "Particles Tracker",
    links: {
      code: "https://github.com/daniel-z/particles-pointer-tracker",
      preview: "https://particles.danielzamorano.pro"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm", "Saas"]
  },
  {
    name: "Photos Api",
    links: {
      code: "https://github.com/daniel-z/unsplash-api",
      preview: "https://photo.danielzamorano.pro"
    },
    description:
      "New experiment with nodejs api framework: https://feathersjs.com/. I created an api to get HD pictures powered by unsplash.",
    tags: [
      "unsplash",
      "feathers",
      "ES6",
      "node",
      "npm",
      "Webpack",
      "Babel",
      "Refactoring"
    ]
  },
  {
    name: "Console Typer",
    links: {
      code: "",
      preview: "https://danielzamorano.pro/#/experience"
    },
    description:
      "Funny util written using pure javascript to give a terminal typing effect to any paragraph.",
    tags: ["ES6", "Fun", "node", "yarn", "Webpack", "Babel"]
  },
  {
    name: "Code Experiments Page",
    links: {
      code: "https://github.com/daniel-z/coding-lab",
      preview: "/"
    },
    description:
      "I decided to add this here as I used it as a prototype to learn VueJS.",
    tags: ["Vue", "Saas"]
  },
  {
    name: "Ecommerce Sample",
    links: {
      code: "https://github.com/daniel-z/react-audition-ecommerce",
      preview: "https://stackblitz.com/edit/react-audition-ecommerce"
    },
    description:
      "Ecommerce page sample used as recruiting exercise using react. Using cloudinary CDN and stackblitz for live coding. I ported this same code to angular.",
    tags: [
      "React",
      "Cloudinary",
      "CDN",
      "ES6",
      "node",
      "npm",
      "Webpack",
      "Babel",
      "Stackblitz"
    ]
  }
];

export default {
  name: "home",
  data: () => {
    return { codeExperiments };
  },
  components: {}
};
</script>

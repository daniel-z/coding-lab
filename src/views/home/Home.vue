<template src="./Home.html"></template>
<style lang="scss" src="./Home.scss" scoped></style>

<script>
const codeExperiments = [
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    previewUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    image: {
      url: "https://placekitten.com/800/800",
      alt: "particles project preview image"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    previewUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    image: {
      url: "https://placekitten.com/800/800",
      alt: "particles project preview image"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    previewUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    image: {
      url: "https://placekitten.com/800/800",
      alt: "particles project preview image"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    previewUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    image: {
      url: "https://placekitten.com/800/800",
      alt: "particles project preview image"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    previewUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    image: {
      url: "https://placekitten.com/800/800",
      alt: "particles project preview image"
    },
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring", "node", "npm"]
  }
];

export default {
  name: "home",
  data: () => {
    const processCodeExperiments = codeExperiments.map(cexperiment => {
      return {
        ...cexperiment,
        imageStyle: {
          "background-image": `url("${cexperiment.image.url}")`
        }
      };
    });
    console.log(processCodeExperiments);
    return {
      codeExperiments: processCodeExperiments
    };
  },
  components: {
    // HelloWorld
  }
};
</script>

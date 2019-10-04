<template src="./Home.html"></template>
<style lang="scss" src="./Home.scss" scoped></style>

<script>
const codeExperiments = [
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring"]
  },
  {
    name: "Particles Tracker",
    repoUrl: "https://github.com/daniel-z/particles-pointer-tracker",
    description:
      "2D animation using canvas and ES6, is a complete refactoring and code improvement of a code sample I found in codepen.",
    tags: ["ES6", "Webpack", "Babel", "Refactoring"]
  }
];

export default {
  name: "home",
  data: () => {
    return {
      codeExperiments
    };
  },
  components: {
    // HelloWorld
  }
};
</script>

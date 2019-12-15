# VueJS Large Project RoadMap in 2020

in this tutorial you will learn vue js advanced configurations for a project.


## HighLights

- ### [Installing Vuejs](#installing-vuecli)

- ### [Create A New VueJS Project](#create-vuejs-project)

- ### [Project Options Selection](#project-options-selection)
  - [What is Babel ?](#what-is-babel)
### Installing Vue Cli {#installing-vuecli}

To install vue cli, run:
```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```


### Create a new VueJS Project {#create-vuejs-project}

To create a new project, run:

```
vue create hello-world
```
Then select "Manually select features".

![create a new vuejs project](https://raw.githubusercontent.com/ebubekirtabak/vuejs-large-project-road-map-in-2020/master/images/select_features.png)

### Project Options Selection {#project-options-selection}

Select features what you want for your projects.

I selected Babel, Css pre-processors, Router, Vuex, Linter, Unit Testing, E2E Testing

![project options selections](https://raw.githubusercontent.com/ebubekirtabak/vuejs-large-project-road-map-in-2020/master/images/project_options_selection.png)

Let's explain that's features.

#### What is Babel ? {#what-is-babel}
---

>Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. Here are the main things Babel can do for you:

- Transform syntax

- Polyfill features that are missing in your target environment (through @babel/polyfill)

- Source code transformations (codemods)

- And more! (check out these [videos](https://babeljs.io/videos.html) for inspiration)

```javascript
// Babel Input: ES2015 arrow function
[1, 2, 3].map((n) => n + 1);

// Babel Output: ES5 equivalent
[1, 2, 3].map(function(n) {
  return n + 1;
});
```

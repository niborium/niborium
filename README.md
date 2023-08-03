### Robin Karlsson (Niborium)

Take a look at my homepage https://robinkarlsson.se or take a look at my published npm packages https://www.npmjs.com/~niborium  
Also have some repositories from my school projects and also my hobby projects.

````
const robinKarlsson = {
  name: "Robin Karlsson",
  jobTitle: "Systemutvecklare | Webbutvecklare | Software Developer | Web Developer",
  expertise: [
    ".NET",
    "C#",
    "JavaScript",
    "React",
    "TypeScript",
    "Blazor",
    "Selenium",
    "Cypress"
  ],
  hobbies: [
    "Spend time with family and friends",
    "Coding",
    "Skiing",
    "Chess",
    "Music Production",
    "Tech"
  ],
  catchPhrase: "Building amazing software, one line of code at a time!",
  get introduction() {
    return `Hi, my name is ${this.name} and I am a ${this.jobTitle}. I have expertise in technologies like ${this.expertise.join(", ")}. When I'm not coding, you can find me ${this.hobbies.map(hobby => `enjoying ${hobby}`).join(", ")}. ${this.catchPhrase}`;
  }
};

console.log(robinKarlsson.introduction);
````

[![trophy](https://github-profile-trophy.vercel.app/?username=niborium)](https://github.com/ryo-ma/github-profile-trophy)

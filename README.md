<h1 align='center'>Hi 👋, I'm Fernando Tagliaferro</h1>
<h3 align="center">Full-Stack Software Engineer</h3>


### /about-me
```javascript

app.get("/about-me", (req, res) => {
  res.send({
    firstName: "Fernando",
    lastName: "Tagliaferro",
    pronouns: "He | Him",
    interests: ["coding", "technology", "travel", "coffee", "pet",  "soccer", "photography"],
    askMeAbout: ["coding", "travel", "coffee"],
    technologies: {
      programming: ["Javascript", "Typescript", "Java", "PHP"],
      frontEnd: ["HTML", "CSS", "JavaScript", "React", "Angular"],
      backEnd: ["Node.js", "Express.js", "Spring Boot", "PHP"],
      database: ["mySQL", "PostgreSQL", "Oracle", "mongoDB"],
      devops: ["CI/CD", "Docker", "Docker Swarm", "Kubernetes", "RabbitMQ", "Sonar"],
      conventions: ["Design Patterns", "GitFlow", "TDD", "Clean Code", "SOLID", "Clean Architecture"],
    },
    currentlyLearning: ["Next.js", "Tailwind CSS", "NestJS", "Prisma ORM"],
  });
});

```

### /contact
```javascript

app.get("/contact", (req, res) => {
  res.send({
    email: "nandotag@outlook.com",
    location: {
      city: "Campinas",
      state: "São Paulo",
      county: "Brazil",
    },
    company: "Self-employed",
    jobTitle: "Full-Stack Developer",
    website: "",
    socialMedia: {
      linkedin: "https://www.linkedin.com/in/fernandotag",
      medium: "",
    },
  });
});

```

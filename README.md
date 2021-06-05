```typescript
interface Profile {
  pronouns: string;
  code: string[];
  technologies: {
    frontend: { [key: string]: string[] };
    backend: { [key: string]: string[] };
    databases: string[];
    serverless: string[];
    devOps: string[];
    misc: string[];
  };
  architecture: string[];
  funFact: string;
}

const Jason: Profile = {
  pronouns: 'He' || 'Him',
  code: ['Javascript', 'Typescript', 'Go', 'PHP', 'Python'],
  technologies: {
    frontend: {
      js: ['React', 'Vue'],
      css: ['Bootstrap'],
    },
    backend: {
      js: ['Node', 'Express'],
      go: ['Revel', 'Gin'],
      php: ['Laravel'],
      python: ['Flask'],
    },
    databases: ['MySQL', 'MongoDB', 'Amazon DynamoDB'],
    serverless: ['Amazon S3', 'AWS Lambda'],
    devOps: ['Docker', 'Kubernetes'],
    misc: ['Bash', 'Vim'],
  },
  architecture: ['MVC', 'SPA', 'Microservices', 'Event-driven'],
  funFact: 'There are two ways to write error-free programs; only the third one works',
};
```

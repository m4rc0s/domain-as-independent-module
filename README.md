# Domain as Independent Module

Versioning some notes about an ideia that stands to keep the domain rules development isolated from application development in all aspects, for example:

- Product Development Workflow;
- Release Management and Deploy Strategies;
- Development Workflow;

And more... but I not shure what yet!

# Objective

For noew the main objective is create a very simple independent domain module that will have your own release strategy and create an application component that will orchestrate the process and use the domain module as a dependency to enable application to work according to business;

# Ideias behind it

- Keep focus on problem space instead solution space;
- This is from solution space but totally focused in attends problem space rules;
- The part of solution space that keeps people near from real business problem as the way you expose your application to the world, or where you store your data becomes to make senes in isolated context specific to talk about the solution;
- Test MUST be yout friend here, use them to ensure the business requirements;
- Keep your domain module ahead of your application component, it will make you think about the business befor think about where your application will be hospedated or where is your data, you dont need them to run your business rule;
- Think about business rules as a independent engine that composes your achitecture;
  

# Ideia Version

beta-0.0.1

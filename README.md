# Domain as Independent Module

Versioning some notes about an ideia that stands to keep the domain rules development isolated from application development in all aspects, for example:

- Product Development Workflow;
- Release Management and Deploy Strategies;
- Development Workflow;

And more... but I not shure what yet!

# Objective

For now the main objective is create a very simple independent domain module that will have your own release strategy and create an application component that will orchestrate the process and use the domain module as a dependency to enable application to work according to business;

# Ideias behind it

- Keep focus in problem space instead solution space;
- The domain system come from solution space but totally focused to attends `problem space` requirements;
- The solution space doubts that keep people far from real world business problems as "the way you expose your application to the world", or "where we will store our data" becomes to make sense in another isolated context that is specific to talk about the solution;
- Tests MUST be your friends here, use them to ensure the business requirements;
- Keep your domain module ahead of your application component, it will make you keep a space for business module in your product dicovery chain; think about the business before think about where your application will be hosted or where is your data, you dont need them to run your business rule;
- Think about business rules system as a independent engine that composes your achitecture;
  

# Ideia Version

beta-0.0.1

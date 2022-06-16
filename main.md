# Domain as Independent Module

Domain as Independent Module principle: design specific system that handle your domain processess, appying their business rules, this system should be treated as dependency, must be something like library; then it will be used by your applications which will interacts with the domain using an Interaction Specification Model;

> 
> The same team should maintain the domain and application system;
> 

## Keep your domain available

- Versioning
- Development pipeline
- Distribution strategy

## Business changes management

The business should determines when the domain changes;

When Domain System Dependency change, applications that depends on these domain rules should adapt their orchestration rules to attends the changes;

# Behaviour and Orchestration

# Domain Systems

# Application Systems

# Interaction Specification Model

This is the model that your determines for your domain system to communicate with applications

# Practical Approach

The Jon Doe is the CEO of the Sunny Yard Veggie Logistic an amazing company that intermediates delivery of vegetables connecting small and medium producers with restaurants, supermarkets and others; Now the CEO wants to expand their  business attending to people that wants to receive fresh vegetables at their houses and after a lot of research he decided that the better way to achieve this objective is linking their ligistic business chain with a new area that will manage the client order process from the start until the end, and they will be integrated with some channels to get in touch with the customer, for that they will build an app; So now is necessary to have some Services handling the business process the user interactions with their logistic process; 
To build these Services we will implements a full platform using the Sunny Yard Veggies problem space as study case aiming to apply the Domain as Independent Module approach; 

# References

- [Getting Started with ECS](https://bevyengine.org/learn/book/getting-started/ecs/)
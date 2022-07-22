# Typescript-RR-Music-Library
### RR to Typescript
- ### Activity: Convert Your Full-Stack Project
Migrating projects to TypeScript can seem intimidating at first. However, the more you do, the more comfortable it begins to feel. For small-scale projects, you may not catch much. But recall that 38% number from AirBnB-and remember, that number came from experienced developers.

Your job now is to spend the last hour of this TypeScript course migrating your full-stack project to TypeScript. You'll want to start with the front end to cement your familiarity with TypeScript with React, then move on to the back end.

- ### Part 1: Make a Plan
Determine how you're going to perform your migration. As already suggested, you should move from the front end to the back end to become more familiar with typed React.

## Ask yourself the following:

Are there any extra type definitions that I should add?
In what order should I migrate my components?
Can I think of anything from the project that I may need to look out for or could be especially difficult?
- ### Part 2: Install and Begin the Migration
It's time to get working with TypeScript. You'll want to follow similar steps from the code along in the previous lesson.

Install TypeScript on the front end, including any additional type definitions.
Name all your JS files to TSX files and start the server so your application recognizes TypeScript and adds the configuration.
Handle any quick-fix errors that you see in your project.
Type all errors as any so that your project compiles.
- ### Part 3: Type Your Front End
Go through the process of moving from any to the types covered in previous lessons. Start with your most simple component and work your way to the parent components.

Are there interfaces that you could add to your definitions file to reduce code bloat?
Are there types that you could explicitly add to make your functions easier to understand?
If you find places where you cannot replace any successfully, make a note of them and continue with your project. Save these for office hours, or make it a point to ask on a site like Stack Overflow. The type may reveal itself as you get further into the project.

- ### Part 4: Compile Your Front End
Assuming that your front end is fully typed, it's time to compile. Make sure that your front end continues to work as expected before moving on. If not, check the console for errors, then look for any types you may have missed. If you don't see anything, check that the application still works in development mode. If it's still not working, make a note to ask about it during office hours.

- ### Part 5: Install TypeScript and Configure It on Your Back End
You'll set up TypeScript the same way you did when you migrated your Game Project.

Remember to add all the necessary dependencies for any npm packages you have added.
Remember to make the changes needed to work with nodemon.
Set up the configuration file with the location where your code should compile, the libraries it will need, and make sure to set it to 'strict'.
- ### Part 6: Begin the Migration
Follow the same steps you followed for the front end. Make sure that your project still works once all types that aren't obvious are typed as any.

- ### Part 7: Type Your Back End
Again, follow the instructions for the front end. Make sure to check your routes as you go. You may be dealing with more asynchronous code on your back end. Don't hesitate to check your notes on generics and asynchronous TypeScript. You may also run into some type assertion issues or even need to do some minor restructuring.

- ### Part 8: Compile Your Back End to Test the Full Application

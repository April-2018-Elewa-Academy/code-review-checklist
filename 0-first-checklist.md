

## Reviewer

### Why reviewing code?

 - Are there any obvious logic errors in the code?
 - Looking at the requirements, are all cases fully implemented?
 - Are the new automated tests sufficient for the new code? Do existing automated tests need to be rewritten to account for changes in the code?
 - Does the new code conform to existing style guidelines?

### Reviewing process


 - Prioritize goals for code review (e.g. catch bug? understand the way each other think?... think about what is the goal of one particular review) 
 - Use the app/ the perspective of the user to review (detect problems)  
 - Set up a timeframe (do them immediately)  
 - Copy to another repository / work in isolation (read code in a realistic environment)  
 - Imagine your own solution before reviewing  
 - Quiz yourself on their code to make sure you understand it
 - Write an explanation of how you think their code works and why
 - Limit yourself to an hour at a time
 - Make visual representations/diagrams (figure out/understand) what their code is doing (concrete take away)
 
 ### before request - developer
* Provide a clear and focused list of concerns & features to be reviewed
* Annotate your code when necessary
* Create a separate branch with (as much as possible) only the code to be reviewed
* Provide a this template in your project with your "before" section completed

### during request - reviewer
* Critique the code, not the coder
* Comment on behavior, not implementation
* Be prompt.  If you can't do this review, help them find someone who can
* Isolate their code in a new repository for simpilcity and focus
* Investigate the code in your own development environment
* Limit yourself to an hour at a time
* Provide positive, constructive, feedback
* Trust your developer, when in doubt approve their code

### after request - developer
* Read your code reviewer's explanation of your code.  Get back to them:  
  * Were they right about what you intended?
  * Did you learn something from their interpretation?
  * Did they mis-understand something key?
* Trust your reviewer. Implement their suggestions unless they're flat-out wrong:
  * This will help to promote a more stylistically consistent code base.

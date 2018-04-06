
## Developer

### Before Request

* Review thoroughly your code before asking for a review.
* Make sure specifications are complete and well documented.
* Fill out the checklist, add it to your project repository, and mention it (refer the file) in your review request.
* Provide a clear and focused list of concerns & features to be reviewed
 * Annotate your code when necessary (Mark/refer all concerns and features in your list in the actual code - add a comment with a fixed "Issue Name" in your code and use the same name in the list.
      
### After Request

* Read your code reviewer's explanation of your code.  Get back to them:  
  * Were they right about what you intended?
  * Did you learn something from their interpretation? (* Take notes (even if just mental) of new solutions and the things you've learned.)
  * Did they mis-understand something key?
* Trust your reviewer. Implement their suggestions unless they're flat-out wrong:
  * This will help to promote a more stylistically consistent code base. 
* Keep an open mind and consider the feedback as an opportunity to learn.


## Reviewer

### Important questions

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


### during request - reviewer
* Critique the code, not the coder
* Comment on behavior, not implementation
* Be prompt.  If you can't do this review, help them find someone who can
* Isolate their code in a new repository for simpilcity and focus
* Investigate the code in your own development environment
* Limit yourself to an hour at a time
* Provide positive, constructive, feedback
* Trust your developer, when in doubt approve their code


## Notes for later
* Create a separate branch with (as much as possible) only the code to be reviewed
* If possible indicate the type of struggle (e.g. "check for syntax errors", "check for performance", "check for functionality" etc etc)
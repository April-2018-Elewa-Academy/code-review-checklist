# Code Review Checklist


## developer

* before request




* after request

any errors?
full implement?
automation test?
need to rewriting?
spec match?

2 reviews before merge to master. 
=======

## Evan's contribution


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
* Run the code. It will be easier to get it by itneraction than by code reading
* Diagram the code's behavior
* Quiz yourself on their code to make sure you understand it
* Write an explanation of how you think their code works and why
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

## reviewer
* during request


any errors?
full implement?
automation test?
need to rewriting?
spec match?

1)concrete  
    errors  
    matching specs - is it what it should be  
2)concrete  
    don't work for more than an hour, your brain can't handle it and you'll miss bugs. don't look at more than 400 lines per hour
    annotate your code BEFORE asking for a code review  
3)concrete  
    as early as possible     
    point out essentials, not everything  
    each change gets a pull request  
4)concrete  
    developers  
      -be your first reviewer 
      -have checklist  
5) - prioritize goals for code review (e.g. catch bug? understand the way each other think?... think about what is the goal of one     particular review) (concrete take away)  
  - use the app/ the perspective of the user to review (detect problems)  
  - set up a timeframe (do them immediately)  
  - copy to another repository / work in isolation (read code in a realistic environment)  
  - imagine your own solution before reviewing  
  - make visual representations/diagrams (figure out/understand) what their code is doing (concrete take away)  



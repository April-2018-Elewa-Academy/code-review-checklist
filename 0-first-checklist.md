# Code Review Checklist


## developer

* before request


      be your first reviewer
      have checklist
      
* after request

## Reviewer
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


 kidn to the coder, not the code
 respect juniorer developers
 avoid "why" questions
 know standards


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


# Mariana's contribution - Checklist

## Developer

### Before Request

* Define and document acceptance criteria

 * Acceptance crteria is a thorough description the end state functionality the code is supposed to perform (e.g. for a code intended to work as a calculator acceptance criteria would be:
 - perform SUM correctly  
 - perform multiplication correctly  
 - etc etc)

* Specify (make a list) potential struggles

 * By potential struggles we mean areas in the code which were more challenging to develop and therefore may contain potential errors. Or pieces of the code which contain an implemented solution which you are not sure is the best possible one(simplest, most performant etc).
 * Indicate where in the code the struggle is located (mark it with a specific comment?)
 * If possible indicate the type of struggle (e.g. "check for syntax errors", "check for performance", "check for functionality" etc etc)

### After Request

* Keep an open mind and consider the feedback as an opportunity to learn.
* Review all feedback (or at least try to).
* Reply to your reviewer (even if it's just to thank them for the review)
* Take notes (even if just mental) of new solutions and things you've learned from the review.

## Reviewer

### During Request

* Take your time to review. Be patient
* Review acceptance criteria and verify if it contains all functionality the project/code is supposed to perform.
* Try to understand fully the code before commenting.
* Review carefully all "potential struggles" pieces and reply with a specific commentary. Be as specific as you can demonstrating you have examined the code thoroughly and why you like/dislike the solution.
* Always add references to the related piece in the code when offering a comment.
* Run the code and verify if it meets the specified acceptance criteria.

### After Request

* Keep the conversation going if/when new information or differences of opinion emerge.
* Keep an open mind and consider the feedback as an opportunity to learn.
* Review all feedback (or at least try to).
* Take notes (even if just mental) of new solutions and things you've learned from the review.

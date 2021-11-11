# Living in the grey area of Exceptions

### Exception management processes
- determine what exception priorities are 
- get aligned on goals and solutions for exceptions that pop up
  - be able to see signals through the noise of errors to help prioritize exceptions 
  - have collective team ownership of addressing exceptions 
  - proactively address exceptions
- exceptions can be solved collectively over time
- learn to write bug stories so that you can provide context for whatever developer ends up addressing the exception
- identify levers for efficiency 
- create custom exception handlers in complex parts of the codebase to provide more robust errors 
- put into place error grouping so that you are not being flooded by lots of the same exception 

### Understanding the Error
- if the exception isn't clear, do research to understand all the parts of the error message 
- look through the stacktrace provided in the error to pinpoint areas in the code that need to be examined  
- try to reproduce the error locally 
- try and find patterns in past occurrences of the error

### Determining priority 
- determine what the user impact is of this error
- determine how often this error has been happening

### Steps to handling exceptions:
- diagnose and determine priority
- decide:
  - fix issue
  - create bug ticket
  - ignore issue

### Ideas 
- have a rotating pair to triage exceptions daily 
  - have a process put in place to show acknowledgment of exceptions by developers and what action was taken with that exception
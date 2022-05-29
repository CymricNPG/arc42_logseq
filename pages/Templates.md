- # Decision record template by Michael Nygard
  
  This is the template in [Documenting architecture decisions - Michael Nygard] http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions). You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.
  
  In each ADR file, write these sections:
	- # Title
	  template:: ADR
		- ## Status
			- What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?
		- ## Context
			- What is the issue that we're seeing that is motivating this decision or change?
		- ## Decision
			- What is the change that we're proposing and/or doing?
		- ## Consequences
			- What becomes easier or more difficult to do because of this change?
- Black Box Template
	- ### \<Name black box 1>
		- ==Hints:==
		  collapsed:: true
			- Here you describe \<black box 1> according the the following black box template:
			- Purpose/Responsibility
			- Interface(s), when they are not extracted as separate paragraphs.   This interfaces may include qualities and performance characteristics.
			- (Optional) Quality-/Performance characteristics of the black box, e.g.availability, run time behavior, ....
			- (Optional) directory/file location
			- (Optional) Fulfilled requirements (if you need traceability to requirements).
			- (Optional) Open issues/problems/risks
		- *\<Purpose/Responsibility>*
		  
		  *\<Interface(s)>*
		  
		  *\<(Optional) Quality/Performance Characteristics>*
		  
		  *\<(Optional) Directory/File Location>*
		  
		  *\<(Optional) Fulfilled Requirements>*
		  
		  *\<(optional) Open Issues/Problems/Risks>*
		- ### \<Name black box 2>
		  
		  *\<black box template>*
		- ### \<Name black box n>
		  
		  *\<black box template>*
		- ### \<Name interface 1>
		  
		  ...
		- ### \<Name interface m> {#__name_interface_m}
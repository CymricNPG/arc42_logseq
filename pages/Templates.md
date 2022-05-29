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
	- ### \<Name black box/Interface>
	  template:: Black Box/Interface
		- ==Hints:==
		  collapsed:: true
			- Here you describe \<black box 1> according the the following black box template:
			- Purpose/Responsibility
			- Interface(s), when they are not extracted as separate paragraphs.   This interfaces may include qualities and performance characteristics.
			- (Optional) Quality-/Performance characteristics of the black box, e.g.availability, run time behavior, ....
			- (Optional) directory/file location
			- (Optional) Fulfilled requirements (if you need traceability to requirements).
			- (Optional) Open issues/problems/risks
		- **Purpose/Responsibility**
			- *\<Purpose/Responsibility>*
		- **Interfaces(s)**
			- *\<Interface(s)>*
		- **Quality/Performance Characteristics**
			- *\<(Optional) Quality/Performance Characteristics>*
		- **Directory/File Location**
			- *\<(Optional) Directory/File Location>*
		- **Fulfilled Requirements**
			- *\<(Optional) Fulfilled Requirements>*
		- **Open Issues/Problems/Risk**
			- *\<(optional) Open Issues/Problems/Risks>*
- White Box Template
	- ### White Box *<building block X>*
	  template:: White Box
		- *...describes the internal structure of building block X.*
- Infrastructure Template
- ***\<Overview Diagram>***
- **Motivation**
	- *\<explanation in text form>*
- **Quality and/or Performance Features**
	- *\<explanation in text form>*
- **Mapping of Building Blocks to Infrastructure**
	- *\<description of the mapping>*
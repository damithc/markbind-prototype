<seg id="def-NFR" title="Non Functional Requirements"> 
In contrast to __Functional Requirements__ which specify what the system should do, 
__Non-Functional Requirements__ specify the constraints under which system is developed and operated. 
</seg>

<note id="nfrs-in-a-nutshell" title="NFRs in a Nutshell" styles="big,important,right">
FRs are about **WHAT** a system does; NFRS are about **HOW** the system does those things
</note>

<seg id="def-examples" title="NFR examples"> 
Some examples of Non-Functional Requirements:
* Data requirements e.g. size, volatility, persistency etc., 
* Environment requirements e.g. technical environment in which system would operate or need to be compatible with. 
* Accessibility, Capacity, Compliance with regulations, Documentation, Disaster recovery, Efficiency, Extensibility, 
  Fault tolerance, Interoperability, Maintainability, Privacy, Portability, Quality, Reliability, 
  Response time, Robustness, Scalability, Security, Stability, Testability, and more ...
</seg>


<seg id="level5-more-examples" title="More examples">
More NFR examples...  
</seg>  

<seg id="level4-importance" title="Why NFRs are Important?">
Non-functional requirements are easier to miss. We should spend extra effort in digging them out as early as possible 
because sometimes they are critical to the success of the software. 
E.g. A web application that is too slow or that has low security is unlikely to succeed even if it has all the 
right functionalities.   
</seg>

<seg id="level2-question-peformance" title="Is this an NFR?">
<question>Is this an NFR? _The webpage must load within 5 seconds._
<answer>Yes</answer>
</question>
</seg>

<seg id="level3-question-pick" title="Which ones are NFRs?">
<question>Which of these are NFRs?
- [ ] The system must be secure
- [ ] The system must be fast
- [ ] The system must allow adding accounts
<answer>
- [x] The system must be secure
- [x] The system must be fast
- [ ] The system must allow adding accounts
</answer>
</question>
</seg>
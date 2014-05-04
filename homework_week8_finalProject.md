#Quality Assurance Plan#

Quality assurance (QA) can be viewed to ensure that few, if any, defects remain in the software system when it is delivered to its customers or released to the market. Furthermore, we want to ensure that these remaining defects will cause minimal disruptions or damages.

Dian-Dian is an app in mobile device which can help users to memorize words efficiently and quickly. The whole system will use card to help user to recite words and it’s operation would be easy for that the users would be in different ages. As we now want to assurance the quality of Dian-Dian System，we would go through the whole life-cycle of the development of Dian-Dian to assurance the quality to meet the expectations of the customers. We assume that the software development process of Dian-Dian is waterfall process. Then we can illustrate the quality assurance activities from phase to phase.

## Early phases ##

Early phases include requirement phase, design phase and coding phase, in these phases, we focus on defect prevention. Because of the possibilities of defect propagations and the increasing cost over time or successive development phases to fix defects once they are injected into the system, we need to reduce the number of faults by defect prevention that can help remove software faults early.

Various defect prevention activities are concentrated in early phases before actual faults have been injected into the software systems.  There are two general strategies for defect prevention:

- Error  blocking:  Identifying common errors,  which  are defined to  be  missing or incorrect human  actions, and  blocking them  to  prevent fault injections.

- Error source removal:  Identifying common error sources and removing them, thus 
preventing fault injections. 

In Dian-Dian System we can apply inspection which based on error source removal strategy. We can inspect requirement documents and product specifications in requirement phase, different levels of product designs in design phase, and source code in coding phase. For the detection technique, we can use checklist-based defect detection which is widely used to ensure coverage of important areas for inspection.

Besides, in Dian-Dian system we can apply some other techniques such as following well-defined standards, and methodologies, or using appropriate tools to help block identified common errors. On the other hand, we can use activities that focused on people and their product and process knowledge can be carried out to removal these identified error sources, such as through education and training, process maturity and improvement initiatives, and other techniques specifically based on causal analysis of injected or potential faults.

## Testing Phases ##
In this phase, we focus on defect removal.

1 validation activities & verification activities

- Validation activities includes system testing, acceptance testing and beta testing, usage-based statistical testing, software fault tolerance, software safety assurance activities, which focus on providing the expected accidentfree operations or reducing accident damage when an accident is unavoidable.

- Verification activities check the conformance of a software system to its specifications. When failures are involved in verification activities, we are typically dealing with internal system failures and overall system failures in the form of incorrect behavior, instead of the evidence of presence or absence of certain functions or feature directly observable by customers. 

2 external speciﬁcations (black-box)

3 internal implementation (white/clear-box) 

In Dian-Dian system we can divide it into two parts: one is the front app and the other is the backend server. The front app has following functions:
       
		Register and login
		Functional Wizard
		Card learning
		Rewards
		Setting
		User switch and management
The backend server has following functions:
		
		Database and controlling of the database
		Algorithm for users’ learning schedule and repeat of the words
		Words’ version control
		Purchase for more words to learn
		Safety for user data and card data.

We have to figure out what is input and what is output and then we can design test cases to test all functions covered all aspects.


## Late Phases ##

Late phases include release and support phases.In these phases, we focus on defect containment.

Finally, failure prevention and containment activities, such as fault tolerance and safety assurance, are typically the focus of operational phases.  However, their planning, design, and implementation need to be carried out throughout the software development process. In some sense, they are equivalent to adding some necessary functions or features into the existing product to make them safe or fault tolerant.

## Phase transitions ##
When two phase is switching, we focus on inspection/review/etc.
Inspection can be a very effective and efficient way to deal with quality 
problems caused by faults that have already been injected into software systems.
For review, there are two kinds of reviews:informal reviews and formal reviews.informal reviews include self conducted reviews, independent reviews, orthogonality of views desirable.Formal reviews: code reading, code reading by stepwise abstraction, Active design reviews (ADR), Inspection for program correctness.






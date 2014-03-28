#What are the basic concepts of DDG #

Since program execution typically follows a sequential execution 
model, we can view the data dependencies as embedded in the data flow, where the data flow is the mechanism that data are carried along during program execution. The test cases are derived from data dependency analysis (DDA), with a focus on D-U relations, and the related model we call data dependency graph (DDG). 

In DDGs, each node represents the definition of a data item, such as a variable, a constant, and a compound data structure. The links in DDGs represent the D-U relation, or “is used by”.  That is, if  we have a link from A to B, we interpret it as that the data defined in  A is used  to define the data in B. This analysis of chains of D-U relations used in defining later data items can be carried out 
to identify the definitions of those earlier items, until we resolve all the definitions. This backward chaining process, starting from the computational result back to all its input and constants represents the model construction process.

We elaborate on each of these sub-steps below, with a focus on building the DDGs. Once such a DDG is constructed, slice definition and selection is fairly straightforward, and test case sensitization also directly follows. Outcome prediction is also easy with DFT because the selected and sensitized slice directly defines the computational results. Another reason that we  focus on DDG construction is that its form and structure are quite different from the program structure and flow-chart that most software developers are familiar with. 

We next describe the ways to construct DDGs by first examining the specific character- istics of  them, identifying the information sources, outlining a generic DDG construction procedure, and finally an indirect but easy-to-follow procedure for people who are familiar with traditional sequential programming aind flow-charts. 








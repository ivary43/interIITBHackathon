## RCBOT for e-commerce
A conversational helper bot that makes ordering products online effortless for jioPhone users.

Different level of extraction- 
1) First level of extaction is using dialog_flow module for Natural language Understanding. Which helps us in named and known entity extraction.
2) After processing the user request we identify what intent is to be triggered to perform the desired action.
3) A webhook is called upon triggering of the actions.
4) The webhook requests the node.js server to perform appropriate action based on intent and data passed. This then calls the webstore APIs for the e-commerce sites.

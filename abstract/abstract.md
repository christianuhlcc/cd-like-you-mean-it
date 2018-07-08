## Continuous Delivery like you know no fear

Warning: This talk can make your own release process seem awfully slow and risky! Everybody does Continuous Integration - more or less, but I think a modern CD pipeline can fundamentally change the way we are collaborating while building Software. At Matmatch we're pushing the boundaries of what Continous Delivery can be by leveraging Gitlab and Kubernetes: Every Branch gets deployed into its own enviroment - and the Product Manager or the Stakeholder can release every feature directly to production with the click of a button. We don't bundle releases anymore, every feature goes straight to production. Goodbye test systems, good riddance staging processes.

Why did we, as a small startup, bother with pushing that system to its limits? To get faster Feedback and to minimize Risk! By releasing and failing faster than the rest, we are outpacing others when it comes to opportuinties to learn. It's a joy to work that way and and we could never imagine going back.

In this talk I will walk you through our pipeline, the hickups we had along the way to build it and the benefits we get from having this pipeline in place. 
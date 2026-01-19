<!-- aap product jitna use kroge performance utna improve hota rhega  -->
<!-- dynamically model naye data pe model train hota rhta hai  -->
incremental training hoti hai isme & model improve after every training : : in small batches 

## ye aapka model tb train ho rha hai jab model phle se hi server pe hai 

small batch of data -> model -> test -> server pe bhej dia -> server has a inflow of continuesly new data -> model predict & learning and new data 

### eg.
chatbot of famous companies : deployement ke time pe naye data ko pakad ke improve bhi ho rhe hai 

swift key keyboard :: dyanimically performance improve hota rhta hai (maybe they used online learning in it )

youtube is the biggest example : your feed changes after you watched some video the related content aata rhta hai



## when to use WHAT?

where there is a concept drift : 
if the nature of problem changing rapidly : eg. stock changes ( online learning

cost effective : online learning is more cost effecttive 

faster solution : 


## how to implement 


<!-- learning rate  -->

how frequently you want to train your model on the coming dataflow


<!-- out of core learning  -->
 when you can;t load the big dataset : then you do online learning

huge Dataset In GBs : we convert into small dataset : each small dataset ko 1-1 krke aap usko bhejoge to the model 


## <!-- Disadvantages  -->
Tricky to use 
Risky 

1) data handleing managemnet (huge dataset)
2) when model is free to train on the new datset the new anamoly (hacker maybe or anyother identity that want to ruin your model )
3) so you have to create some risk management algo to fix the model learning (maybe server offline and  )

server offline krke model ko pichle state me rollback krke : fir se live krna {ye sb aana chahiye}



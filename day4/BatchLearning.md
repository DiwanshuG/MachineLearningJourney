<!-- batch Vs Online ML  -->

machine learing models different servers per differently behave krte hai 
uske hisaab se ML ke parts hain 

1 Batch vs Online ML


1) Batch Learning (Offline ML)

conventional way of training model : model ko ek baar me saare data ko train krte hain : training me complete data use hota hai 
incremental training nhi hoti 

aap model ko apne machine pe train krte ho aur : trained model ko aap server pe daal ko , that's called batch learning 

Data   ->  Model   -> test    -> then usko server pe daal do :: ML model predict krta rhega 



# problem with batch learning 
time ke sath model up to date nhi rhta 
model ko retrain krwana pdhta rhta hai :: on new data as the data changes 
jaise hi data update ho rha hai : aapko model dobaara se train kraana pdhta hai :: test kro :: then again server pe daalo  (repeat hota rhta hai )

depends on data size  :)  time at which the data is changing ::)  
so mainly model ko weekly train krte hain :: kyuki entire data ko dobara train krna pdhta hai ::


# Disadvantage 
Lots of Data
Hardware Limitation 
Availaibity



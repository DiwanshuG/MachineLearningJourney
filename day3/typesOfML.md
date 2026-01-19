# types of ML

1) supervised learning 
Regression , Classificatio

2) Unsupervised Learning
Clustering , Dimensnality Rduction , Anamoly Detetection , Association 
3) Semisupervised Learning 
4) Reinforcement Learning 




## Supervised Learning 

labeled dataset se naye input ke prediction kar paao 

5000 students data 

iq | cgpa | y/n placement

87 | 7.1  | y
111| 8.9  | y
75 | 6.3  | n

here we have input and output both 

2 part : 
# Regression & Classification 

data types : numerical data (age weight cgpa ) & categorical data (brand , nationality , gender)

<!-- if output columns of a problem is Numerical Data => Regression  -->
# regression
input -  iq , cgpa 
output - package 

<!-- if output columns of a problem is Categorical Data => Classification  -->

5000 students data 

iq | cgpa | y/n placement

87 | 7.1  | y
111| 8.9  | y
75 | 6.3  | n




## Unsupervised Learning 

5000 students data 

iq  | cgpa 
70  | 8.0
122 | 5.6
132 | 9.1

clustering , Dimensionality reduction , Anamoly Detection , Association rule learning 

# Clustering 
actually u can plot the above data on a 2d plane 

now clustring algo will be able to detect that which group of students are there :
it will make clusters of different types of students and we will be able to classify them 

1) jaise aap different types of dimensional data ko bhi clustring algo se clusters bna skte ho :: very high dimensional data ko bhi :: jo aap imagine bhi nhi kr paate 
group inside groups 


# Dimensionality Reduction 
1) jab bahut jyda input columns ho jaaye 

<!-- inputs columns ko remove kr dega jo relative hai and unko ek column me convert kr dega  -->
feature extract krke into one column [PCA algo hota hai u'll understand in future]


2) jab data ko plot nhi kr skte 
aap data ko 2-3 coordinate system me laake aap plot kr skte hain
eg. MNIST dataset (number images ka data ) that's in 784 dimensional space
aap PCA lgaake : isko 3d me le aate hai   [https://colah.github.io/posts/2014-10-Visualizing-MNIST/]


# Anamoly Detection 

kuch gadbad ho rha hai usko detect krna hai 
mtlb outlier ko htaana hai ya anamoly 


# Assiciation Rule based learning

milk + bread saath me kharida ja rha hai 
to unko sath me rkh denege :: 

case study of ML in walmart: 
baby diaper ke sath | bear ko sath me rkho {in walmart}



# Semi- supervised Learning
google photos : automatically identifiy same person 

aap kisi ek photo btaoge to wo uss person ke saare photos ko ek sath laa dega


# Re inforcement Learning

No data at starting

aap college gye aapko kaise college life me kaise jina hai
self driving car

<!-- Google deepmind  -->
create a agent : jisme ek Go game me 2017 me world champion ko 5 mese 4 baar hraaya tha
<!-- Tensors -->

is a Data Strctures : all the lading libarary in ML/DL spaces : you have to deal with tensors

<!-- tensor is a container for numbers -->
A tensor is a generalized data structure used to represent data in multiple dimensions.
Think of it as an extension of numbers, lists, and tables.


a scalor is 0D scalor


<!-- 1 D TENSOR/ VECTOR -->

2d tensor : 2 axis
number of axis aka rank somewhere

[1,2,3,4] : is a vector 4D : is a 1D tensor
[1,2] : 1D tensor : vecotr 2D

scalor + scalor : vector


<!-- 2D tensors/Metrics -->



<!-- ND Tensors  -->



Rank : number of axes = number of dimensions
Shape: kisi ek particular axis me kitne items store ho skte hai (2,3): (row,columns)
size : number of items in a Tensor

<!-- size of a Scalor is always 1 -->
<!-- vector is 1D tensor par uske dimensions alag hi hote hain  -->



## Example of 1D tensors

students(10000)
cgpa | iq | state | placement


for example we have only states with 0 & 1 

[8.1,91,0] : this is a 1D tensor : or a 3D vector with 3 spaces (iq , cgpa , state)



<!-- example of 2D tensor  -->

cgpa | iq | state  (10000 data)

a collection of 10000 vector is a metrix :  
[        ]
[        ]
[        ]



<!-- example of 3D tensors -->

NLP : natural language processing


Hi Rahul
Hi Ankit 
Hi Diwanshu

the above text is the input text : so we'll vectorise the given input 


Hi | Rahul | Ankit | Diwanshu
1  |  0    |  0    |  0
0  |  1    |  0    |  0
0  |  0    |  1    |  0
0  |  0    |  0    |  1

Hi Diwanshu  : [[1,0,0,0] , [0,0,0,1]]
and all the other data is comes in the form of 3D tensor



:Example 2: 
time series data
(share market data) :
 highest price | lowest Price         for whole year , (365,2) shape      : this will be a 2D vector 
 for this data if we are going to do for 10 years : (10,365,2)  : this will be a 3D vector


<!-- example of 4D vector -->
images data : Computer vision

image is a collection of pixels : 
in three channels (R,G,B) : agar ek ka shape hai 1200,800

ek image : (3,1200,800)  : 3D tensor
collection of images : for example you have 50 images [50,3,1200,800]  : 4D tensors



<!-- example of 5D tensors -->
"collection of videos" 

persistance of vision :  12 images in a second can be classify by the human  


video : frames (60 sec) :: 30 frame per second : 

480p  : 480 x 720 (resolution) with 3 channels

(4 , (1800 , 480 , 720 ,3)) : 5D tensor   , 4 videos 

"5D will be the max in your syllabus" 
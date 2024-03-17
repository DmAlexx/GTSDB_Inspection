Questions
Please answer the following questions:

1. Do you consider the dataset to be balanced? If so, why? If not, why?
   - I don't consider that dataset is balanced. We can see histogram, it shows a wide variation in the number of images across different classes.
   - To achieve a balanced dataset, the number of images for all
   - classes should be roughly equal, with a permissible deviation of up to 20-30%.

     ![image](https://github.com/DmAlexx/GTSDB_Inspection/assets/106063042/74bb5e38-7e35-40b8-a761-d0b33357b08c)

3. Are there any classes that are (significantly) over-represented or under-represeneted?
   - We can categorize the images into subgroups based on their quantity. The largest subgroup contains 12(~29%) classes with approximately 500 images each,
   - followed by 9 (~21%)  classes with around 250 images, and so on, up to 2250 (4 classes ~9%) images per class. 

Optional
Perform a further analysis on the dataset and draw some conclusion from it.

Hint 1: Unlike MNIST or CIFAR10, this dataset contains images with various spatial resolutions. Is there anything we can tell about 
the resolution distribution?
- Let's see on histogram below, the largest number of images has a resolution before 60 pixels, around 38000 images.
  ![image](https://github.com/DmAlexx/GTSDB_Inspection/assets/106063042/925a825a-7fcd-4b4b-aa34-8620ce7500bc)
 
Hint 2: What about the brightness distribution?
- are there classes there are significantly more bright than others?
- Let's see on histogram below,it consider class with class_id - 0, that the bigges of all and it has brighnest above 120.
  ![image](https://github.com/DmAlexx/GTSDB_Inspection/assets/106063042/7c68c8bc-a9e3-4171-a8e8-24dd22172d0e)


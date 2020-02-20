# Movie-Clustering
This was a school project that focused on clustering.
We were given data about movies and what people rated those movies.
I first applied PCA to the data and decided to use a dimensionality of 2 as it would be easier to see 
on a scatter plot
![image](https://user-images.githubusercontent.com/54549208/74963090-23b37f80-53df-11ea-8c6c-68a01d515197.png)
I then decided to apply KMeans to the data. But I first had to decide how many
clusters to use so I created an elbow plot to determine that 8 clusters would be optimal
![image](https://user-images.githubusercontent.com/54549208/74963201-552c4b00-53df-11ea-9e4a-803018f18ccd.png)
Next I applied SVD to the data to compare with a dimensionality of 2 as well so I could compare
it to the PCA graph. However, I wanted this graph to be in color so I could actually see the different
clusters. I applied KMeans with 8 clusters to the data that was transformed by SVD
![image](https://user-images.githubusercontent.com/54549208/74963434-b48a5b00-53df-11ea-8d79-9659511c8e2f.png)

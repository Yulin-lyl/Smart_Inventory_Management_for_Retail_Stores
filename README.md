# Smart_Inventory_Management_for_Retail_Stores

To enhance in store experience and optimize the inventory, Retail Stores are going the extra mile to use technology in never before seen ways. The goal is to build a platform that can be used to track the in store inventory using Camera Vision and get a strong layer of Analytics that tells in real time the sales performance of the products.

The AWS tools used:
 - Amazon Athena
 - Amazon Rekognition
 - Tableau
 - Amazon S3

The platform will keep track of inventory on the shelf using Open CV and the information will be available on a dashboard in real time. The Analytics layer will have information on time of sales of products, the shelf which led to the sales and sales cycle of the products. This information through dashboard will enable the store management to predict inventory placement and sales and thus optimize the in store inventory.

Steps:
1. Capture image using OpenCV
2. Store the data of image in S3
3. Transform image into products and quantity using ReKognition
4. Store the data in S3
5. Data queried and transformed in Amazon Athena
6. Display the trend of inventory in Tableau

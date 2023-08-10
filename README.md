# Data_deduplication_using_dynamic_perfect_hash_techniques
#### ©Copyright  @Md Hasib Hasan
In Computer Science hashing is use for storing data retrieving data in constant time.On the other hand, with a huge use and collection of data, cloud storage has gained popularity among the users. In cloud
storage most of the data is redundant. Cloud storage providers are using deduplication as the mechanism to keep only one copy of the file, by which cloud storage providers are minimizing the storage. But
for deduplication counting of duplicate is required. We are showing a mechanism for data deduplication counting using dynamic perfect hash techniques.
</br>
</br>
As the increasing demand of data rates, cloud storage system has become a necessity for
computer users. But in cloud storage many users upload same type of data like a popular movie,
song, research paper etc. This causes the use of cloud storage inefficient. So, the cloud storage
providers use data deduplication. Data deduplication is the process of removing duplicate data
from the cloud storage.
Data processing
</br>
* Using dynamic perfect hashing for data deduplication makes the counting of
duplicate data easier.
* It helps to keep track of the popular unpopular data.
* It is useful for the retrieval of data in a constant time.
* It makes the data layer more secured in cloud storage because of the two-level
hashing.
</br>
Data deduplication using dynamic perfect hashing plays an important role in cloud storage systems by
eliminating redundant data and reducing storage costs. It helps to optimize storage capacity, backup,
recovery times and security. Identifying popular data in the cloud using dynamic perfect hashing
is a crucial step towards optimizing the performance and efficiency of cloud storage systems. By
understanding which data is popular and in high demand, cloud providers can allocate their resources
more effectively and reduce costs of the storage and retrieval. Additionally, users can benefit from
faster access to popular used data, leading to improved productivity and overall user satisfaction. It
also provides a wide level security to data by two level hashing (which work as encryption). There is
no unmixed blessing on earth this algorithm has some flaws. For rehashing it needs a space on O(n).
Which is costly. It also uses a bucket for counting the popularities. Which is also storage inefficient.
Overall, dynamic perfect hashing provides a reliable way to handle duplicate data in cloud storage
system and can significantly improve the performance of cloud storage for data deduplication.

#### ©Copyright  @Md Hasib Hasan

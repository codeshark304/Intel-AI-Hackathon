# Intel-AI-Hackathon
Team Name: THE 404

Team Lead: Monish Kiran A  

Email: monishkiran304@gmail.com

# Problem Statement
Memory Optimisation in Android Phones using AI/ML.

# Description
The performance of an Android phone is determined by the architecture and the memory management, especially the cache memory utilization. Irrespective of the architecture, for any Android phone the average memory access time (AMAT) can be minimized, thereby enhancing the overall performance of the device. This hackathon idea aims to develop a predictive model to optimize cache memory block utilization, minimize the miss rate and improve Android phone performance.

# Explanation - Idea
The cache memory blocks are small blocks of memory which stores data that needs to be frequently accessed. The cache don't always have an hit rate of 100%. The first cache miss is called as compulsory or cold miss. The first cold miss is inevitable as the cache block is loaded for the first time. The seconf d miss is called capacity and the third miss is called as conflict. The model will be predicting the miss rate types and predicitng the miss rate. With the miss rate percentage, we will calculate the hit rate and the performance of the phone.  

![WhatsApp Image 2024-03-26 at 13 27 51_0b1d35d9](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/806e0d91-0f89-442a-9f1b-9121471ba055)  

Reference: Department of Computer Science, University of Maryland.

With the heuristic parameters and the long run usage datasets, the MODEL will predict the cache memory usage and its performance. 

# Explanation - Algorithm

# Virtual Demonstration

# Intel AI Analytics Toolkits:
![288444454-c4da56ab-906a-4aa3-b3cd-47f93e3f7b59](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/fa9d030a-6876-4561-ba6b-331b03eea395)
![download](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/24f4e04e-4c06-47af-bab7-379433f579d7)
![image](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/58d818b3-641d-492c-9801-88cfe0062567)


# Model Training

# Experiments

# Intel Developer Cloud

# Output
An Android App called MemoryMate is created which will display the predictions done by the model under the Memory Management tab. This tab will show the performance graph of the android phone along with the X variables ie Cache blocks, associativity and the y varaible ie conflict(3rd miss) and the miss rate. 

![WhatsApp Image 2024-03-28 at 17 06 36_65498253](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/93e5c88b-f2e6-4198-a02f-5bd52ab9a2e7)

Under the Verdict tab, the final verdict of the android phone along with the indicators will be displayed.
# Tech Stacks used:


# Conclusion

Optimizing cache memory in Android phones is important for several reasons:

#Improved Performance: Cache memory stores frequently accessed data and app components. By optimizing cache usage, Android devices can retrieve this data quickly, leading to improved performance and faster response times for apps and system operations.

 #Reduced Data Usage: Efficient cache management can help reduce the amount of data that apps need to download from the internet repeatedly. This not only speeds up app loading times but also conserves mobile data, which is crucial for users on limited data plans.
 
#Storage Space Management: Cache data can accumulate over time and consume significant storage space on the device. By optimizing cache usage, you can prevent unnecessary clutter and free up storage for other important data and apps.

#Battery Life: Accessing data from cache memory is less resource-intensive than fetching it from the internet or storage. Therefore, efficient cache management can contribute to better battery life by reducing the overall workload on the device's CPU and network components.

#Enhanced User Experience: A smoother and more responsive user experience is directly influenced by how efficiently an Android device manages its resources, including cache memory. Optimizing cache usage contributes to a seamless and enjoyable user experience with minimal delays and interruptions.

Overall, optimizing cache memory in Android phones is essential for maximizing performance, reducing data usage, managing storage space effectively, improving battery life, and delivering a superior user experience.


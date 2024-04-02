# Intel-AI-Hackathon
Team Name: THE 404

Team Lead: Monish Kiran A  

Email: monishkiran304@gmail.com

# Problem Statement
Memory Optimisation in Android Phones using AI/ML.

# Description
The performance of an Android phone is determined by the architecture and the memory management, especially the cache memory utilization. Irrespective of the architecture, for any Android phone the average memory access time (AMAT) can be minimized, thereby enhancing the overall performance of the device. This hackathon idea aims to develop a predictive model to optimize cache memory block utilization, minimize the miss rate and improve Android phone performance.

# Explanation - Idea
The cache memory blocks are small blocks of memory that store data that needs to be frequently accessed. The cache doesn't always have a hit rate of 100%. There are many causes and thus different types of cache misses, compulsory misses, cold misses, and conflict miss. The idea will involve the development of a predictive model to anticipate cache miss rates and types. The model will analyze factors such as cache block size, associativity, and memory access patterns to make accurate predictions and the performance of the phone. With the heuristic parameters and the long-run usage datasets, the MODEL will predict the cache memory usage and its performance. An Android application named MemoryMate will be developed as the output of this project. MemoryMate will feature a dedicated “Memory Management” tab that displays performance predictions generated by the model. The “Memory Management” tab will include intuitive graphical representations, such as performance graphs and the user will be able to visualize the impact of different cache configurations on performance. Additionally, the app will provide insights into cache miss rates and types, empowering users to make informed decisions for memory optimization. 

Video Explanation:

https://drive.google.com/file/d/1ciQiYCfZhpjSGJblNwQnRpmXMVyEfY5z/view?usp=sharing


# Explanation - Algorithm
Random Forest Regressor is being used here. A random forest is a meta estimator that fits a number of decision tree regressors on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. Trees in the forest use the best split strategy, i.e. equivalent to passing splitter="best" to the underlying DecisionTreeRegressor. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.
With the heuristic parameters and the long run usage datasets, the MODEL will predict the cache memory usage and its performance.
 

# Dataset
https://drive.google.com/file/d/18ZHB-tUi5Ch3oLit8ylyAghGyNs-5_38/view?usp=sharing

Reference:![WhatsApp Image 2024-03-26 at 13 27 51_fc46f22d](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/02487f06-18bc-499b-8bad-654459020fee)


# Intel AI Analytics Toolkits:

![image](https://github.com/codeshark304/Intel-AI-Hackathon/assets/116503676/72cb9ea4-3f4d-47a3-9ccc-63b7ab31ffb1)


scikit-learn* , OneDAL, pandas, numpy, XGBoost


# Intel Developer Cloud

Processor used: 5th Generation Intel Xeon Scalable Processors

With and Without Intel OneAPI

# Output
"MemoryMate" an Android Mobile app is designed to analyse and optimize cache performance on a device. The app, built with Kotlin, will leverage machine learning to identify usage patterns and suggest cache configuration improvements for a better hit rate.

1)The application will offer the following functionalities:

•	Cache Performance Monitoring: Display key cache metrics like hit rate, miss rate, and capacity utilization.

•	Pattern Analysis: Utilize machine learning algorithms to analyze user access patterns and identify spatial and temporal locality trends.

•	Optimization Recommendations: Based on the analysis, suggest potential cache configuration adjustments like size or associativity to improve the hit rate.

•	Hardware Consideration: Factor in device hardware specifications like main memory size, storage capacity, and processor speed during optimization recommendations.

2)Development Platform: Kotlin (Android)

Machine Learning Model: The specific model selection will depend on chosen libraries and desired functionalities. Potential options include:

•	Markov Chain Models: Can effectively capture temporal locality by predicting future data access based on past sequences.

•	K-Nearest Neighbors (KNN): Useful for identifying similar access patterns and suggesting configurations that worked well in those scenarios.

•	Data Acquisition: The app can access cache performance metrics through system APIs provided by the Android platform.

3)The application will consider the following cache optimization principles:

Spatial Locality: Programs tend to access data that is physically close together in memory. The app can analyze access patterns to identify frequently accessed data clusters and ensure they reside in the same cache line, improving hit rates.

Temporal Locality: Programs are more likely to access data recently used. The app's machine learning model can predict future access patterns based on recent usage and prioritize storing that data in the cache.

4)The app will generate reports summarizing:

•	Current cache performance metrics (hit rate, miss rate, and capacity utilization).

•	Identified access patterns and their impact on cache efficiency.

•	Recommended cache configuration adjustments for optimal hit rate.

5)This application can benefit users by:

•	Improving device performance: A higher cache hit rate leads to faster data access and a smoother user experience.

•	Extending battery life: Reduced reliance on main memory access can improve battery efficiency.

•	Providing actionable insights: Users gain a deeper understanding of their app's data access patterns and can optimize cache settings accordingly.

# Conclusion

By focusing on memory optimization through cache memory block management, this hackathon idea aims to contribute to the ongoing efforts to improve Android device performance. The combination of predictive modeling and user-friendly interface design in the MemoryMate app will empower users to make informed decisions regarding memory management, ultimately resulting in a smoother and more efficient user experience.

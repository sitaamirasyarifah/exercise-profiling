Reflection
Name   : Sita Amira Syarifah
NPM    : 2206023023
Adpro-C

Reflection
Please answer the following questions:
1.What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
2.How does the profiling process help you in identifying and understanding the weak points in your application?
3.Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
4.What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
5.What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
6.How do you handle situations where the results from profiling with Inte	lliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
7.What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

Reflection Module 5
1. **Difference between Performance Testing with JMeter and Profiling with IntelliJ Profiler:**
   - Performance testing using JMeter aims to measure the overall performance of the application under various load conditions, such as identifying how the application behaves when given a specific number of users or requests. Meanwhile, Profiling with IntelliJ focuses more on analyzing the internal behavior of the application, including CPU usage, memory consumption, and thread activity. Because it focuses on analyzing the internal workings of the application, profiling can optimize specific areas of code for better performance.

2. **How Profiling Process Helps in Identifying Weak Points:**
   - Profiling allows me to see which methods or areas of code consume high system resources. Additionally, profiling provides insights into which areas of the application spend most of their time. With these insights, I can easily optimize by focusing only on the methods that need performance improvement.

3. **Effectiveness of IntelliJ Profiler in Identifying Bottlenecks:**
   - Yes, I feel sufficiently assisted by the Profiler in IntelliJ in analyzing and identifying bottlenecks in my application code. The well-visualized flame graph helps me see which methods consume the most resources.

4. **Main Challenges and Overcoming Them:**
   - This Module 5 tutorial is my first time conducting performance testing and profiling. Initially, I was confused about what to do and how to interpret the results. I also found the setup seeding process and optimizing by changing methods challenging. However, carefully reading the tutorial and discussing with friends helped me complete this performance testing and profiling.

5. **Main Benefits of Using IntelliJ Profiler:**
   - The advantage of using IntelliJ Profiler for profiling is that I can directly focus on the root cause of application performance issues because IntelliJ Profiler shows which parts of the application consume the most resources. So, I can focus directly on prioritized methods for optimization.

6. **Handling Inconsistent Results:**
   - To handle such situations, during profiling, I check the results repeatedly (at least 3 times), then I estimate the average. I do the same when conducting performance testing with JMeter. In essence, for the process, I perform performance improvement → profiling → performance testing, and after several iterations of these steps, I believe the results are consistent enough.

7. **Optimization Strategies and Ensuring Functionality:**
   - I try to implement several efficient techniques on various methods. For example, I prefer using StringBuilder over repeated string concatenation in the jointStudentNames method because I believe repeated string concatenation will consume more memory. Additionally, I try to learn the usage of @Query annotation to fetch HighestGPA data. After performance improvement, I perform testing again to ensure that the output remains the same as before the changes were made.

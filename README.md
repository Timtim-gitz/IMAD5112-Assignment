# IMAD5112-Assignment
My History App Report

Introduction:

The My History App is a unique android application developed with the aim of making history both educative and fun, particularly targeting young people interested in historical figures and their lifespans. That said, anyone else interested in history can use this fun app. This report provides a comprehensive overview of the app's features, technical details, target audience, and its potential impact.

Features

The My History App offers several key features designed to engage users and provide them with educational insights into historical figures and their lifespans.

Documentation of Historical Figures
The app features a curated list of 10 historical figures spanning various fields and eras. These figures include Pablo Escobar, Wolfgang Amadeus Mozart, Steve Jobs, Fidel Castro, Amy Winehouse, Stephen Hawking, Queen Elizabeth II, Mother Teresa, Neil Armstrong, and Karl Marx. For each historical figure, the app provides essential information such as their name, age at death, and a brief fact about them. This feature allows users to learn about prominent individuals from history and gain insight into their lives and what made them unique. For instance, users can delve into the groundbreaking theories of Karl Marx, explore the musical genius of Wolfgang Amadeus Mozart, or reflect on the  impact of Fidel Castro’s leadership.

Age Matching Functionality
 Users can enter an age into the app and click the "enter age" button, and the application will match that age with historical personalities who died between the ages of 20 and 100. For example, if a user enters the age 90, the app will display information about a historical figure who died in their 90s, including the precise age they died and a brief description of them. This feature adds an interactive component to the app, allowing users to research historical figures relevant to their generation. Age inputs outside the 20 to 100 range will result in a "null" response. 
User Interface

The app's user interface features a vintage aesthetic, providing a visually engaging experience reminiscent of historical documents and a pocket watch, reflecting that we travelling back in time. 
The "Enter Age" button on the main interface allows users to enter an age. the "Generate History" button activates the age matching feature. Thereafter, users can access details about the matched historical figure once the age matching process is completed. Furthermore, the app has a "Clear" button that lets users reset it and set the age again. Additionally, the user interface has a "show results" button that, when a valid age is entered, displays the historical figure's information.The "null" caution appears on the show results button if an incorrect age is entered. Below is an image of the user interface after the user inputs the age 88 into the “enter age” button.



Technical Details 

The My History App is developed using Kotlin, a modern programming language for Android app development. Kotlin’s syntax is concise and expressive, allowing developers to focus on implementation rather than dealing with brackets, null errors, and long compilation times. It is preferred by developers at prominent firms like Google, Amazon, and Uber (Maine,2024) .My History App is built using Android Studio, the official integrated development environment (IDE) for Android app development. The app utilises various Android development frameworks and libraries to implement its features, including user interface components, data handling, and age matching algorithms.

The age matching functionality is implemented using a custom algorithm that compares the user's input age with the ages at death of the historical figures stored in the app's database. The algorithm selects the historical figure whose age at death is closest to the user's input age within the specified age ranges, that is, 20 to 29, 30 to 39, 40 to 49, 50 to 59, 60 to 69, 70 to 79, 80 to 85, 86 to 89, 90 to 95 and 96 to 100. Once  a matching historical figure is found, the app retrieves and displays relevant information about that figure, including their name, age at death, and a brief fact about them.

Target Audience:

The primary target audience for the My History App is young people with an interest in history, particularly those who enjoy learning about historical figures and their contributions to society. The app is designed to appeal to users who seek both educational content and entertainment value, providing a unique and engaging way to explore history through the lens of age.

By targeting young people, the app aims to foster a deeper appreciation for history and inspire curiosity about the lives and accomplishments of historical figures. However, the app’s appeal extends to educators, historians, and enthusiasts seeking to supplement their knowledge with interactive digital resources. By targeting a diverse audience, the app aims to foster a deeper appreciation for history and inspire curiosity. Through its interactive features and informative content, the app seeks to make history more accessible and relatable to a new generation of learners.

Testing and Deployment:

In addition to its features and functionality, the My History App underwent testing and deployment processes to ensure reliability and compatibility across different devices and platforms. The app’s development lifecycle included the use of GitHub Actions, A continuous integration and delivery (CI/CD) platform that automates your build, test, and deployment workflow ($). 

To run the app on GitHub Actions, firstly I created  a repository on GitHub to host my Kotlin app.after ensuring that my project is ready with the necessary files and configurations, I added a GitHub Action workflow. In the GitHub repository, I create a new directory named `.github/workflows`. Inside this directory,  I added a  YAML file to define the  workflow. Thereafter, I committed the changes to my repository and pushed them to GitHub. 
The integration of GitHub Actions into the My History App’s development workflow played a crucial role in ensuring the app’s quality, reliability, and efficiency. As a result of these automated processes, the My History App was able to maintain a high level of quality and consistency throughout its development lifecycle, ultimately providing users with a level a seamless and enjoyable experience.

Conclusion

In conclusion, the My History App offers a compelling and immersive experience for users interested in history, providing a curated selection of historical figures and their lifespans in an engaging and interactive format. With its unique age matching functionality, intuitive user interface, and comprehensive database of historical figures, the app serves as a valuable educational resource and a source of inspiration for users of all ages.

By combining educational content with entertainment value, the My History App aims to make history more engaging and accessible to a wide audience, fostering a deeper understanding and appreciation of the individuals who have shaped the course of human history. As technology continues to evolve, apps like My History have the potential to revolutionise the way we learn about and interact with the past, paving the way for new discoveries and insights into our shared heritage

References 

Maine.C.2024). A Comprehensive Kotlin Learning Guide for All Levels. Retrieved from https://blog.jetbrains.com/education/2024/04/04/kotlin-learning-guide/
GitHub.(N.d). Understanding GitHub Actions.  Retrieved from https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#


youtube link

https://youtu.be/RKFYmEQFRLQ?si=nNlGknqncwcduZVT

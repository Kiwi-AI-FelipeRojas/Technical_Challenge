This repository contains the solution for the AI Vision & LLM Engineer - Technical Challenge. Each of the folders has the solution for each part of the challenge. The file "Report.PDF" is a brief report on how the solution was solved and the file
“Solution_demo.mp4” is a video that shows an example of both solutions. 

- Part 1: Computer Vision Task - Object Detection & Tracking 

For the first part of the challenge, a computer vision model was trained using the Fast Food Classification Dataset (https://www.kaggle.com/datasets/utkarshsaxenadn/fast-food-classification-dataset/data). The model was trained to detect and count, in real time, 3 different types of food: burgers, pizzas and fries. When running the code the camara of the computer will activate automatically. When a burger, pizza or fries appear in front of the camara, the model will identify it and enclosed it in a rectangle. At the same time, a graph will display showing the number of identified objects. At last, the code with generate a text file containing a JSON with the count of objects at different time stamps.

- Part 2 LLM Task - Structured Data Extraction & Processing

For the second part of the challenge, a code was developed using a LLM to extract key information of Word or PDF files. The code will analyze all files in an specific folder an extract: name of a restaurant, ID of the order, all ordered food items, actions to take, time and date of the order and its total price. At the end of the process, the extracted data is exported to a text file that contains a JSON with the extracted data of each of the analyzed files. 

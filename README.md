# Student-Details-Update

Team Members:
1. Rashmita Pandey (16030721009)
2. Chandan Thakur (16030721010)

This is the implementation of smart contract using Solidity. In this smart contract, Student details is stored in the blockchain using setStudentData Function. To link the Student to the corresponding Department we have implemented setDept function. In order to check if the Student details is linked to the Department or not, we have implemented checkdetails function.

Elements Description:
![image](https://user-images.githubusercontent.com/49206219/173084967-a736e086-4d4c-47b3-bdff-86928f68d61d.png)

1. setStudentData: This function is storing the following student details onto the blockchain.
    a. name
    b. department
    c. homeaddress
    d. batch
    e. phone
2. studentmapping: This public variable is taking student address as an input.
3. setDept: This function takes input as the department address as an input to which the students data gets mapped
4. checkdetails: This function takes students adress and the batch information of the student to check if the students data is mapped to the Department or not.

Code works in the following mentioned steps:
1. Enter the Student data.

![image](https://user-images.githubusercontent.com/49206219/173085548-af1d771d-1749-43f5-b407-7d6b96a64103.png)

2. Copy the student address and paste it in studentmapping.

![image](https://user-images.githubusercontent.com/49206219/173087129-03216e46-8df0-41ea-bd86-8bd0f023e369.png)
![image](https://user-images.githubusercontent.com/49206219/173087723-feeb177a-e56e-46d4-a47e-6e10c0798b3d.png)

3. Enter Department address (i.e. Account address) in setDept.

![image](https://user-images.githubusercontent.com/49206219/173090793-17234baf-c1c2-4faa-97ff-da2267196a9f.png)
![image](https://user-images.githubusercontent.com/49206219/173090913-02112d65-bf00-44be-897b-1452370b7a48.png)

4. Paste the Department adress in deptmapping.

![image](https://user-images.githubusercontent.com/49206219/173091390-693a5ba2-ba13-4889-b49e-c5c1ad5159a5.png)

(Till now we were linking the depatment address with student data address. Now to check if the student data is mapped to the Department, we have to perform step 5.)

5. In checkdetails Section enter Student address in the unique field and enter the batch of the student to check if the student data is mapped to the Department or not.

![image](https://user-images.githubusercontent.com/49206219/173092578-769ba71e-8c4d-4856-b2ea-05baaa664466.png)

6. Output:

![image](https://user-images.githubusercontent.com/49206219/173092868-f466087a-b261-4cd4-a8da-4038dbc6c1f4.png)







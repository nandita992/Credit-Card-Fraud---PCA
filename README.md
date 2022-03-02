**Business Problem**

For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

It has been estimated by Nilson Report that by 2020, banking frauds would account for $30 billion worldwide. With the rise in digital payment channels, the number of fraudulent transactions is also increasing in new and different ways.

In the banking industry, credit card fraud detection using machine learning is not only a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees as well as denials of legitimate transactions.

**Understanding and Defining Fraud**¶

Credit card fraud is any dishonest act or behaviour to obtain information without proper authorisation from the account holder for financial gain. Among different ways of committing frauds, skimming is the most common one, which is a way of duplicating information that is located on the magnetic strip of the card. Apart from this, the other ways are as follows:

Manipulation/alteration of genuine cards
Creation of counterfeit cards
Stealing/loss of credit cards
Fraudulent telemarketing


![Logistic Regression-3](https://user-images.githubusercontent.com/98303163/156309416-96365e34-d34a-462d-95ed-70c7ed8386ae.png)


Step 1: Importing the dataset and Sanity Checks
- List all the libraries used
- Make ROC functions for later use
- Import the data csv file onto the disk
- Check for null values

Step 2: Exploratory Data Analysis
- Class imbalance of Fraudalent vs Non-Fraudalent 
- Scatter plot of amount and time and their ditribution of classes

Step 3: Pre-processing the data
- Splitting the data between X and Y
- Splitting between train and test set
- Check for skewed data and apply Power Transofmer to make the distribution more Gaussian

Step 4: Model Building using cross validation

<img width="604" alt="Screenshot 2022-03-02 at 2 28 37 PM" src="https://user-images.githubusercontent.com/98303163/156329049-41502dd6-3307-427a-a44c-9df4e263a7b7.png">

<img width="600" alt="Screenshot 2022-03-02 at 2 29 30 PM" src="https://user-images.githubusercontent.com/98303163/156329186-bc59591a-569e-4843-a8f7-b096a203c87d.png">

<img width="600" alt="Screenshot 2022-03-02 at 2 30 31 PM" src="https://user-images.githubusercontent.com/98303163/156329406-bf1b7551-8cfc-42d4-bf94-716363afd475.png">

<img width="597" alt="Screenshot 2022-03-02 at 2 30 54 PM" src="https://user-images.githubusercontent.com/98303163/156329447-4f95c071-c14a-48dc-8c9a-b48853191653.png">

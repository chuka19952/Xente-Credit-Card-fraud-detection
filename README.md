# Xente-Credit-Card-fraud-detection
Built and proferred a solution for xente an e-commerce company against credit card fraud on its customers

# The objective of this competition is to create a machine learning model to detect fraudulent transactions.

Fraud detection is an important application of machine learning in the financial services sector. This solution will help Xente provide improved and safer service to its customers.

This competition is sponsored by Xente, Innovation Village, and insight2impact.

About Xente (www.xente.co)

Xente is an e-payments, e-commerce, and financial services company in Uganda offering various products and services that can be paid for using Mobile Money (Airtel Money, MTN Mobile Money), Bank Card (Visa Card, Master Card), Xente wallet and on credit (Pay Later). Some of the products consumers can buy include airtime, data bundles, pay water and electricity bills, TV subscription services, buy event tickets, movie tickets, bus tickets, and more.

# About Innovation Village (www.innovationvillage.co.ug):

The Innovation Village is Uganda’s launchpad for leading Innovators and entrepreneurs. We are building an entire ecosystem of entrepreneurs and innovators in what is growing to become a business solutions provider for our biggest challenges or opportunities. From helping entrepreneurs launch and grow high-impact ventures to attracting regional and global opportunities, our ecosystem approach converges multiple partners including public, private, academia, research and civil society as one force for good.

Our overall goal is to create a destination that grows companies that matter (Startups, SMEs and Purpose-Driven Enterprises) and centered around solving our biggest industry and community challenges. Collectively, we are a convergence of Network, Talent, Capital and Physical Assets leading Uganda and the region into the 4th Industrial revolution.

# About insight2impact (i2ifacility.org):

insight2impact (i2i) is a resource centre supporting the use of data for decision-making, with a focus on financial and economic inclusion. i2i is hosted by FinMark Trust and Cenfri and funded by the Gates Foundation in partnership with The Mastercard Foundation.

# About dataset
# Xente is an e-commerce and financial service app serving 10,000+ customers in Uganda.

This dataset includes a sample of approximately 140,000 transactions that occurred between 15 November 2018 and 15 March 2019.

One of the challenges of fraud detection problems is that the data is highly imbalanced. See these blogs for examples on how imbalanced data might be handled:

# The files for download here are:

    Xente_variable_definitions.csv: Definition of the features per transaction
    Training.csv: Transactions from 15 November 2018 to 13 February 2019, including whether or not each transaction is fraudulent
    Test.csv: Transactions from 13 February 2019 to 14 March 2019, not including whether or not each transaction is fraudulent

# error metric
The error metric for this competition is the F1 score, which ranges from 0 (total failure) to 1 (perfect score). Hence, the closer your score is to 1, the better your model.

F1 Score: A performance score that combines both precision and recall. It is a harmonic mean of these two variables. Formula is given as: 2*Precision*Recall/(Precision + Recall)

Precision: This is an indicator of the number of items correctly identified as positive out of total items identified as positive. Formula is given as: TP/(TP+FP)

Recall / Sensitivity / True Positive Rate (TPR): This is an indicator of the number of items correctly identified as positive out of total actual positives. Formula is given as: TP/(TP+FN)

Where:

    TP=True Positive

    FP=False Positive

    TN=True Negative

    FN=False Negative

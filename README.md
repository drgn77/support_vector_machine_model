🧠 Support Vector Machine (SVM) Classifier

This project demonstrates how to build, train, and evaluate a Support Vector Machine (SVM) model using the Social Network Ads dataset.
The model predicts whether a user will purchase a product based on their Age and Estimated Salary.

📦 Libraries Used

pandas, numpy – data handling

matplotlib – visualization

scikit-learn – model training, scaling, evaluation

joblib – saving the trained model

⚙️ Workflow

Load dataset from data/Social_Network_Ads.csv

Split data into training and test sets

Scale features using StandardScaler

Train an SVM with a linear kernel

Evaluate model with metrics (accuracy, precision, recall, F1-score) and confusion matrix

Save the trained model to models/support_vector_machine.pkl

🧩 Example Prediction
classifier.predict(sc.transform([[30, 87000]]))

📊 Output

Model evaluation metrics

Confusion matrix visualizationg
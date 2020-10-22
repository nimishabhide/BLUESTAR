# Diabetes-classification
Uses the most famous random forest algorithm.
Use this code to find the accuracy of the model and please modify as per your code
from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)

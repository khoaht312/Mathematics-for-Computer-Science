
# Logistic Regression

# Naive Bayes

1. Multinomial Naive Bayes
- Được sử dụng trong phân loại văn bản
- Đặc trưng bởi số lần xuất hiện của từ trong văn bản
P(xi|y) = Ni / Nc (từ / tổng từ)

Laplace Smoothing: P(xi|y) = Ni + alpha / Nc + d{alpha}

2. Bernouli Naive Bayes

Mô hình này được áp dụng cho các loại dữ liệu mà mỗi thành phần là một giá trị binary - bẳng 0 hoặc 1. Ví dụ: cũng với loại văn bản nhưng thay vì đếm tổng số lần xuất hiện của 1 từ trong văn bản, ta chỉ cần quan tâm từ đó có xuất hiện hay không.

3. Gaussian Naive Bayes

Mô hình này được sử dụng chủ yếu trong loại dữ liệu mà các thành phần là các biến liên tục.

# SVM

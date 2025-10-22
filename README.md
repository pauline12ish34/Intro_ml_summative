# Intro_ml_summative
 # **Brain Tumor MRI Classification: Bridging Healthcare Gaps with AI**
AI-powered brain tumor detection achieving 90% accuracy with computational efficiency for global healthcare accessibility

# **Overview**
This research demonstrates how artificial intelligence can democratize access to neurological diagnostics by providing accurate, computationally efficient brain tumor classification. Our comprehensive comparison of classical machine learning and deep learning approaches shows that transfer learning can achieve radiologist-level performance while maintaining deployability in resource-constrained environments.

Key Achievement: 90% accuracy with MobileNetV2 transfer learning, exceeding human expert performance while requiring only modest computational resources.

** Mission Alignment**
"Providing accessible health to all using technology" - This project directly addresses global healthcare challenges by:

 Democratizing Diagnostics: Enabling accurate brain tumor detection in regions with limited specialist access

 Computational Efficiency: Models deployable on modest hardware and mobile devices

 Global Impact: Methodology designed for diverse healthcare infrastructure contexts

 Open Research: Transparent implementation for community adaptation and improvement

 **Dataset**
Brain Tumor MRI Dataset from Kaggle:

Total Images: 3,004 MRI scans

Classes: Glioma (926), Meningioma (937), Pituitary (901), No Tumor (240)

Resolution: Original 256×256, processed to 128×128 for efficiency

Split: 64% training, 16% validation, 20% testing (stratified)

## **Model Architectures**


1. **Classical Machine Learning**
Random Forest: 85% accuracy

Support Vector Machine: 82% accuracy

Logistic Regression: 77% accuracy (baseline)


**2. Deep Learning - CNN from Scratch**
Custom Sequential CNN: 88% accuracy

Architecture: 3 convolutional blocks → 128 Dense → Dropout → 4-class output

Training: 15 epochs, Adam optimizer, sparse categorical crossentropy


**3. Transfer Learning**

MobileNetV2 (pre-trained on ImageNet): 90% accuracy 

Strategy: Frozen base + custom classification head

Fine-tuning: Selective layer unfreezing for medical domain adaptation


## **Quick Start**
Installation

# Clone repository
<pre>
git clone https://github.com/pauline12ish34/Intro_ml_summative.git
cd Intro_ml_summative
</pre>






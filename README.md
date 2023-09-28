# Diabetic_Retinopathy_CodeClause


1. **Running the Code:**
   - Download the dataset from [here](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid). If the link shows "403 Forbidden," copy and paste it into your browser.
   - Create "test" and "train" folders.
   - Upload training images to the "train" folder and testing images to the "test" folder.
   - Rename the training and testing CSV files as "Training_labels.csv" and "Testing_labels.csv."
   - Run the code on your system.

2. **Understanding Diabetic Retinopathy:**
   - Diabetic retinopathy results from prolonged high blood sugar associated with diabetes, causing damage to the small blood vessels in the retina.
   - Regular eye exams are crucial, as untreated diabetic retinopathy can lead to vision loss and blindness.
   - Early treatment and diabetes management can prevent or delay vision problems.

3. **Project Overview:**
   - The project detects and classifies diabetic retinopathy stages on a scale of 0 to 4.
   - Severity classes: '0' - Healthy Eye, '1' to '4' - Increasing severity levels.
   - Terms: NPDR (Nonproliferative diabetic retinopathy) and PDR (Proliferative diabetic retinopathy).

4. **Pre-processing of Images:**
   - Image size reduction.
   - Data Augmentation increased the dataset from 413 to 2857 images.

5. **Classification:**
   - Inception Resnet V2 is used as the training model.
   - 'Adam' is employed as the optimizer.

6. **Future Scope:**
   - Implementing feature detection techniques could enhance accuracy.
   - Blood Vessel and Exudate Detection may further improve accuracy.
   - With an expanded dataset, the model can be trained more accurately in the future.

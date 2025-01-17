

###  **Project Structure: Mid-Term Part 2 – Machine Learning (KRLS with Gaussian Kernel)**

1. **Objective**

   * Apply your knowledge of supervised learning.
   * Use **Kernel Regularized Least Squares (KRLS)** with a **Gaussian kernel** for model training.

2. **Provided Data**

   * You will receive a **training dataset** only.
   * You must **analyze the output** to determine the **type of problem** (e.g., regression or classification).
   * ⚠️ **The test set will not be provided** in advance.

3. **Workflow Structure**

   * Perform **Q-Fold Cross Validation**:

     * Use it to choose the optimal values for:

       * Regularization parameter **λ (lambda)**
       * **Gaussian kernel** parameter
   * Train the model using the **best hyperparameters** selected from cross-validation.

4. **Deliverables (Notebook Requirements)**

   * A clean, well-commented **Jupyter notebook** showing:

     * The **training procedure**
     * Reuse of your existing code from weekly hands-on exercises
   * ➕ **Important Final Cell**:

     * Include code to:

       * Load the test dataset (you’ll get it during evaluation)
       * Evaluate the model
     * ⚠️ Missing or incorrect implementation in this part will cost you points during grading.



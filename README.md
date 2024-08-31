# React Formik Task

In this application, users can adjust the per-unit quantity of items, and the application will automatically update both the total quantity and the total amount based on these adjustments. This functionality is managed using React Redux Toolkit to ensure efficient state management and a scalable approach.

## Features

-State: Manages the quantity, pricePerUnit, totalQuantity, and totalAmount.
-Reducers: Define actions to increase or decrease the per-unit quantity, which automatically updates the total quantity and amount.
-Selectors: Allow components to access the current state values, such as the total quantity and amount.

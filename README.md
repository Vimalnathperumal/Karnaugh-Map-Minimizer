# Karnaugh_Map_Minimizer
This project creates an engaging application that simplifies Boolean  expressions using Karnaugh maps, helping learners and professionals  optimize logical functions efficiently.

## Tech Stacks :
- Java: Core language for implementing K-map algorithms and GUI.

## How to Use : 
### 1.  Input Handling
- The user enters a Boolean expression or a truth table.
- The program parses the input, validates it, and determines the number of variables.
  ![input](https://github.com/user-attachments/assets/3dcd5506-f825-4bc4-a3f1-bb07c27061f2)


### 2. K-map Generation
 - A K-map grid is created dynamically based on the number of variables (2x2, 2x4, or 4x4).
 - The user can see how minterms (or maxterms) map onto the grid.
 - The program identifies the largest possible groups and highlights them on the K-map.
 - The minimized expression is derived based on these groupings.
   ![kmap](https://github.com/user-attachments/assets/48e614bb-49ca-4867-86af-557184044b2d)


### 3.  Output and Verification
 - The minimized Boolean expression is displayed in SOP or POS form.
 - The tool offers an option to verify the correctness by comparing the minimized expression with the original input.
   ![output](https://github.com/user-attachments/assets/c9d02fbb-6a11-4e32-b9e2-538461c70cb8)


## Points To Remember : 
> [!NOTE]
> Enter valid Boolean expressions or truth table values without syntax errors. The program may not function as expected if invalid input is provided.

> [!TIP]
>For best performance, simplify the input before entering it into the tool. For example, reduce unnecessary variables or terms if they are already evident.

> [!IMPORTANT]
>  Ensure Java is installed and configured correctly. Verify that the Java runtime environment (JRE) is up to date to avoid compatibility issues.

> [!WARNING]
>When using manual grouping (if allowed), ensure no overlaps or missed groupings. Incorrect groupings can lead to inaccurate simplifications.

> [!CAUTION]
> If your project supports exporting or saving, save the K-map and minimized expressions periodically. This avoids loss of progress due to unexpected software crashes or errors.

# UNITY3D Modular AI Framework

HOW TO USE THIS SYSTEM:

To use this system, do the following:

Step 1: Import the files in the "code" folder into Unity3D

Step 2: Drag the EnemyAI script onto a GameObject

Step 3: To add a new condition, create a new .cs file to match the template of ExampleCondition.cs

Step 4: Drag the new condition script onto the same GameObject as the EnemyAI script, and then add it into the conditions[] array

Step 6: To add a new action, create a new .cs file to match the template of ExampleAction.cs

Step 7: Drag the new action script onto the same GameObject as the EnemyAI script. Then, drag it into the associatedAction field of the
        condition that you want to have trigger this action. If you want this action to have higher priority, increase the actionPriority
        float value. Only the action with the highest actionPriority will be executed.
 

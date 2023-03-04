# Patient Admission Scheduling Optimization
## Introduction:  
For the purpose of this project, we are going to implement a MIP optimizer to model practical
bed planning scenarios and solve the patient admission scheduling problem from the
hospital’s perspective. Our goal is to assign each patient an appropriate room as soon as
possible while reducing the extra cost spent on room transferring. We will achieve this by
giving a penalty value for each case of miss-assignment of room, and for every time we fail
to accept a patient. Besides, we will also take the extra cost spent on room transfer into
account. By minimizing the sum of the overall penalty and extra cost, we will find the
optimal solution for managing our patient rooms. Using available data as the input, the
MIP model will record situations such as the availability of rooms, priorities, and patients’
requirements for specific medical equipment. These will all become parts of the constraints
of the problem. We will try to make this model as applicable as it could be to real-world
patient scheduling problems by incorporating more constraints.

## Data Source:
https://people.cs.kuleuven.be/~tony.wauters/wim.vancroonenburg/pas/ 
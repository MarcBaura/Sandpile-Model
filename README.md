# Sandpile-Model
# WHAT IS IT?
This model is our groups attempt to code the sandpile model using the netlogo application. Our sandpile model starts with each patch having random values ranging from 1 to 3. The user is then allowed to choose whether to drop a sandgrain either on a random patch or on the center. As a result, that patch will have it's value incremented by 1. If a patch's value becomes 4, that patch will relax which will turn its value to 0 and it will redistribute 1 sandgrain to its (Von Neumann) neighbors. The relaxation and distribution will continue for each tick until there are no patches with values greater than 3.

# HOW IT WORKS
Patches that have a value of 4 will relax (turn its value to 0) then it will redistribute 1 sandgrain to its (Von Neumann) neighbors. Simulating how sands create avalanches when a certain area of it has more sand grain than it can accommodate.

# HOW TO USE IT
Click the setup button to set up the sandpile with random values.

Click the go button to start the sandpile model.

Choose an option from the DropZone whether to drop the sand grain in a Random or Center patch.

# THINGS TO NOTICE
When the patches started to have continous chain of reaching the threshold, those patches that were relaxed within the tick will not be affected by the spreading of sand of those reaching the threshold.

# THINGS TO TRY
(suggested things for the user to try to do (move sliders, switches, etc.) with the model)

# EXTENDING THE MODEL
(suggested things to add or change in the Code tab to make the model more complicated, detailed, accurate, etc.)

# NETLOGO FEATURES
(interesting or unusual features of NetLogo that the model uses, particularly in the Code tab; or where workarounds were needed for missing features)

# RELATED MODELS
(models in the NetLogo Models Library and elsewhere which are of related interest)

# CREDITS AND REFERENCES
This model is our groups attempt to code the sandpile model using the netlogo application.

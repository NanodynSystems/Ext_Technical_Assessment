# INTRODUCTION
This repository contains the data and instructions to complete the technical assessment test for employment at Nanodyn. This readme describes the necessary context, problem statement and instructions. Upon completion of this technical assessment, please send your output to dirk@nanodyn.co.za.

# CONTEXT
The sugar production process is fairly well established. Although different factory configurations do exist, the foundation remains fairly consistent. At Nanodyn, one of our focus areas is the optimization of this sugar production process.

There is a fair amount of chemistry and physics involved, but a diagrammatic illustration of this can be found within this repository.

1 - At the first stage, sugarcane is delivered to the plant and loaded onto a belt. <br>
2 - A cane shredder then shreds the cane and ensures that the product is prepared for extraction. The finer the shredder is able to shred the cane, the better the extraction of sugar.<br>
3 - The cane enters the diffuser together with imbibition water. In this phase, the diffuser acts as a very big percolator where we effectively dissolve the sugar into the water to be able to separate the cane fibres from the sucrose.<br>
4 - The cane is then dosed with lime to ensure that the fluid is of optimum acidity. If the pH is too high, it affects the colour of the fluid and therefore the quality of the produced sugar. If the pH is too low, the sugar within the water inverts (decomposes and is destroyed). As such, this lime dosing step is critical.<br>
5 - The resultant juice is pushed into a tank that acts as buffer to ensure consistent and sufficient supply downstream in the process.<br>
6 - A set of evaporators then attempt to remove the fluid from the juice, thereby affecting the consistency of the liquid. This consistency is measured as "brix" and is defined as the percentage of solids within the fluid. This is done at controlled temperatures and pressures to in turn control the evaporation.<br>
7 - Additional downstream components then converts this syrup into sugar as we know it and consequently it is sold for a profit. This exercise does not focus on these downstream components and they can therefore be considered a black box.<br>

Take Note: Some steps are not mentioned for the sake of simplicity.

# PROBLEM STATEMENT
As with any business, the objective is to maximize profit. At different stages of this production process, sensors and data collection mechanisms allows us to monitor and effectively manage the process. Interventions can be introduced either by automating some of the components in the process; for example, changing valves to increase or decrase flow, changing temperatures at different stages, etc. Alternatively, interventions can be as simple as mere suggestions to be executed by the factory staff. The problem statement here is therefore to investigate the data provided, build necessary models where you see fit and provide suggestions on how profit can be increased.

# INSTRUCTIONS
The data can be found in the `data` folder in parquet format. The data is given as time series with timestamps and values for each of the `tagname` variables. These `tagname` variables are also illustrated in the process diagram to contextualize where they are measured and what they mean.

Use your tool of preference to:
1 - Read this data and apply any data preparation techniques you might deem necessary<br>
2 - Explore and visualize the data - please comment on any findings.<br>
3 - Build model(s) where you deem necessary and detail your reasoning.<br>
4 - Produce recommendations on improvements that could increase profit.<br>

Take note:
* You are welcome to use any coding language or tools you wish. Python and R are good candidates. Do take into consideration, at Nanodyn we do have a preference for Python.
* Please send any code that you may have written. 
* Your final conclusions can be sent in any format. Jupyter notebook is a good candidate, but you are also welcome to simply leave comments in your code or to provide a separate document containing your findings.

# TIPS
This problem statement is open ended by design. Therefore, some tips:
* Do not dive too deep. This problem can take anything from 1 day to 1 year. We do not expect you to solve all problems, we merely wish to see your approach to problem solving in general.
* Please describe your train of thought within the output material. We do not expect you to be an industry expert so this helps us contextualize your findings.
* The profit here is of course pertinent to the solution - building a model to understand this data seems like a sensible idea.
* Make sure that any code you send is easy to execute on our side, since that allows us to evaluate the code more effectively.
* Please feel free to contact dirk@nanodyn.co.za if you have any questions (technical or otherwise). This test is not only meant to evaluate your technical competency, but also to simulate the Nanodyn working environment where we throw you in the deep end and provide support where and when you need it.


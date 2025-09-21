Please open a new terminal OR run the following in the existing one:

    export PATH="$PATH":"$HOME/.maestro/bin"

Then run the following command:

    maestro



>>> Running all Test cases with split within the connected devices

     maestro test --shard-split 3 Android_Test_cases_RC

>>> Running all test cases with all connected devices 

     maestro test --shard-all 3 Android_Test_cases_RC 


>>>> Reading the data from the JS file 

- runScript:
    file: '../Scripts/credentials.js'
    - inputText: ${output.credentials.retailMobile}

>>>> 

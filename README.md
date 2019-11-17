#  Hello, this is an EcmaScript Linting tool, porpularly known as ESlint, used to spot out errors in your javascript code. 
  A lot of people complained that they have been finding it dificult to set it up with visual studio code editor so i felt i should share it.
 This linting project is coupled with prettier, a formatting tool for javascript. All is just to ensure script integrity 
and cleaner codes.

Usage:
1. Clone it into your machine or download it from here.
2. Cd into eslint
3. Open vscode by typing "code ." without double quotes
4. Create two files in the eslint directory by typing "touch code.js" and "touch .eslintrc" without double quotes.
5. To install everything needed by config.js i mean the dependencies, run the code below:

       "npx install-peerdeps --dev eslint-config-wesbos" without double quotes.
       
6. Copy the code below and put it in .eslint file

        {
          "extends":["wesbos"]
        }

7. For a test, just write javascript code anyhow inside test.js.... 
8. Inside code.js(note that you can use any name of your choice with .js extension)
9. Lastly, in Vscode Editor, Go to Files -> Preference -> settings -> Click Extension dropdown and select ESlint and check the box
9. Lastly, run the code below to see eslint in action
           npm run lint:fix
           
 RESULT 
 The code is formatted and error of commision or omission is spit out in the cmd
  Thank you



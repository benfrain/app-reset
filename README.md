# app-reset.css
A minimal CSS reset specifically for web applications

## Why use app-reset.css?
Every time I make something 'appy' I have to switch off or reset a bunch of user agent styles so that I can use the correct element for the job at hand but style it inline with the project I'm building.

App-reset is intended specifically for web applications.

## Accessibility Notes
These resets target HTML elements that typically receive styling defaults by User Agents that I always need to 'undo'.

Be aware that some of these resets have a negative impact on the default usability and accessibility of a web page. Therefore, ensure you add an equivalent accessible style back that matches your project aesthetic.

## You'll want to run this through Autoprefixer You'll typically need to run this through (https://github.com/postcss/autoprefixer) for production. Only essential prefixes are added here (e.g. proprietary property value/pairs) and you'll need to set prefixing relative to your desired browser support matrix.

###
Suggestions? Comment or open an issue or find me at https://twitter.com/benfrain or https://benfrain.com

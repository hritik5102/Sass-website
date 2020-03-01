SASS -> Synatically awesome stylesheet
CSS PreProcessor / Extension
Use the feature that do not exist in CSS
SASS file are compiled to regular CSS

feature :
1) provide a variable 
2) nesting property
3) modules 
4) mixing and function 
5) inheritance 
6) operator 
7) Conditional

Get free SVG from : https://undraw.co/search
Pre-requisite

1) npm install -g scss
Two ways to do settings:
    1) sass --watch scss/style.css css/style.css
    
    2) install live sass from vs-code
       add configuration in settings.json   
        "liveSassCompile.settings.formats":[
        // This is Default.
        {
            "format": "expanded",
            // "extensionName": ".css",
            "savePath": "/css"
        }
        ],
        "liveSassCompile.settings.generateMap":false,
    
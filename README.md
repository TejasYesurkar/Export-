# Export to Excel in Angular using ExcelJS
    1)Create An Angualr Cli Project
    2)Install ExcelJS Library
        npm install --save exceljs@1.12.0
    3)Update tsconfig.js
         "compilerOptions": {
            ...
            "paths": {
              "exceljs": [
                "node_modules/exceljs/dist/exceljs.min"
              ]
            }
          }

  4) Install file saver
      npm install --save file-saver
     
  5)Ready To Use

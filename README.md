# postman_newman_sample
Postman+Newman+Report

**Step 1 Node.js install**

**Step 2 npm Newman install**

**Step 3 Command line Run**
```
> newman run collection.json -e environment.json
```

**Step 4 Test Run and Report file create**
```
> newman run collection.json -e environment.json --reporters html,cli --reporter-html-template templates/htmlreqres.hbs --reporter-html-export report.html
```

**Step 4 Jenkins job add(OS:Windows)**
Build(Excute Windows batch command)
```
> newman run ./collection.json -e ./environment.json --reporters html,cli --reporter-html-template templates/htmlreqres.hbs --reporter-html-export report.html
```


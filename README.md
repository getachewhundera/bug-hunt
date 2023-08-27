# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install //done 
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.

### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._  //DONE

### Bug 1



1. added server to app.use(express.static('server/public')); line 19 in server.js 
2. const quoteRouter = require('./routes/quote.router.js');  //added .js to the quote.router line 8 in server.js
3. added module.exports = router; to quoter.router.js line 37
4. addded an s to getQuotes in axios.post  line 46 
5. //removed the s from quotesList to make it quoteList in router.post line 21 
6. switched axios and client.js file around in index.html so axios is loaded first axios is now on line 28
7. removed the quotes route names in quote.router.js line 10 and 17 
8. changed the single quotes to backticks on line 56 of client.js since we are using template literals. 
9. //added an s to deletequote in getQuotes funtion the button created is named deleteQuotes. line 55
10. -changed port number from 5007 to 5001 in line 7 as it states to change it. 


// switched the <input type="submit" />  to <!-- <button type="submit"> Submit </button> --> line 20
                
//aded <!DOCTYPE html> boiler plate 
//href and rel switched for google font line 6 
//added *.log in .gitignore line 1 
//added: to clear input fields 
    document.querySelector('#quoteInput').value= ('');
    document.querySelector('#authorInput').value = ('');


...

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html

# BackstopJS Practice

This project was build to serve as a guide using the backstopJS tool which is used to perform visual tests and detect if there were changes at the level of the front-end objects, it has four scenarios which performs the validation of: 
- A single object on the page
- Complete capture of the page by removing an object from the page.
- Clicking on a link before the screen capture
- Login by entering username - password and clicking on the login button and then taking the screenshots.


## Installation
```sh
git clone https://github.com/camhost01/BackstopJS_Practice.git
```
Extract all files from "BackstopJS_Practice" to your local folder

### backstop_data > bitmaps_reference
Inside this folder you will find the images against which you will contrast the execution of the test cases.

<img width="344" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/0628cc15-de69-446d-8514-ed92256cc5a8">

### backstop.json
Json with scenarios[] section who has the four test scenarios

<img width="1238" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/3855a3b2-e341-428e-b4c4-0db85e0eaeb3">

### package.json
Scripts to run through npm run
<img width="1167" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/b90a3cb6-7214-49e3-9e7b-267dad8b9174">

### clean
Delete folder bitmap_test or bitmap_reference
```sh
npm run clean:bitmaps_test
```
```sh
npm run clean:bitmaps_reference
```

### scenarios 
Execute all scenarios 
```sh
npm run scenarios
```

### approve_scenarios
Approve all image reference for the four scenarios
```sh
npm run approve_scenarios
```

## If you want to run only one test scenario and not all of them
To run only one test scenario and not all of them just add
```sh
npm run logo_test
```

## Execution
```sh
npm run scenarios
```
After execution, the test report is displayed in your browser, showing the results of the comparison at the top of the page

<img width="1751" alt="image" src="https://github.com/camhost01/BackstopJS_Practice/assets/39304271/9793fdbf-f315-4068-a79e-47250c26e51c">

## Note
The reference was taken in that way to generate those test results.








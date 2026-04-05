This is a Playwright framework project using POM design pattern and Data Driven Testing.
The code is with Typescript, the reports is with Allure report.

//

- To run a specific test file and show console logs written in the code:
npx playwright test EndToEndTest.spec.ts --reporter=line  

- generate allure reports and open it in the browser:
allure generate allure-results --clean -o allure-report 
allure open allure-report

- Parallel Testing, run 4 tests in 4 browsers at the same time:
npx playwright test LoginDataDriven.spec.ts --workers 4 


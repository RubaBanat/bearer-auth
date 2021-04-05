# bearer-auth


[Dev](https://github.com/RubaBanat/bearer-auth/tree/dev)

MONGODB_URI=mongodb+srv://rubabanat:0000@cluster0.ligjz.mongodb.net/myFirstDatabase?retryWrites=true&w=majority

---

## Feature requirement



- Fix all bugs in the starter code 
- Check all tests if all work well or not
- Add support for the creation and usage of time sensitive (valid for 15 minutes) JWTs 
- Add support for the creation and usage of ‘single-use’ JWTs
   - With every authenticated access, re-send a new JWT token as a cookie or header
   - Disable those that you’ve already authenticated


---

## UML 

![uml](imgs/uml1.jpg)

--- 

## Tests that assert your features:

- [Github-Acton](https://github.com/RubaBanat/bearer-auth/actions)


- Coverage 

![coverage](imgs/cov.png)


---


- [Pull-Request](https://github.com/RubaBanat/bearer-auth/pull/1)
- [Heroku-deployment](https://bearer-auth-ruba.herokuapp.com/)

---

## workflow

- `First` : 

- Deploy to Dev
- Complete an ACP on your dev branch.
- Go immediately to the repository on GitHub and open the actions tab
- You should see your tests running
- If they were passing on your local machine, they’ll also pass here
- Once your tests have passed, go to Heroku.com and look at your dev app’s Activity tab, it should show you an active deployment
When it completes, go to the Heroku app URL and open your server in the browser, you should see the same results as you saw locally.


- `Second`:


- Go to your repository on GitHub
- Open a pull request from dev to main
- If your tests are passing, you will be able to merge this branch
- Once you merge, the tests will run again using GitHub actions
- Once the tests pass, Heroku will deploy your “main” branch to your “production” app!
- When that process completes, open your app in the browser to prove it.


---

# THE END


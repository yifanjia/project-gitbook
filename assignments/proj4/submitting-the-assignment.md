# Submitting the Assignment

### Files

You may **not** modify the signature of any methods or classes that we provide to you, but you're free to add helper methods.

You should make sure that all code you modify belongs to files with `TODO(proj4)` comments in them \(e.g. don't add helper methods to DataBox\). A full list of files that you may modify follows:

* `src/main/java/edu/berkeley/cs186/database/concurrency/LockType.java`
* `src/main/java/edu/berkeley/cs186/database/concurrency/LockManager.java`
* `src/main/java/edu/berkeley/cs186/database/concurrency/LockContext.java (Part 2 only)`
* `src/main/java/edu/berkeley/cs186/database/concurrency/LockUtil.java (Part 2 only)`
* `src/main/java/edu/berkeley/cs186/database/table/Table.java (Part 2 only)`
* `src/main/java/edu/berkeley/cs186/database/table/PageDirectory.java (Part 2 only)`
* `src/main/java/edu/berkeley/cs186/database/memory/Page.java (Part 2 only)`
* `src/main/java/edu/berkeley/cs186/database/Database.java (Part 2 only)`

Make sure that your code does _not_ use any static \(non-final\) variables - this may cause odd behavior when running with maven vs. in your IDE \(tests run through the IDE often run with a new instance of Java for each test, so the static variables get reset, but multiple tests per Java instance may be run when using maven, where static variables _do not_ get reset\).

### Gradescope

Once all of your files are prepared in your repo you can submit to Gradescope through GitHub the same way you did for [Project 0](../proj0/submitting.md#pushing-changes-to-github-classroom). 

### Partners

If you haven't yet already be sure to fill out [this form](https://forms.gle/REQPugJuLDEK8hfr7) so we know who you're working with. When submitting to Gradescope sure remember add your partner to the submission so they can get credit. Slip days will be deducted individually. For example: You submit on time, but your partner submits a day late. Your partner will have to use a slip day or will receive a late penalty on the project \(but you will not\).

### Grading

* Part 1 is worth 40% of your Project 4 grade. 60% of that will come from public tests and 40% will come from hidden tests. We will only be running public tests on your Part 1 submission.
* Part 2 is worth 60% of your Project 4 grade. 60% of that will come from public tests and 40% will come from hidden tests. We will only be running public tests on your Part 2 submission.

Your Part 2 submission will be used to run all hidden tests \(and public Part 2 tests\). If you do not have a submission for Part 2, you will receive a 0% on all hidden tests for Part 1 and 2. You may go back and make changes to Part 1 even after that part deadline has passed before submitting to Part 2.

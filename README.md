# Merging Side Files Cases


## Two Separate Commits Both Add New Tests |&cross;|

In the case that two separate commits both add unique tests the merge conflict will look something like the following:

![two-tests-added](images/two-tests-added.png)

Following the suggested merge:

![two-tests-added-fixed](images/two-tests-added-fix.png)

Does not work...

It will only add the top test.

To actually get it to work requires adding proper brackets such as this:

![brackets](images/brackets.png)






# Repro Steps

1. Clone this repo.
2. Checkout `test` branch.
3. Modify `Class1` and attempt stash via GitStash. Error displayed is `perhaps you have untracked files, and didn't select Untracked.`
  
# Notes

1. At first, I only had a `master` branch. The above steps worked fine.
2. As soon as a I added the `test` branch and tried stashing changes on it, the error occured.

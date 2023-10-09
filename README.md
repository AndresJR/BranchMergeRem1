# BranchMergeRem1

## Op1 - Merge and fastforward
When we merge the branch feat1MergeFF to main, but there were no commits on main after the branch feat1MergeFF was created, then we can do FastForward, i.e., main branch "moves" to feat1MergeFF. In this situation both branches reference (point) to the same commit.

## Op2 - Merge without fastforward
When we merge the branch feat2MergeNoFF to main and we don't allow FastForwad, a new commit is created in main including all the changes of feat2MergeNoFF. In this situation, main points to the new merge commit, but feat2MergeNoFF keeps pointing to the last commit of its branch.

## Op3 - Rebase instead of merge
When we rebase the branch feat3Rebase to main, one new commit is created in main for each commit in feat3Rebase.

## Op4 - Merge with Squash
When we merge the branch feat4MergeSQ to main and we opt for squashing, a new commit is created in main and the title (1st line) of each commit comment of feat4MergeSQ is included in such a new commit.


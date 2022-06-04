# OmegaBankServer
Delta Inductions Task Submission for SysAd Domain


Although I tried, I couldn't implement aliasing for the updateBranch, allotInterest and makeTransaction scripts.
For updateBranch script, I had to run the command as a BranchManager but I couldn't sudo su into that user via aliases. However, the functionality is there and, ./updateBranch will properly run if we just sudo into the BranchManager account via the shell.
As for allotInterest script, I have created a createCronJob script that will run a cron task everyday at midnight, and would allot interestss to users accordingly. The createCron script too, is to be run with sudo.
For makeTransaction, similar to updateBranch , I had to sudo into anoter user, which I couldn't do with aliasing. However, each user has the functionality and once sudo'ed into the UserAcc, one can access the makeTransacion script.

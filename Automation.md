The whole on boarding process needs to be automated, this document contains the steps for the same.

## journey.hitalent.org

User will be greeted with [something like/similar](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) where the user will use google oauth to signup using gmail something [similar to](https://accounts.google.com/o/oauth2/v2/auth/identifier?client_id=802926523257.apps.googleusercontent.com&redirect_uri=https%3A%2F%2Fwww.linkedin.com%2Fgenie%2Ffinishauth&scope=profile%20email&response_type=code&state=0a6c3b70-4ba1-4dbb-816e-9bb0b416ff9b&flowName=GeneralOAuthFlow).

Once a user logs in or sign up(Gmail), they will land on onboard.hitalent.org/username (username is same as gmail by default else editable by talent, prferrably github profile name), where they will be able to see their progress regarding https://github.com/krantikaridev/helloworld some of the progress is automated some is proctored or self driven.

## Steps
1) Google sign up, if u are on this page it's already done, otherwise you would be redirected to sign up step
2) Slack Invite sent
3) Slack Invite Accepted
4) Github profile -> here the talent has to provide their github profile, once they do that this step is done
5) Helloworld repository(https://github.com/krantikaridev/helloworld) invite sent
6) https://github.com/krantikaridev/helloworld invite accepted
7) https://github.com/krantikaridev/helloworld branch created based on userprofile name
8) First hello world written in language of their choice, we can use git action for parsing the comment or we can ask talent to tag their commit when they are done with a step to automate this, intially we can allow talent to mark it done on their own
9) Now the following rest step are similar to 8 TODO
10) Admin (madan.hitalent.org) will land on onboard.hitalent.org but see cumulative board i.e. progress of each individual who have onboarded hitalent.org, there will be filter on this page so as to make it more useful to see everything in a glance, it will also be public i.e. visible to everyone, from here one can also navigate to individual git profile for https://github.com/krantikaridev/helloworld, hence able to see progress, though only editable permission are with user, the user has various role which allow them to perform different action

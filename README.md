### Hi there 👋, I'm Chloe O 👩‍💻

I'm a freelance front-end web-developer wanting to pivot towards working in a collaborative team-based enviornment contribute to the future of larger technological projects. 

- 👯 I’m looking to collaborate on larger team based projects where I can learn more about back-end intergration.

- 
-  📫 How to reach me:

name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: pemtajo/badge-readme@main
        with:       
          CREDLY_USER: <username_credly> # optional, but default will use the same from github

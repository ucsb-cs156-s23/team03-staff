Set up a team deployment for prod on Dokku

# Acceptance Criteria:

- [ ] On your team's dokku instance, there is an app
      called team02-prod
      ```
      dokku apps:create team02-prod
      ```

- [ ] On your team's dokku instance, there is an database
      called team02-prod-db linked to your team02-prod app
      ```
      dokku postgres:create team02-prod-db
      dokku postgres:link team02-prod-db team02-prod
      ```

- [ ] Your team's team02-prod app is configured for 
      Google OAuth
        
- [ ] The main branch is deployed on Dokku at, for example,
      <https://team02-prod.dokku-xx-cs.ucsb.edu> (substituting your
      own team name for `f22-5pm-1`).
- [ ] A links to both your team's production is added to the top of your team's `README.md` file, replacing the `TODO` entry.



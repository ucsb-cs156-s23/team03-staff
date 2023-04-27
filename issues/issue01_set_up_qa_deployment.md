Set up a team deployment for qa on Dokku

# Acceptance Criteria:

- [ ] On your team's dokku instance, there is an app
      called team02-qa
      ```
      dokku apps:create team02-qa
      ```

- [ ] On your team's dokku instance, there is an database
      called team02-qa-db linked to your team02-qa app
      ```
      dokku postgres:create team02-qa-db
      dokku postgres:link team02-qa team02-qa-db
      ```

- [ ] Your team's team02-qa app is configured for 
      Google OAuth
        
- [ ] The main branch is deployed on Dokku at, for example,
      <https://team02-qa.dokku-xx-cs.ucsb.edu> (substituting your
      own team name for `f22-5pm-1`).
- [ ] A links to your team's qa is added to your team's `README.md` file, replacing the `TODO` entry.



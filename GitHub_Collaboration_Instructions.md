# Set up
1. Open terminal
2. Go to the desired directory e.g. Desktop (cd Desktop)
3. This is a one time step:
    * git clone https://github.com/nikolabaci98/kepler-exoplanet-search-results.git
    * cd kepler-exoplanet-search-results
    * git remote add upstream https://github.com/nikolabaci98/kepler-exoplanet-search-results.git
    * git branch (it will show all the branches in this repo)
    * git checkout -b “nikola’s_branch” (create a new working branch)
    * git branch (will show to branches, the one with the star (*) is the working branch)

# Everyday project update
1. cd Desktop/kepler-exoplanet-search-results 
2. git checkout nikola’s_branch (will switch to this branch)
3. git branch (to confirm the working branch)
4. jupyter notebook (work on your code, save it)
5. git add *
5. git commit -m “your_message”
7. git push (if for the first time then you should do: git push --set-upstream origin nikola's_branch)
8. Create a pull request (in the github website, the repository will now have an additional branch. All the changes are saved into this branch)
The team mate will go over the changes and accept or comment for improvement or clarification
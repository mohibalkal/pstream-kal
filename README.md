# P-Stream

[![Sudo-Flix Image](.github/Sudo-Flix.png)](https://docs.undi.rest)  

"*Better I do it than use some virus sketchy site or support some pedo*" - Pas


"*I do not endorse piracy of any kind I simply enjoy programming and large user counts.*" - BadDev

## Links And Resources
| Service        | Link                                                             | Source Code                                              |
|----------------|------------------------------------------------------------------|----------------------------------------------------------|
| Sudo-Flix/P-Stream Docs | [sudo-docs](https://docs.undi.rest)                          | [source code](https://github.com/sussy-code/docs)        |
| Extension      | [extension](https://docs.undi.rest/extension)                | [source code](https://github.com/sussy-code/browser-ext) |
| Backend        | [fifthwit backend](https://server.fifthwit.net)                    | [source code](https://github.com/FifthWit/open-backend)     |
| Frontend       | [P-Stream](https://pstream.org)                | you're looking at it        |



## Referrers
- [FMHY (Voted as #1 multi-server streaming site of 2024)](https://fmhy.net)
- [Piracy Subreddit Megathread](https://www.reddit.com/r/Piracy/s/iymSloEpXn)
- [Toon's Instances](https://erynith.github.io/movie-web-instances)
- [Entertainment Empire](https://discord.gg/8NSDNEMfja)
- Search Engines: DuckDuckGo, Bing, Google
- Rentry.co
- BadDev said to use it instead of Sudo-Flix 🤷‍♂️


## Running Locally
Type the following commands into your terminal / command line to run P-Stream locally
```bash
git clone https://github.com/Pasithea0/smov.git
cd smov
git pull
pnpm install
pnpm run dev
```
Then you can visit the local instance [here](http://localhost:5173) or, at local host on port 5173.


## Updating a P-Stream Instance
To update a P-Stream instance you can type the below commands into a terminal at the root of your project.
```bash
git remote add upstream https://github.com/Pasithea0/smov.git
git fetch upstream # Grab the contents of the new remote source
git checkout <YOUR_MAIN_BRANCH>  # Most likely this would be `origin/main`
git merge upstream/production
# * Fix any conflicts present during merge *
git add .  # Add all changes made during merge and conflict fixing
git commit -m "Update sudo-flix instance (merge upstream/main)"
git push  # Push to YOUR repository
```


## [Contact Me / Join the Discord](https://discord.gg/7z6znYgrTG)

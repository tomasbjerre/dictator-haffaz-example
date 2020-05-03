# Haffaz Example

An example usage of [Haffaz](https://github.com/tomasbjerre/dictator-haffaz).

Try it by running `npm install`:

```bash
> dictator-haffaz-example@0.0.1 prepare /home/bjerre/workspace/dictator/dictator-haffaz-example
> npx haffaz@0.0.18

  _                __    __               
 | |__     __ _   / _|  / _|   __ _   ____
 | '_ \   / _` | | |_  | |_   / _` | |_  /
 | | | | | (_| | |  _| |  _| | (_| |  / / 
 |_| |_|  \__,_| |_|   |_|    \__,_| /___|
                                          
  Built with dictator-builder@0.0.19.
  https://github.com/tomasbjerre/dictator-builder

Setup some git stuff.
    Up to date: .gitignore should have lines
    Applying: copy pre-commit-hook.txt to .git/hooks/pre-commit
    Applying: pre-commit have chmod 0755
    Applying: copy gitmessage.txt to .gitmessage
```

Notice: `Applying: ....`. The Haffaz dictator dictates what this repository should look like. So that this code does not need to be duplicated in all repositories!

## Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

#### Inputs

#### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

#### Outputs

#### `time`

The time we greeted you.

#### Example usage

```yml
uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: "Mona the Octocat"
```

GitCommands

```bash
git add action.yml entrypoint.sh Dockerfile README.md
git commit -m "My first action is ready"
git tag -a -m "My first action release" v5
git push --follow-tags
```

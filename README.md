# GitHub Actions Debugger

Output all environment variables for debug purpose.

## Usage

In your actions yaml:

```yaml
- uses: 98w/action-debugger@v0.1
```

Output:
```bash
INPUT_EVENT=''
HOME='/github/home'
GITHUB_REF='refs/tags/v0.1'
GITHUB_SHA='f8514e4841034367b78717c5f85b7599a00631db'
GITHUB_REPOSITORY='98w/action-debugger'
GITHUB_RUN_ID='68028435'
GITHUB_RUN_NUMBER='2'
GITHUB_ACTOR='98w'
GITHUB_WORKFLOW='.github/workflows/example.yml'
GITHUB_HEAD_REF=''
GITHUB_BASE_REF=''
GITHUB_EVENT_NAME='push'
GITHUB_WORKSPACE='/github/workspace'
GITHUB_ACTION='waction-debugger'
GITHUB_EVENT_PATH='/github/workflow/event.json'
RUNNER_OS='Linux'
RUNNER_TOOL_CACHE='/opt/hostedtoolcache'
RUNNER_TEMP='/home/runner/work/_temp'
RUNNER_WORKSPACE='/home/runner/work/action-debugger'
ACTIONS_RUNTIME_URL='https://pipelines.actions.githubusercontent.com/3I8QBeicz8h1ECaotBOc7cTMCgFs0jKlGPcfb53OYUTMNLtJOl/'
ACTIONS_RUNTIME_TOKEN='***'
ACTIONS_CACHE_URL='https://artifactcache.actions.githubusercontent.com/3I8QBeicz8h1ECaotBOc7cTMCgFs0jKlGPcfb53OYUTMNLtJOl/'
GITHUB_ACTIONS='true'
```

## TODO

* Support custom environment variable.

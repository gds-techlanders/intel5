name: notify
on: 
  push:
    branches:
      - main
      - dev
jobs:
  build: 
    runs-on: ubuntu-latest
    steps:
      - name: step1
        run: |
          echo "${{ vars.GREETINGS }} from $name $lastname, job1 of workflow1 running in environment $environment"
          sleep 10
          hostname

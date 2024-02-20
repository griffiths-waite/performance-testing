# Performance testinc POC

## Installing

```
pnpm install
```

## Available pnpm Commands

`pnpm build`
Run the Typescript compiler to produce a production build in **./dist**.

## Running the performance tests
Runs the performance tests using the default settings. To do this, run the below command:
```pnpm perf```

### Cli argumnets

You can find below the cli args you can pass in and the default values:

| cli arg    | default value | description
| -------- | ------- | ------- |
| --dry-run  | false    | Run the performance tests without saving the results to `benchmark/results.json`
| -noticeableThreshold | 0.1     | Set the threshold when difference in performance tests are considered noticable. Must be a value greater then 0 but less than 1


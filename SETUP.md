# GitHub profile setup

Copy these files into the root of your `demo-23home/demo-23home` profile repository:

```text
README.md
.github/
└── workflows/
    └── snake.yml
```

Then complete these steps:

1. Push the files to the repository's default branch.
2. Open **Settings → Actions → General → Workflow permissions**.
3. Select **Read and write permissions**, then save.
4. Open the **Actions** tab and manually run the contribution-snake workflow once.

After the first successful runs:

- `snake.yml` publishes light and dark contribution animations to the `output` branch.

The workflow continues updating automatically once per day.
